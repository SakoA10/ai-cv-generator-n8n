# AI CV Generator (n8n + OpenAI)

A real-world CV generator built with n8n and OpenAI.
The user fills a form, the AI cleans and improves the content (without inventing facts), and the CV is emailed automatically.

## What the AI Does

- Improves wording and fixes grammar (same meaning only)
- Never invents facts (no fake companies, roles, dates, or skills)
- Normalizes capitalization and removes weak/invalid skills

## Workflow Overview

![Workflow](screenshots/workflow.png)

## CV Form

![Form 1](screenshots/form-1.png)
![Form 2](screenshots/form-2.png)
![Form 3](screenshots/form-3.png)

## Email Result

![Email 1](screenshots/email-1.png)
![Email 2](screenshots/email-2.png)

## Tech Stack

- n8n (localhost)
- OpenAI (Chat)
- Gmail API

## Notes

- Free-text inputs supported
- Missing data is omitted automatically
- Built for realism, not hallucinations
