<div align="center">

# Дмитро Сільчук · Портфоліо AI-автоматизації

**Підприємець з 2011 року · Аудит бізнесу · Автоматизація і AI**

Знаходжу, де бізнес втрачає гроші й час, і повертаю їх через автоматизацію з AI.
Спершу аудит, потім інструменти.

[🇬🇧 English](README.md) · 🇺🇦 Українська

[![Портфоліо](https://img.shields.io/badge/Портфоліо-Notion-000000?style=for-the-badge&logo=notion&logoColor=white)](https://glamorous-plume-2bc.notion.site/AI-Automator-Portfolio-Dmytro-Silchuk-3ba7d0aa93fd81e49f8ff1a566f046db)
[![Telegram](https://img.shields.io/badge/Telegram-@silchuk__d-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/silchuk_d)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Dmytro%20Silchuk-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/%D0%B4%D0%BC%D0%B8%D1%82%D1%80%D0%BE-%D1%81%D1%96%D0%BB%D1%8C%D1%87%D1%83%D0%BA-a35b58220/)
[![Email](https://img.shields.io/badge/Email-Написати-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dmitriy.silchuk@gmail.com)

</div>

---

## Про мене

Я Дмитро Сільчук, підприємець з 2011 року. Логістика з Новою Поштою, дилерство техніки зі США, Європи та Китаю, нерухомість, готельно-ресторанний комплекс. За ці роки я на власному досвіді дізнався, де бізнес тихо втрачає гроші: у забутих лідах, у ручній рутині, у рішеннях, які власник ухвалює наосліп.

Тому я не продаю модні «AI-впровадження». Спершу розбираюся у вашому бізнесі так, ніби він мій, а потім будую автоматизацію, яка окупається. Багато з того, що пропоную, я спершу перевірив на власних проєктах.

**Я говорю з вами як підприємець з підприємцем.**

---

## Що тут є

У цьому репозиторії лежать workflow n8n, на яких побудовані кейси з мого [портфоліо в Notion](https://glamorous-plume-2bc.notion.site/AI-Automator-Portfolio-Dmytro-Silchuk-3ba7d0aa93fd81e49f8ff1a566f046db). Кожна папка це окрема система, яку можна імпортувати в n8n і підлаштувати під себе.

| # | Система | Що дає бізнесу | Результат | Workflow |
|---|---|---|---|---|
| 01 | **AI-агент для продажів** | Дзвонить кожному новому ліду через 2 хвилини, кваліфікує за BANT, залишає в CRM картку з балом | 2 хв 13 с до першого дзвінка · 8/8 дзвінків з балом | [`01-ai-voice-agent`](workflows/01-ai-voice-agent) |
| 02 | **AI-воронка продажів** | Чатбот на сайті кваліфікує ліди 24/7, AI розбирає кожен діалог, CEO отримує звіт щоп'ятниці | відповідь за 8,8 с · похибка оцінки 7,5 → 1 | [`02-ai-sales-funnel`](workflows/02-ai-sales-funnel) |
| 03 | **Маршрутизація звернень + SLA** | Кожен лист отримує категорію, пріоритет, відповідального і дедлайн; прострочені ескалюються самі | 85% → 100% правильних маршрутів | [`03-ticket-routing-sla`](workflows/03-ticket-routing-sla) |
| + | **Email-підтримка на автопілоті** | AI сортує листи P1–P4, готує чернетки відповідей, веде журнал, відповідає на питання аналітики в чаті | | [`bonus-email-support`](workflows/bonus-email-support) |
| + | **Аналітика продажів для CEO** | Щоденний звіт по воронці, щотижневі алерти «здоров'я угод», прогноз виручки | | [`bonus-sales-intelligence`](workflows/bonus-sales-intelligence) |

Кейси 04 (обробка лідів для інвест-проєкту) і 05 (аналіз дзвінків для кондитерської) є в портфоліо в Notion; їхні workflow надаю на запит.

---

## Як я працюю

| | |
|---|---|
| 🔎 **1 · Аудит** | Рахую, де бізнес втрачає гроші: процеси, воронка, команда, цифри. На виході: втрати в грошах і рішення з зрозумілою окупністю. |
| 🧩 **2 · Архітектура** | Потік даних між CRM, телефонією, поштою і месенджерами. AI там, де він заробляє, решта на чітких правилах. |
| 🛠️ **3 · Збірка** | n8n, API, AI-агенти з контролем відповідей. Жодних ручних кроків. |
| 🧪 **4 · Тест** | Ламаю раніше, ніж це зроблять клієнти: реальні сценарії і крайні випадки на живих даних. |
| 🚀 **5 · Запуск** | Система в бойовому режимі, коротка інструкція для команди, результат у звітах. |
| 📈 **6 · Оптимізація** | Метрики і AI-розбори щотижня, промпти й правила підкручуються. Система стає кращою щомісяця. |

---

## Інструменти

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

Голосові агенти: Happ.tools (рушій ElevenLabs) · Розпізнавання мови: AssemblyAI, Whisper · Доступ до LLM: OpenAI API, OpenRouter

---

## Як використати workflow

1. У n8n: **Workflows → Import from file** і оберіть `.json` з потрібної папки.
2. Підключіть свої облікові дані (CRM, Google, Telegram, OpenAI). Їх у файлах немає.
3. Замініть заглушки: `YOUR_GOOGLE_SHEET_ID`, `YOUR_TELEGRAM_CHAT_ID`, `YOUR_HAPP_ASSISTANT_ID`, `you@example.com`.
4. Перевірте на тестових даних і лише потім вмикайте.

> Усі персональні дані, ID і ключі прибрані. Промпти і бізнес-логіка залишені як є.

---

<div align="center">

**Хочете знати, де ваш бізнес втрачає гроші? Почнімо з аудиту.**

[Telegram](https://t.me/silchuk_d) · [LinkedIn](https://www.linkedin.com/in/%D0%B4%D0%BC%D0%B8%D1%82%D1%80%D0%BE-%D1%81%D1%96%D0%BB%D1%8C%D1%87%D1%83%D0%BA-a35b58220/) · [Email](mailto:dmitriy.silchuk@gmail.com) · [Портфоліо](https://glamorous-plume-2bc.notion.site/AI-Automator-Portfolio-Dmytro-Silchuk-3ba7d0aa93fd81e49f8ff1a566f046db)

</div>
