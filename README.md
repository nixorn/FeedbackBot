Задание по боту - в файле task.txt

Bot.hs - телеграм бот, который подписывает командой /start (пока без указания сайта) новые телеграм чаты. Токен бота может быть указан в переменной FEEDBACK_BOT или вставлен в терминале после запуска

Server.hs - API сервер. Запускается на порту 8080 и прослушивает эндпойнт (метод POST)
http://localhost:8080/feedback, в теле которого ожидает поля email и message

Database.hs - модуль, который добавляет новый чат и получает все чаты(пока работает с файлом subscribers, файл создается если его нет)

Для проверки работы можно использовать:

https://github.com/DeniLark/form-feedback-bot
