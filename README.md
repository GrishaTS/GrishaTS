# Григорий Безруков

**Data Scientist** · NLP, LLM, поиск · Москва

1,5 года коммерческой ML-разработки: поиск и ранжирование, NLP, LLM-агенты, распознавание речи, компьютерное зрение. Довожу модели до прода: от исследования данных и выбора модели до API, мониторинга качества и переобучения. Студент 4 курса ФКН ВШЭ, «Программная инженерия».

## Опыт

**fodd** · с апреля 2026. Сервис сопоставления строк строительных смет со справочником работ из 5 651 позиции. Обработка сметы сократилась с 1–2 недель работы четырёх человек до 1–2 дней одного: 70% строк сервис проставляет сам. Top-1 на нижнем уровне справочника 85,1% (top-5 95,4%): каскад по уровням, bi-encoder с hard negatives и listwise-реранкер.
`PyTorch` `BM25` `bi-encoder` `Qdrant` `FastAPI` `PostgreSQL` `MLflow`

**Фриланс в команде senior ML-инженера** · апрель 2025 – май 2026, заказчики под NDA:

- диалоговый поиск по видеоархиву на LangGraph-агенте, работает в проде;
- анализ видеозаписей на признаки коррупции: диаризация, распознавание речи (GigaAM-v3, WER 0,62 против 0,81 у Whisper) и LLM-этапы;
- классификация заявок в техподдержку: эмбеддинги multilingual-e5 и реранкер, weighted F1 до 0,87;
- авторазметка изображений для Label Studio: YOLOv8, SAM, Florence-2, разметка примерно в 4 раза быстрее.

## Проекты

**[Natural Language Video Search](https://github.com/GrishaTS/natural-language-video-search)**: диалоговый поиск по архиву системы видеонаблюдения, публичная версия курсового проекта. LangGraph-агент разбирает запрос, уточняет у пользователя неоднозначные имена и адреса и собирает фильтр событий. В исследовательской части сравнил модели поиска видеомоментов по тексту на QVHighlights.
`LangGraph` `FastAPI` `Qdrant` `vLLM` `PostgreSQL` `Vue 3` `Docker`

**[Natural Language Image Search](https://github.com/GrishaTS/natural-language-image-search)**: офлайн-галерея с поиском фотографий по описанию на русском. Дообучил ruCLIP на датасете с подписями от Qwen 2.5, веса на [Hugging Face](https://huggingface.co/bezGriga/ruclip-finetuned-clip993).
`PyTorch` `ruCLIP` `FastAPI` `Qdrant` `MinIO` `Docker`

## Стек

- **ML:** Python, SQL, scikit-learn, CatBoost, LightGBM, pandas, NumPy, A/B-тесты
- **DL и LLM:** PyTorch, Hugging Face Transformers, LangGraph, LangChain, MCP, RAG, vLLM
- **Поиск:** Qdrant, FAISS, BM25, эмбеддинги, ранжирование
- **CV и речь:** YOLO, SAM, OCR, ASR
- **Прод и данные:** FastAPI, Docker, Kubernetes, PostgreSQL, Spark, Airflow, MLflow

## Контакты

[Telegram](https://t.me/bezGriga) · [bezgrisa@gmail.com](mailto:bezgrisa@gmail.com) · [Hugging Face](https://huggingface.co/bezGriga) · [Резюме (PDF)](https://github.com/GrishaTS/GrishaTS/blob/main/Bezrukov_Grigory_Data_Scientist.pdf)
