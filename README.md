# Aldiyar_test_0

Запустите виртуальное окружение, убедитесь, что имеются файлы: credentials.json, main.py, requirements.txt, config.py

Установите зависимости из файла requirements.txt

pip install -r requirements.txt

Установите зависимости google следующим образом

pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib

В теле config.py введите свои существующие данные для соединения и доступа к локальному PostgreSQL

Запустите main.py, проследуйте в браузер и получите токен, затем еще раз запустите main.py - он будет работать в режиме онлайн с подключеннием к БД (интервал по умолчанию установлен 15 секунд)

Ссылка на таблицу для редакции

https://docs.google.com/spreadsheets/d/1i7Ceq7UKXH519wrAMYMWMT8IOus7OfvP_ijXZ-nsqQQ/edit#gid=0
