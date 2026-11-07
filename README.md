<div align="center">

# Dmytro Silchuk · AI Automation Portfolio

**Entrepreneur since 2011 · Business audit · Automation & AI**

I find where a business loses money and time, then get it back with automation and AI.
Audit first, tools second.

🇬🇧 English · [🇺🇦 Українська](README.uk.md)

[![Portfolio](https://img.shields.io/badge/Portfolio-Notion-000000?style=for-the-badge&logo=notion&logoColor=white)](https://glamorous-plume-2bc.notion.site/AI-Automator-Portfolio-Dmytro-Silchuk-3ba7d0aa93fd81e49f8ff1a566f046db)
[![Telegram](https://img.shields.io/badge/Telegram-@silchuk__d-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/silchuk_d)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Dmytro%20Silchuk-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/%D0%B4%D0%BC%D0%B8%D1%82%D1%80%D0%BE-%D1%81%D1%96%D0%BB%D1%8C%D1%87%D1%83%D0%BA-a35b58220/)
[![Email](https://img.shields.io/badge/Email-Write%20me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dmitriy.silchuk@gmail.com)

</div>

---

## About me

I'm Dmytro Silchuk, an entrepreneur since 2011. Logistics with Nova Poshta, a dealership of machinery from the USA, Europe and China, real estate, a hotel and restaurant complex. Over these years I've learned first-hand where a business quietly loses money: forgotten leads, manual routine, decisions made blind.

That's why I don't sell trendy «AI implementations». First I get to know your business as if it were my own, then I build automation that pays for itself. Much of what I offer, I've tested on my own projects first.

**I talk to you as one entrepreneur to another.**

---

## What's inside

This repository holds the n8n workflows behind the cases in my [Notion portfolio](https://glamorous-plume-2bc.notion.site/AI-Automator-Portfolio-Dmytro-Silchuk-3ba7d0aa93fd81e49f8ff1a566f046db). Each folder is one system you can import into n8n and adapt.

| # | System | What it does for the business | Result | Workflows |
|---|---|---|---|---|
| 01 | **AI Voice Agent for B2B Sales** | Calls every new lead 2 minutes after the request, qualifies by BANT, leaves a scored card in CRM | 2 min 13 s to the first call · 8/8 calls scored | [`01-ai-voice-agent`](workflows/01-ai-voice-agent) |
| 02 | **AI Sales Funnel** | Website chatbot qualifies leads 24/7, AI reviews every dialogue, CEO gets a weekly report | 8.8 s reply · scoring error 7.5 → 1 | [`02-ai-sales-funnel`](workflows/02-ai-sales-funnel) |
| 03 | **Support Ticket Routing + SLA** | Every email gets a category, priority, owner and deadline; overdue tickets escalate by themselves | 85% → 100% correct routing | [`03-ticket-routing-sla`](workflows/03-ticket-routing-sla) |
| + | **Email Support on Autopilot** | AI sorts support emails P1 to P4, drafts replies, logs everything, answers analytics questions in chat | | [`bonus-email-support`](workflows/bonus-email-support) |
| + | **Sales Intelligence for the CEO** | Daily funnel report, weekly deal health alerts, revenue forecast | | [`bonus-sales-intelligence`](workflows/bonus-sales-intelligence) |

Cases 04 (lead processing for an investment project) and 05 (call analysis for a bakery) are in the Notion portfolio; their workflows are available on request.

---

## How I work

| | |
|---|---|
| 🔎 **1 · Audit** | I find where the money leaks: processes, funnel, team, numbers. Output: losses in money and a solution with a clear payback. |
| 🧩 **2 · Architecture** | Data flow between CRM, telephony, email and messengers. AI where it earns money, clear rules everywhere else. |
| 🛠️ **3 · Build** | n8n, APIs, AI agents with output checks. Zero manual steps. |
| 🧪 **4 · Test** | I break it before your clients do: real scenarios and edge cases on live data. |
| 🚀 **5 · Launch** | Live in production, a short guide for the team, results in reports. |
| 📈 **6 · Optimise** | Weekly metrics and AI reviews, prompts and rules tuned. Better every month. |

---

## Tech stack

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Zoho CRM](https://img.shields.io/badge/Zoho%20CRM-E42527?style=flat-square&logo=zoho&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=flat-square&logo=googlesheets&logoColor=white)
![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white)
![ElevenLabs](https://img.shields.io/badge/ElevenLabs-000000?style=flat-square&logo=elevenlabs&logoColor=white)

Voice agents: Happ.tools (ElevenLabs engine) · Speech-to-text: AssemblyAI, Whisper · LLM access: OpenAI API, OpenRouter

---

## How to use a workflow

1. In n8n: **Workflows → Import from file** and pick a `.json` from any folder.
2. Connect your own credentials (CRM, Google, Telegram, OpenAI). They are not included.
3. Replace the placeholders: `YOUR_GOOGLE_SHEET_ID`, `YOUR_TELEGRAM_CHAT_ID`, `YOUR_HAPP_ASSISTANT_ID`, `you@example.com`.
4. Test on sample data before you activate it.

> All personal data, IDs and keys have been removed. The prompts and business logic are kept as they are.

---

<div align="center">

**Want to know where your business loses money? Let's start with an audit.**

[Telegram](https://t.me/silchuk_d) · [LinkedIn](https://www.linkedin.com/in/%D0%B4%D0%BC%D0%B8%D1%82%D1%80%D0%BE-%D1%81%D1%96%D0%BB%D1%8C%D1%87%D1%83%D0%BA-a35b58220/) · [Email](mailto:dmitriy.silchuk@gmail.com) · [Portfolio](https://glamorous-plume-2bc.notion.site/AI-Automator-Portfolio-Dmytro-Silchuk-3ba7d0aa93fd81e49f8ff1a566f046db)

</div>
