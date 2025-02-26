МОЙ DOCKER-ПРОЕКТ

Я использовал имя kostas-app, можно, конечно же, заменить на свое (как и в случае с my_container)

Как запаустить DOCKER
=====================
Чтобы начать сборку, я использовал Терминал. Ввел команду cd + путь до папки в которой лежал Dockerfile.
Далее следуем инструкции:
1. **Собрать образ:**
    docker build -t kostas-app .
2. **Запустить:**
    docker run -d -p 8000:8000 --name my_container kostas-app


#### Contact me:
[![Telegram](https://img.shields.io/badge/Telegram-262424?style=for-the-badge&logo=Telegram)](https://t.me/ffraud)


Privet