# Григорий Безруков

**Data Scientist** · классический ML и NLP/LLM · Москва

3 года в ритейле (Магнит, Inventive Retail Group) и строительстве (ФОДД): прогноз спроса и промо, отток и склонность к покупке, семантический поиск, text-to-SQL агенты. Веду задачи от постановки с бизнесом до продакшена и A/B-проверки эффекта.

**Сейчас:** Data Scientist в ФОДД — автоматизирую сложные бизнес-процессы с помощью ML, NLP и LLM.\
**Открыт к предложениям:** Data Scientist / ML-инженер (NLP, LLM).

## Проекты

**[Natural Language Video Search](https://github.com/GrishaTS/natural-language-video-search)** — диалоговый поиск по видеоархиву на естественном языке. LangGraph-агент разбирает запрос, уточняет у пользователя неоднозначные имена и адреса и собирает фильтр событий для системы видеонаблюдения. В исследовательской части сравнил CLIP, X-CLIP, CG-DETR и Qwen3-VL на бенчмарке QVHighlights: у Qwen3-VL-8B с оконной индексацией Recall@IoU≥0,5 — 0,67 против 0,54 у CLIP ViT-L/14.
`LangGraph` `FastAPI` `Qdrant` `vLLM` `PostgreSQL` `Vue 3` `Docker`

**[Natural Language Image Search](https://github.com/GrishaTS/natural-language-image-search)** — офлайн-галерея с поиском фотографий по текстовому описанию на русском. Дообучил ruCLIP на 993 парах «изображение — подпись», подписи сгенерировал через Qwen 2.5; веса выложены на [Hugging Face](https://huggingface.co/bezGriga/ruclip-finetuned-clip993).
`PyTorch` `ruCLIP` `FastAPI` `Qdrant` `MinIO` `Docker`

## Стек

- **ML:** Python, SQL, PyTorch, CatBoost, Scikit-learn, pandas, A/B-тесты
- **NLP и LLM:** LLM, RAG, семантический поиск, Qdrant
- **Данные и продакшен:** PostgreSQL, ClickHouse, Spark, Airflow, FastAPI, Docker, MLflow

## Контакты

[Telegram](https://t.me/bezGriga) · [bezgrisa@gmail.com](mailto:bezgrisa@gmail.com) · [LinkedIn](https://www.linkedin.com/in/grigoriy-bezrukov) · [Резюме (PDF)](https://github.com/GrishaTS/GrishaTS/blob/main/Безруков_Григорий_Data_Scientist.pdf)
