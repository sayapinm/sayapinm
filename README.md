# Mikhail Sayapin — Python Developer (Trading Systems / AI)

20+ лет коммерческой разработки, последние годы — высоконагруженный Python-backend, алготрейдинг и AI-интеграции в продакшене.

📫 sayapinm@gmail.com

## Специализация

- **Trading Systems / Algotrading** — real-time обработка market-data, интеграция с биржевыми API (спот/фьючерсы, несколько площадок), исполнение ордеров с контролем задержки, арбитражные стратегии (меж- и внутрибиржевые)
- **AI Integrations** — Telegram/мессенджер-боты с LLM (OpenAI, Gemini, Anthropic Claude), RAG-логика, автоматизация бизнес-процессов и клиентской поддержки
- **SaaS / высоконагруженный backend** — микросервисная архитектура, event-driven системы (Kafka/RabbitMQ), масштабирование до 1M+ пользователей без деградации SLA

## Стек

**Языки и фреймворки:** Python, FastAPI, Django, Django REST Framework, Flask, Asyncio, Aiogram, Aiohttp
**Данные:** PostgreSQL, ClickHouse, Redis, SQLAlchemy, NoSQL
**Очереди и стриминг:** Apache Kafka, RabbitMQ, Celery, WebSocket
**AI/ML:** OpenAI API, Anthropic Claude API, LLM-интеграции, RAG, PyTorch, TensorFlow
**Инфраструктура:** Docker, Kubernetes, CI/CD (GitLab CI), Prometheus, Grafana, ELK
**Trading:** Binance API, Bybit API, OKX API, Gate.io API, MOEX API, ccxt, Pine Script, TradingView, WebSocket market-data streams
**API:** REST, gRPC, OAuth2

## Проекты-витрины (без раскрытия торговой логики/NDA)

Шесть репозиториев ниже — рабочий код с урезанной коммерческой логикой (подробности и что именно скрыто — в README каждого репо). Сгруппированы по тем же трём направлениям, что и специализация выше.

### Trading Systems / Algotrading

| Repo | Что показывает |
|---|---|
| [gate-funding-arbitrage-bot](https://github.com/sayapinm/gate-funding-arbitrage-bot) | Дельта-нейтральный арбитражный бот для Gate.io: спот + Earn-лендинг + шорт фьючерса, две независимые ставки дохода. Верификация ордеров по реальным балансам, автоматический rollback при частичном исполнении |
| [gate-basis-arbitrage-bot](https://github.com/sayapinm/gate-basis-arbitrage-bot) | Базисный (спред) арбитраж со ступенчатым входом/выходом и PnL-ориентированной логикой закрытия позиций |
| [gate-basis-bollinger-bot](https://github.com/sayapinm/gate-basis-bollinger-bot) | Статистический вариант: вход по пробою полосы Боллинджера на базисе, двухскоростная архитектура (медленный скан + быстрый монитор) |

### AI Integrations

| Repo | Что показывает |
|---|---|
| [chart-zone-vision-bot](https://github.com/sayapinm/chart-zone-vision-bot) | Telegram-бот: Claude Vision извлекает торговые зоны со скриншота графика, мультисигнальный детектор (8 сигналов слияния) подтверждает вход, мониторинг через Bybit WebSocket |
| [social-media-autopilot](https://github.com/sayapinm/social-media-autopilot) | SaaS автопостинга: Gemini генерирует контент и публикует его в Telegram/VK/Дзен/Instagram/MAX с тарифным биллингом — архитектурная выдержка |

### MOEX Fundamentals Pipeline

| Repo | Что показывает |
|---|---|
| [moex-portfolio-advisor](https://github.com/sayapinm/moex-portfolio-advisor) | Пайплайн сбора рыночных данных и фундаментальных показателей эмитентов МосБиржи (MOEX ISS, T-Invest API, SmartLab) с анализом через Claude API и автоматической отчётностью в Telegram по расписанию |

## Опыт (кратко)

- **Dieffetech** (SaaS, FinTech, eCommerce, AI), 2023 — н.в. — проектирование высоконагруженных backend-систем (10k–1M+ пользователей), переход на микросервисы, разработка систем алготрейдинга и AI-ботов
- **Торговая компания МЫЛО-ОПТ**, 2015–2023 — eCommerce-платформа, интеграции с 1С, службами доставки, банками
- **Яндекс**, 2010–2015 — eCommerce-платформа, обработка 800k+ заказов/сутки
- **Алкогольная Сибирская группа**, 2005–2010 — учётные системы, интеграция с торговым оборудованием

## Контакты

Открыт к предложениям в направлениях Trading Systems, AI Integrations, SaaS Backend. Удалённый формат.

📫 sayapinm@gmail.com · [github.com/sayapinm](https://github.com/sayapinm)
