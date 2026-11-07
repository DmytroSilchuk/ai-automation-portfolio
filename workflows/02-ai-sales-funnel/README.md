# 02 · AI Sales Funnel: 24/7 Lead Qualification and a Weekly CEO Report

A website chatbot qualifies every lead by BANT and creates it in Zoho CRM with a score. Every morning AI reviews each dialogue; every Friday the CEO gets a short report in Telegram.

**Result in tests:** 8.8 s average reply · scoring error 7.5 → 1 point after 3 prompt versions · CEO report built in 36 s.

| File | Role |
|---|---|
| `WF1_chatbot_bant_qualification.json` | Chat → AI agent with Postgres memory → lead in Zoho CRM with score and calculation |
| `WF2_daily_dialogue_review.json` | Daily 09:00: lead + full dialogue → AI analyst → Google Sheets (mistakes, objections, prompt fix) |
| `WF3_weekly_ceo_report.json` | Friday 17:00: CRM metrics + dialogue analysis → AI report with structured output → Telegram |

**Stack:** n8n, OpenAI, Postgres, Zoho CRM, Google Sheets, Telegram.

📖 Full case: [Notion](https://glamorous-plume-2bc.notion.site/AI-Sales-Funnel-for-an-Agency-24-7-Lead-Qualification-and-a-Weekly-CEO-Report-3fa7d0aa93fd81d28916cae1d1c85de6)

---

🇺🇦 **Коротко:** чатбот на сайті кваліфікує ліди 24/7 і створює їх у CRM з балом, AI щодня розбирає діалоги, CEO щоп'ятниці отримує звіт у Telegram.
