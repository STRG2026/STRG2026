<div align="center">

# Привет! Я STRG2026 

### Python • ML / AI • Backend

Разрабатываю прикладные ML/LLM-системы и backend-сервисы:
от retrieval-пайплайнов и локальных LLM до асинхронных API,
баз данных, тестов и контейнеризации.

</div>

---

##  Чем занимаюсь

- **ML / LLM:** RAG, embeddings, semantic search, локальные LLM;
- **Backend:** FastAPI, REST API, асинхронный Python, JWT/RBAC;
- **Data:** PostgreSQL, Redis, Chroma, SQLAlchemy, Alembic;
- **Infrastructure:** Docker, Docker Compose, GitHub Actions;
- **Engineering:** тестирование, API-документация, структурирование бизнес-логики и воспроизводимый локальный запуск.

## 🛠 Технологии

<p>
  <img src="https://img.shields.io/badge/Python-3.11+-3776AB?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/Ollama-000000?logo=ollama&logoColor=white" />
</p>

##  Избранные проекты

### [ML Interview Coach](https://github.com/STRG2026/ml_interview_coach)

Локальный тренажёр технических интервью по машинному обучению.

Система выполняет семантический поиск по учебным материалам,
генерирует вопросы, формирует эталонный ответ, оценивает ответ
пользователя и возвращает структурированную обратную связь.

**Стек:**  
`FastAPI` · `Ollama` · `Qwen` · `Chroma` · `RAG` · `Embeddings` · `Pydantic`

**Что реализовано:**
- локальная работа без отправки материалов во внешние LLM API;
- semantic retrieval по пользовательским конспектам;
- отдельная генерация вопроса и эталонного ответа;
- автоматическая оценка ответа по шкале 0–10;
- выявление ошибок и пропущенных тезисов;
- хранение контекста интервью по `session_id`;
- FastAPI API и консольный клиент.

 [Открыть проект](https://github.com/STRG2026/ml_interview_coach)

---

### [Room Booking Service](https://github.com/STRG2026/avito)

Backend-сервис для управления переговорными комнатами,
расписаниями и бронированиями.

**Стек:**  
`FastAPI` · `SQLAlchemy 2.0` · `asyncpg` · `PostgreSQL` · `Redis` ·
`Alembic` · `JWT` · `Pytest` · `Docker Compose` · `GitHub Actions`

**Что реализовано:**
- JWT-аутентификация;
- роли `admin` и `user`;
- асинхронная работа с PostgreSQL;
- управление комнатами и расписаниями;
- генерация временных слотов;
- защита от повторного бронирования;
- миграции Alembic;
- тесты и линтинг;
- CI через GitHub Actions;
- запуск всего окружения через Docker Compose;
- OpenAPI и Swagger UI.

 [Открыть проект](https://github.com/STRG2026/avito)

##  Как я подхожу к разработке

Мне важно, чтобы проект был не просто работающим кодом, а понятной инженерной системой:

- архитектуру можно быстро понять по README;
- проект воспроизводимо запускается локально;
- зависимости и конфигурация явно описаны;
- бизнес-логика отделена от инфраструктурного кода;
- API документирован;
- критичные сценарии покрываются тестами;
- проект можно автоматически проверить через CI.

---

<div align="center">

**GitHub:** [@STRG2026](https://github.com/STRG2026)

</div>
