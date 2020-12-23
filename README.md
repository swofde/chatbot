# chatbot
Chatbot for telegram using Dialogflow v1

# Примечание
Будут необходимы имя и номер сессии DialogFlow v1, Хэш телеграм бота, данные аккаунта Google Cloud SDK (GOOGLE_APPLICATION_CREDENTIALS, см. туториалы от гугла).

# Применение
1. Необходимо зарегистировать вашего бота в телеграме написав @BotFather, проследовать инструкциям. <1 мин.
2. Скопировать хэш вашего бота в файл chbot.py. <1 мин.
3. Настроить Dialogflow v1 и создать файл key.json с описанием сервисного аккаунта Google Cloud (Самая сложная часть). ~1-2 часа тыканий в воздух.
4. Запустить бота командой:
```
python chbot.py
```
