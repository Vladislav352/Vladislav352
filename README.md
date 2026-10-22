# Владислав Арсентьев · AI-интегратор

Собираю рабочие системы из ИИ-агентов, данных и интерфейсов для компаний и для себя. Любимый стек: Python stdlib + SQLite/Postgres, TypeScript + React там, где нужен интерфейс, OpenClaw как агентская платформа, Claude Code и Codex как напарники. Всё ниже работает в продакшене, а не в демо.

*AI integrator. I build working systems out of AI agents, data pipelines and interfaces: for businesses (marketplace analytics, regulatory assistants, document checking, company dashboards) and for myself (a personal command center and a memory warehouse for my agents).*

## Для бизнеса

| Проект | Что это | Стек |
|---|---|---|
| [wb-monitor](https://github.com/Vladislav352/wb-monitor) | Мониторинг конкурентов и своих продаж на Wildberries и Ozon: сбор, оценка продаж с автокалибровкой, позиции, алерты, Telegram-бот, ежедневный разбор от LLM, дашборд на 12 вкладок | Python stdlib, SQLite, Chart.js, launchd |
| [finpulse](https://github.com/Vladislav352/finpulse) | Фин.пульс: выручка, маржа, ДРР и выплаты по пяти кабинетам маркетплейсов, план из Google-таблицы, HTML-дашборд дважды в день | Python, TrueStats API, Google Sheets, 1С OData |
| [regbot](https://github.com/Vladislav352/regbot) | РегБот: RAG-ассистент по регуляторике медизделий, косметики и таможни с цитатами, проверками реестров и дайджестом | Python, SQLite FTS5, Telegram Bot API, Codex CLI |
| [DocChecker](https://github.com/Vladislav352/DocChecker) | Проверка технических документов на 300 страниц: LanguageTool, правила оформления, LLM-проверка смысла, результат как комментарии Word | Python, Tkinter, LanguageTool, python-docx |
| [company-command-center](https://github.com/Vladislav352/company-command-center) | Командный центр компании: управленческий дашборд, корпоративный агент в Битрикс24 и Telegram через read-only шлюз данных, VPS-инфраструктура | HTML/JS, OpenClaw, Supabase, Docker, Caddy |
| [process-discovery-kit](https://github.com/Vladislav352/process-discovery-kit) | Набор для AI-аудита бизнес-процессов: опросники, инвентарь процессов, карта в Miro через API | Markdown, CSV, Node.js, Miro REST |

## Для себя

| Проект | Что это | Стек |
|---|---|---|
| [command-center](https://github.com/Vladislav352/command-center) | Личная операционная система: радиальная карта сфер → проектов → задач, чат с агентом в каждом круге, живые терминалы агентов | Vite, React, shadcn, Hono, Vercel AI SDK, OpenClaw |
| [agent-memory](https://github.com/Vladislav352/agent-memory) | Общая память двух агентов (append-only события → детерминированный канон) и склад на Postgres + pgvector с гибридным поиском по 11 тыс. чанков | Python, Postgres, pgvector, Ollama |
| [finance-relay](https://github.com/Vladislav352/finance-relay) | Агент видит личные финансы без доступа к банкам: сторож читает СМС и уведомления на Mac, режет OTP, отдаёт JSONL | Python, macOS Messages, launchd |

## Как я работаю

- Сначала увидеть, что уже есть, потом проектировать. Прототип за день, потом живые данные.
- Честные цифры: каждое число подписано источником, оценка никогда не выглядит фактом.
- Агент читает, не пишет; секреты вне репозитория; скрипты по расписанию падают громко.
- Один файл HTML лучше фреймворка, если его можно открыть без сервера.

Telegram: [@Skit888](https://t.me/Skit888) · канал [AI Way For](https://t.me/AI_Way_For)
