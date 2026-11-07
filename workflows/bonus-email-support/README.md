# Email Support on Autopilot

AI reads every support email, sets priority P1 to P4, category and tone, writes a draft reply or an auto-reply, labels the email and logs it to Google Sheets. On top: period reports and an AI agent that answers analytics questions in chat.

| File | Role |
|---|---|
| `email_support_automation.json` | Gmail → filter → AI classifier → router (draft / auto-reply / label) → Sheets log |
| `report_for_period.json` | Support report for any period |
| `compare_periods.json` | Compares two periods |
| `analytics_ai_agent_chat.json` | AI agent in chat that answers questions about support stats |

**Stack:** n8n, OpenAI, Gmail, Google Sheets.

---

🇺🇦 **Коротко:** AI сортує листи підтримки, готує чернетки відповідей, веде журнал і відповідає на питання про статистику в чаті.
