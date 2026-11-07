# 01 · AI Voice Agent for B2B Sales

An AI phone agent calls every new lead 2 minutes after the request, qualifies it by BANT in Ukrainian and leaves a scored card in Zoho CRM. Every morning AI reviews all calls and suggests script fixes.

**Result in tests:** 2 min 13 s from a new lead to the first call · 8/8 calls ended with a scored lead · under 30 s from hang-up to an updated CRM card.

| File | Role |
|---|---|
| `V0_website_form_to_crm_to_ai_call.json` | Website form → lead in Zoho → call trigger (demo) |
| `V1_voice_agent_init_crm_data.json` | Gives the agent the client's name and company from CRM at call start |
| `V2_postcall_bant_score_to_crm.json` | Transcript → AI extracts BANT facts → code calculates score and status → CRM |
| `V3_new_lead_ai_call_in_2_min.json` | New lead → 2-min pause → phone and working-hours check → Happ API call |
| `V4_daily_ai_call_review.json` | Daily 09:15: every call reviewed by AI, one row per call in Google Sheets |

**Stack:** n8n, Happ.tools (ElevenLabs), OpenAI, Zoho CRM, Google Sheets.
**Why it can be trusted:** AI only extracts facts; the score and status are calculated in code.

📖 Full case: [Notion](https://glamorous-plume-2bc.notion.site/AI-Voice-Agent-for-B2B-Sales-Calls-Every-New-Lead-in-2-Minutes-3fe7d0aa93fd81419026e3ac7923a05c)

---

🇺🇦 **Коротко:** AI-агент дзвонить кожному новому ліду через 2 хвилини, кваліфікує за BANT і залишає в CRM картку з балом. Щоранку AI розбирає всі дзвінки і підказує, як покращити скрипт.
