<h1 align="center">Матвей Прохоров | LLM Developer & Data Scientist</h1>

<p align="center">
  <a href="https://t.me/pip_install_matvey">
    <img src="https://img.shields.io/badge/Telegram-%40pip__install__matvey-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
  </a>
  <a href="mailto:workhorov@gmail.com">
    <img src="https://img.shields.io/badge/Email-workhorov%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>



### Обо мне

Я учусь на 3-м курсе ПМИ (**Центральный Университет**, специализация «Искусственный интеллект»). 
Занимаюсь коммерческой разработкой асинхронных сервисов, R&D в области анализа данных и построением архитектур на базе **LLM / RAG**. 


### Технический стек

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
</p>

* **AI / LLM / RAG:** `LangChain` | `Prompt Engineering` | `Vector Search (ChromaDB, FAISS)` | `Hugging Face` | `PyTorch`
* **Data Engineering:** `DWH Architecture` | `SQLAlchemy 2.0` | `Alembic` | `SCD2`
* **Machine Learning & Tools:** `CatBoost` | `XGBoost` | `Scikit-learn` | `Optuna` | `Pandas` | `NumPy` | `Aiogram 3`

---

### Основные проекты 

#### [SIMILIS](https://github.com/lkazumin/similis) — R&D-платформа атрибуции артефактов
> **98 / 100 баллов по итогам оценивания**
* Разработал CV/NLP пайплайн для автоматического извлечения признаков материальной культуры и генерации структурированных описаний (`auto_description`).
* Применил Data-Centric подход для обработки сырого мультимодального корпуса исторических данных.

#### [RAG Movie Agent](https://github.com/lkazumin/rag_movie_agent) — Персонализированный ИИ-агент для рекомендации фильмов
* Спроектировал гибридную RAG-систему на базе `LangChain` и `ChromaDB` (векторизовано 10k+ сюжетов).
* Интегрировал реляционную БД через `SQLAlchemy 2.0` для динамического исключения уже просмотренных пользователем фильмов на этапе векторного поиска.

#### [Carsharing Data Infrastructure](https://github.com/lkazumin/carsharing_db_project) — Аналитический слой и ETL
* Спроектировал физическую структуру базы данных в `PostgreSQL` 
* Реализовал инкрементальный ETL-пайплайн на `PL/pgSQL` с поддержкой историчности изменений по **SCD Type 2**.
* Внедрил отказоустойчивую систему мягкой валидации данных на триггерах: аномальные строки изолируются, упаковываются в `JSONB` и логируются без падения транзакции mass-load загрузки.

#### [CoffeeShop Loyalty Bot](https://github.com/lkazumin/suda_coffee_bot) — Коммерческий бот в продакшене
* Разработал и вывел в прод асинхронный сервис лояльности для кофейни "Suda" в Москве.
* Реализовал транзакционную логику в `PostgreSQL` для полной защиты от фрода и повторных начислений.
