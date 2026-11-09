# Mikhail Sayapin — Python: сбор данных, автоматизация, торговые боты, AI-интеграции
 
15+ лет работы с данными в e-commerce и ритейле; последние годы — Python-сервисы сбора и обработки данных, торговые боты и интеграции с LLM.
 
📫 sayapinm@gmail.com
 
## Специализация
 
- **Сбор и обработка данных** — REST/WebSocket API, парсинг, нормализация, контроль полноты и качества данных, регулярные отчёты
- **Trading Systems / Algotrading** — real-time обработка market-data по 700+ инструментам, спот/фьючерсы/Earn на Gate.io, исполнение ордеров с проверкой по балансам, внутрибиржевой арбитраж
- **AI Integrations** — Telegram-боты с LLM (Anthropic Claude, Gemini), Claude Vision, автоматизация контента и бизнес-процессов
## Стек
 
**Языки и фреймворки:** Python, Asyncio, Aiohttp, Aiogram
**Данные:** PostgreSQL, SQLite, SQLAlchemy, Redis
**AI/ML:** Anthropic Claude API, Gemini API, LLM-интеграции
**Инфраструктура:** Linux VPS, systemd, cron, Docker
**Trading:** Gate.io API, Bybit WebSocket, MOEX ISS, T-Invest API, Pine Script, TradingView
**Сбор данных:** REST, WebSocket, Playwright, антидетект-браузеры
 
## Проекты-витрины (без раскрытия торговой логики/NDA)
 
Шесть репозиториев ниже — рабочий код с урезанной коммерческой логикой (подробности и что именно скрыто — в README каждого репо).
 
### Trading Systems / Algotrading
 
| Repo | Что показывает |
|---|---|
| [gate-funding-arbitrage-bot](https://github.com/sayapinm/gate-funding-arbitrage-bot) | Дельта-нейтральный арбитражный бот на 700+ инструментов: спот + Earn-лендинг + шорт фьючерса, две независимые ставки дохода. Верификация ордеров по реальным балансам, автоматический rollback при частичном исполнении |
| [gate-basis-arbitrage-bot](https://github.com/sayapinm/gate-basis-arbitrage-bot) | Базисный (спред) арбитраж со ступенчатым входом/выходом и PnL-ориентированной логикой закрытия позиций |
| [gate-basis-bollinger-bot](https://github.com/sayapinm/gate-basis-bollinger-bot) | Статистический вариант: вход по пробою полосы Боллинджера на базисе, двухскоростная архитектура (медленный скан + быстрый монитор) |
 
### AI Integrations
 
| Repo | Что показывает |
|---|---|
| [chart-zone-vision-bot](https://github.com/sayapinm/chart-zone-vision-bot) | Telegram-бот: Claude Vision извлекает торговые зоны со скриншота графика, мультисигнальный детектор (8 сигналов слияния) подтверждает вход, мониторинг через Bybit WebSocket |
| [social-media-autopilot](https://github.com/sayapinm/social-media-autopilot) | SaaS автопостинга: Gemini генерирует контент и публикует его в Telegram/VK/Дзен/Instagram/MAX с тарифным биллингом — архитектурная выдержка |
 
### Сбор данных: MOEX Fundamentals Pipeline
 
| Repo | Что показывает |
|---|---|
| [moex-portfolio-advisor](https://github.com/sayapinm/moex-portfolio-advisor) | Сбор рыночных данных и фундаментальных показателей эмитентов МосБиржи из 3 источников (MOEX ISS, T-Invest API, SmartLab) со сверкой, анализом через Claude API и автоматической отчётностью в Telegram по расписанию |
 
## Опыт (кратко)
 
- **Dieffetech**, 2023 — н.в.: товарные данные и автоматизация — парсинг, AI-извлечение характеристик, контроль качества, каталог 10 тыс. SKU
- **Проектная работа**, 2023 — н.в.: торговые боты, сбор данных MOEX, AI-боты
- **МЫЛО-ОПТ**, 2015–2023: каталог 10 тыс. SKU, интеграции 1С → Битрикс → маркетплейсы
- **Яндекс**, 2010–2015: данные каталога e-commerce, обмен по CommerceML
## Контакты
 
Открыт к предложениям: сбор данных и парсинг, автоматизация, торговые системы, AI-интеграции. Удалённый формат.
 
📫 sayapinm@gmail.com · [github.com/sayapinm](https://github.com/sayapinm)
