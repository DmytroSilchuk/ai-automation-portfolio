# 03 · Support Ticket Routing + SLA Escalation

Every support email gets a category, priority P1 to P4, one named owner and a deadline, with a short written reason from AI. A watcher checks deadlines every 5 minutes and escalates: owner → team lead → owner of the business.

**Result in tests:** 85% → 100% correct routing after one prompt iteration · ~3 s per ticket · 3/3 escalation levels fired, 0 duplicates.

| File | Role |
|---|---|
| `ticket_routing_sla_escalation.json` | Gmail → AI classifier with reasoning → deadline in code → Sheets log → Telegram alert; SLA watcher with L0 / L1 / L2 |
| `setup_label_and_test_tickets.json` | One-off: creates the Gmail label and sends 13 test tickets |

| Priority | SLA |
|---|---|
| P1 | 30 min |
| P2 | 2 h |
| P3 | 4 h |
| P4 | 24 h |

**Stack:** n8n, OpenAI, Gmail, Google Sheets, Telegram.

📖 Full case: [Notion](https://glamorous-plume-2bc.notion.site/Support-Ticket-Routing-for-an-Online-Store-Every-Email-Gets-an-Owner-and-a-Deadline-4077d0aa93fd81d28ea7c1d8f000fc04)

---

🇺🇦 **Коротко:** кожен лист отримує категорію, пріоритет, відповідального і дедлайн; якщо ніхто не відповів вчасно, звернення ескалюється само.
