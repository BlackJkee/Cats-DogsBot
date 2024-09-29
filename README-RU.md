[![Static Badge](https://img.shields.io/badge/Telegram-Bot%20Link-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/catsdogs_game_bot/join?startapp=1197825376)

# АВТО ФАРМ ДЛЯ CatsVSDogsBot🚀



# 🔥🔥 Используйте PYTHON версии 3.10 🔥🔥

> 🇪🇳 README in english available [here](README-EN)

## Функционал  
|                       Функционал                        | Поддерживается |
|:-------------------------------------------------------:|:--------------:|
|                     Многопоточность                     |       ✔️       | 
|                Привязка прокси к сессии                 |       ✔️       | 
|              Привязка User-Agent к сессии               |       ✔️       |
|               Поддержка pyrogram .session               |       ✔️       |
|     Авто-регистрация аккаунта по вашей реф. ссылке      |       ✔️       |
|                       Авто таски                        |       ✔️       |
|                   Авто  Daily rewards                   |       ✔️       |



## [Настройки](https://github.com/BlackJkee/CatsVSDogsBot/blob/main/.env-example/)
| Настройки             |                                                 Описание                                                 |
|-----------------------|:--------------------------------------------------------------------------------------------------------:|
| **API_ID / API_HASH** |           Данные платформы, с которой будет запущена сессия Telegram (по умолчанию - android)            |
| **SLEEP_TIME**        |                          Время сна между циклами (по умолчанию - [7200, 10800])                          |
| **START_DELAY**       |                       Задержка между сеансами при запуске (по умолчанию - [5, 25])                       |
| **AUTO_TASK**         |                                    Авто таски ( по умолчанию - True)                                     |
| **JOIN_CHANNELS**     |                             Автовступление в каналы tg (по умолчанию - True)                             |
| **CLAIM_REWARD**      |                              Eжедневное вознаграждение (по умолчанию - True)                             |

## Быстрый старт 📚

Для быстрой установки и последующего запуска - запустите файл `run.bat` на **Windows** или `run.sh` на **Линукс**

## Предварительные условия
Прежде чем начать, убедитесь, что у вас установлено следующее:
- [Python](https://www.python.org/downloads/release/python-3100/) **версии 3.10**

## Получение API ключей
1. Перейдите на сайт [**my.telegram.org**](https://my.telegram.org/auth) и войдите в систему, используя свой номер телефона.
2. Выберите `API development tools` и заполните форму для регистрации нового приложения.
3. Запишите `API_ID` и `API_HASH` в файле `.env`, предоставленные после регистрации вашего приложения.

## Установка
Вы можете скачать [**Репозиторий**](https://github.com/BlackJkee/CatsVSDogsBot) клонированием на вашу систему и установкой необходимых зависимостей:
```shell
git clone https://github.com/BlackJkee/CatsVSDogsBot.git
cd CatsVSDogsBot
```

Затем для автоматической установки введите:

Windows:
```shell
run.bat
```

Linux:
```shell
run.sh
```

# Linux ручная установка
```shell
sudo sh install.sh
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
cp .env-example .env
nano .env  # Здесь вы обязательно должны указать ваши API_ID и API_HASH , остальное берется по умолчанию
python3 main.py
```

Также для быстрого запуска вы можете использовать аргументы, например:
```shell
~/CatsVSDogsBot >>> python3 main.py --action (1/2)
# Or
~/CatsVSDogsBot >>> python3 main.py -a (1/2)

# 1 - Запускает кликер
# 2 - Создает сессию
```


# Windows ручная установка
```shell
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
copy .env-example .env
# Указываете ваши API_ID и API_HASH, остальное берется по умолчанию
python main.py
```

Также для быстрого запуска вы можете использовать аргументы, например:
```shell
~/CatsVSDogsBot >>> python main.py --action (1/2)
# Или
~/CatsVSDogsBot >>> python main.py -a (1/2)

# 1 - Запускает кликер
# 2 - Создает сессию
```