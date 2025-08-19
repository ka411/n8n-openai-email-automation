n8n-OpenAI Email Automation — Project Summary
This project is a production-minded workflow that turns your inbox into a smart, polite, and fast-responding assistant. Built on n8n for orchestration and OpenAI for language understanding, it automatically reads incoming Gmail messages, classifies them (e.g., Job Applications, Sponsorship Requests, Irrelevant/Other), and sends a tailored reply—while logging what happened and giving you control over edge cases.

What it does (at a glance)
Ingests email from Gmail in near-real time (via n8n Gmail Trigger).

Understands intent using an OpenAI GPT prompt that’s optimized for short, noisy emails.

Maps intent → action: chooses the right reply template, pulls in merge fields, and sends a response.

Keeps records: stores classifications, confidence, and email metadata (e.g., in Google Sheets/Notion/DB).

Improves over time: you can refine prompts, templates, and categories based on real conversations.

