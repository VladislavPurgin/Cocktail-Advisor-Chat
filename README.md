# Cocktail Chat

Цей додаток дозволяє шукати коктейлі, зберігати улюблені інгредієнти та отримувати рекомендації. Проєкт реалізує чат-бот для рекомендації коктейлів з використанням RAG (Retrieval-Augmented Generation). Бот інтегрується з Pinecone для зберігання векторних embeddings коктейлів та використовує Together API для генерації відповідей.

## Вимоги
Для роботи з проєктом потрібно:
1. Python 3.9 або новішої версії.
2. API ключі для Pinecone та Together API.
3. Бібліотеки, вказані у requirements.txt.

## Запуск
1. Клонуйте репозиторій:
   git clone https://github.com/ваш-юзернейм/cocktail-chatbot-rag.git
   cd cocktail-chatbot-rag
2. Встановіть залежності:
   pip install -r requirements.txt
3. Створіть файл .env у корені проєкту та додайте туди ваші API ключі:
   PINECONE_API_KEY=ваш_pinecone_api_key
   TOGETHER_API_KEY=ваш_together_api_key
4. Запуск проєкту:
   python main.py або uvicorn app.main:app --reload
   Після цього відкрийте браузер.
   Головна сторінка: http://127.0.0.1:8000
   Документація API: http://127.0.0.1:8000/docs
