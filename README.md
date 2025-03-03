# TrafficDown

[Telegram](https://t.me/HackActivity)

Это скрипт, который позволяет съесть много трафика, понизить скорость любой сети!
Необходим Python версии выше 3.13!

## Как он работает

Как он ест трафик: скрипт получает очень много мусорной информации, которая много весит. Из-за этого можно съесть у точки доступа много трафика.
Как он понижает скорость сети: скрипт делает очень много запросов на случайный IP (8.8.8.8:443), из-за чего сеть начинает лагать.

## Установка

Скрипт сам установит необходимые модули. Поддерживает:

- Android (termux)
- Linux дистрибутивы
- Windows
- WSL

Почему не поддерживает pydroid? Он ужасен.

## Запуск

Как использовать на Android:
Скачайте Termux, введите команду 
apt update && apt upgrade -y && apt install python3 && apt install git && git clone https://github.com/Sonys9/TrafficDown && cd TrafficDown && python3 TrafficDown.py

Как пользоваться на Windows:
Скачайте Python 3.8 и выше с Microsoft Store (там легче всего, либо через python.org) и запустите скрипт

Как пользоваться на Linux дистрибутивах:
Впишите в терминале команду apt update && apt upgrade -y && apt install python3 && apt install git && git clone https://github.com/Sonys9/TrafficDown && cd TrafficDown && python3 TrafficDown.py

💻 HackActivity (https://t.me/HackActivity)
![image](https://github.com/user-attachments/assets/7a89c0e3-6f6e-4ce9-94c6-98a25d167778)
