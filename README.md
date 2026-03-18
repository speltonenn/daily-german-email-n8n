# daily-german-email-n8n
Daily German learning sentences via email using n8n and Claude AI
# 🇩🇪 Daily German Learning — n8n Workflow

An automated workflow that sends daily German practice sentences to your email every morning.

## What it does
- Runs every day at 8:00 AM
- Picks a new topic automatically (food, travel, work, family, etc.)
- Generates 5 German sentences at B1 level using Claude AI
- Each sentence includes a German version, English translation and key vocabulary
- Sends everything to your email

## Tech stack
- [n8n](https://n8n.io) — workflow automation
- [Claude API](https://anthropic.com) — AI sentence generation
- iCloud SMTP — email delivery

## Setup
1. Import `Dein tägliches Deutsch.json` into n8n
2. Add your Anthropic API key to the HTTP Request node
3. Add your iCloud App-Specific Password to the email node
4. Activate the workflow

## Note
Never commit real API keys. Replace all credentials with your own before use.
