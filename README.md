<br/>
<p align="center">
  <a href="https://github.com/TegroTON/SMMPanel-SMOService-Telegram-Bot">
    <img src="static/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Smoservice Bot</h3>

  <p align="center">
    Система автоматиизированного продвижения в социальных сетях.
    <br/>
    <br/>
    <a href="https://github.com/TegroTON/SMMPanel-SMOService-Telegram-Bot"><strong>Explore the docs »</strong></a>
    <br/>
    <br/>
    <a href="https://github.comTegroTON/SMMPanel-SMOService-Telegram-Bot">View Demo</a>
    <a href="https://github.com/TegroTON/SMMPanel-SMOService-Telegram-Bot/issues">Report Bug</a>
    <a href="https://github.com/TegroTON/SMMPanel-SMOService-Telegram-Bot/issues">Request Feature</a>
  </p>
</p>

![Downloads](https://img.shields.io/github/downloads/TegroTON/SMMPanel-SMOService-Telegram-Bot/total) ![Contributors](https://img.shields.io/github/contributors/TegroTON/SMMPanel-SMOService-Telegram-Bot?color=dark-green) ![Issues](https://img.shields.io/github/issues/TegroTON/SMMPanel-SMOService-Telegram-Bot) ![License](https://img.shields.io/github/license/TegroTON/SMMPanel-SMOService-Telegram-Bot) 

## Table Of Contents

* [About the Project](#about-the-project)
* [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Authors](#authors)
* [Acknowledgements](#acknowledgements)

## About The Project

![Screen Shot](static/main_menu.png)

🚀 SMOService & RosMedia - Ваши идеальне инструменты для продвижения в социальных сетях! Получайте больше подписчиков, просмотров и многого другого с легкостью и эффективностью.

Основные функции:
* Новый заказ: Быстро и удобно создайте заказ на накрутку нужного параметра.
* История: Отслеживайте все свои заказы и их статус в одном месте.
* Кошелек: Управляйте своими средствами, пополняйте баланс и оплачивайте услуги.
* Рефералы: Приглашайте друзей и знакомых, получая вознаграждение за их активность.
* Чеки: Поделитесь деньгами с кем-либо, используя простую ссылку для передачи.
* Мои боты: Уникальный функционал! Создайте копию этого бота с новым ID.

Присоединяйтесь к нам и делайте ваш аккаунт популярным!

## Built With

Бот разработан с использованием современных технологических решений, обеспечивающих высокую производительность и стабильность работы. Использование асинхронных библиотек позволяет боту быстро и эффективно обрабатывать большое количество запросов, адаптируясь к высоким требованиям современных пользователей.


* [python 3](https://www.python.org/downloads/)
* [aiohttp](https://docs.aiohttp.org/en/v3.8.1/web_advanced.html)
* [aiogram](https://aiogram.dev/)
* [sqlite](https://www.sqlite.org/index.html)

## Getting Started

Для успешной настройки и стабильной работы бота необходимо следовать нижеуказанным техническим требованиям:

* Сервер:
Хостинг: Рекомендуется использовать VPS или выделенный сервер для оптимальной производительности и надежности. Сервер должен иметь стабильное интернет-соединение и соответствующие ресурсы (CPU, RAM) в зависимости от ожидаемой нагрузки.
Операционная система:
Рекомендуются современные дистрибутивы Linux, такие как Ubuntu, CentOS или Debian. Однако большинство UNIX-подобных систем также подойдут.
Программное обеспечение:
Python 3: Убедитесь, что на сервере установлена последняя стабильная версия Python 3. Это основной язык программирования, на котором написан ваш бот.

* pip: Система управления пакетами для Python. Необходима для установки необходимых библиотек и зависимостей для вашего бота.

* Примечание:
Перед началом настройки рекомендуется проверить все установленное программное обеспечение на актуальность версий и наличие всех необходимых зависимостей.

### Prerequisites

Для корректной установки и функционирования бота убедитесь, что следующие библиотеки и их версии установлены на вашем сервере:
```sh
aiofiles==23.1.0
aiogram==3.0.0rc2
aiohttp==3.8.5
aiohttp-jinja2==1.5.1
aiosignal==1.3.1
annotated-types==0.5.0
anyio==3.7.1
asgiref==3.7.2
async-timeout==4.0.2
attrs==23.1.0
beautifulsoup4==4.12.2
blinker==1.6.2
callback==0.0.1
certifi==2023.7.22
charset-normalizer==3.2.0
click==8.1.7
colorama==0.4.6
Django==4.2.5
fastapi==0.103.1
Flask==2.3.3
frozenlist==1.4.0
idna==3.4
itsdangerous==2.1.2
Jinja2==3.1.2
lxml==4.9.3
magic-filter==1.0.11
Markdown==3.4.4
MarkupSafe==2.1.3
multidict==6.0.4
pydantic==2.2.1
pydantic_core==2.6.1
python-dotenv==1.0.0
requests==2.31.0
sniffio==1.3.0
soupsieve==2.4.1
sqlparse==0.4.4
starlette==0.27.0
typing_extensions==4.7.1
tzdata==2023.3
urllib3==2.0.4
validators==0.21.2
Werkzeug==2.3.7
yarl==1.9.2
```
Для автоматической установки всех необходимых библиотек, вы можете использовать файл req.txt с приведенным выше содержимым, выполнив команду:
```sh
pip install -r req.txt
```
Это обеспечит установку всех нужных зависимостей для надежной работы вашего бота.

### Installation

**Шаг 1**
1. Настройка файла .env для вашего бота
Для корректной работы вашего бота необходимо правильно настроить файл конфигурации .env. Пройдите по следующим подшагам:
    * 1.1. Откройте файл .env в редакторе кода.

    * 1.2. Настройка API token бота в Telegram:
Получите api token вашего бота в Telegram.
Вставьте его рядом с графой apitoken.
    * 1.3. Настройка данных магазина в Tegro Money:
Получите shopid и secret key вашего магазина в Tegro Money.
Укажите их в соответствующих графах файла.
    * 1.4. Указание администратора бота:
Укажите user id пользователя Telegram, который будет администратором вашего бота.
    * 1.5. Указание имени бота:
    * 1.6. Настройка данных для SMOService:
Укажите ваш api key в графе для SMOService.
Укажите ваш user id в соответствующей графе для SMOService.
    * 1.7. Настройка данных для SMMPanel:
Укажите ваш api key в графе для SMMPanel.
Укажите ваш user id в соответствующей графе для SMMPanel.
    * 1.9. Сохраните и закройте файл .env.

**Шаг 2**

 2. Получение HTTPS сертификата через Certbot
Для обеспечения безопасности соединения с вашим сервером рекомендуется использовать HTTPS сертификат. Чтобы его получить, следуйте указаниям ниже:

    * 2.1. Перейдите на официальный сайт Certbot по следующей ссылке: https://certbot.eff.org/

    * 2.2. На сайте выберите программное обеспечение (web-сервер) и систему, которые используются на вашем сервере.

    * 2.3. Следуйте предложенной инструкции на сайте для установки и настройки Certbot. Это обычно включает в себя несколько команд, которые необходимо выполнить в вашем терминале или командной строке.

    * 2.4. После успешной настройки и получения сертификата, Certbot выведет в консоли информацию о местоположении ключей сертификата.

    * 2.5. Запишите или сохраните следующие пути:
Путь к вашему приватному ключу (обычно privkey.pem)
Путь к полному цепочному сертификату (обычно fullchain.pem)
    * 2.6. Укажите сохраненные пути в вашем конфигурационном файле или там, где это требуется для настройки вашего сервера.

🚫 Подсказка по безопасности: Никогда не делитесь приватными ключами и убедитесь, что у них соответствующие права доступа, чтобы они были недоступны для всех, кроме необходимых служб и администратора.

**Шаг 3**
Настройка Nginx для работы с вашим ботом
Для того чтобы ваш Telegram бот мог корректно обрабатывать запросы, необходимо настроить web-сервер Nginx. Следуйте инструкциям ниже:

* 3.1. Установка и исходная настройка Nginx
    * 3.1.1. Установите Nginx:

```sh
sudo apt-get install -y nginx
```
* 3.1.2. Перейдите в каталог, где хранятся доступные конфигурации сайтов:

```sh
cd /etc/nginx/sites-available/
```
* 3.1.3. Создайте и откройте новый конфигурационный файл:

```sh
sudo nano telegram_bot.conf
```
* 3.2. Конфигурация файла
В появившемся редакторе, впишите следующую конфигурацию:

```sh
server {
    listen 80;
    listen 443 ssl;
    server_name Имя_вашего_сервера_без_http_и_/;
    ssl_certificate Путь_Который_Вы_Сохранили;
    ssl_certificate_key Второй_Путь_Который_Вы_Сохранили;
    location / {
        proxy_set_header Host $http_host;
        proxy_redirect off;
        proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for;
        proxy_set_header X-Real-IP $remote_addr;
        proxy_set_header X-Scheme $scheme;
        proxy_pass http://localhost:8001/;
    }
}
```

Памятка: Замените Путь_Который_Вы_Сохранили и Второй_Путь_Который_Вы_Сохранили на актуальные пути к вашим файлам сертификата, которые вы сохранили на предыдущем шаге.

Сохраните и закройте файл.
* 3.3. Активация и перезапуск Nginx
    * 3.3.1. Перейдите в каталог с активными конфигурациями:

```sh
cd /etc/nginx/sites-enabled/
```

* 3.3.2. Создайте символическую ссылку на ваш конфигурационный файл:

```sh
sudo ln -s ../sites-available/telegram_bot.conf telegram_bot.conf
```

* 3.3.3. Перезапустите Nginx для применения изменений:

```sh
sudo service nginx restart
```

**Шаг 4**
Для того чтобы ваш бот всегда был в рабочем состоянии и автоматически запускался после перезагрузки сервера или внезапных отключений, создайте сервис, используя systemd.

* 4.1. Создание конфигурационного файла сервиса
    * 4.1.1. Перейдите в каталог systemd, где хранятся конфигурационные файлы сервисов:

```sh
cd /etc/systemd/system/
```

* 4.1.2. Создайте и откройте новый файл для вашего сервиса:

```sh
vim tgbot.service
```

* 4.2. Конфигурация файла сервиса
В появившемся редакторе, вставьте следующую конфигурацию:

```sh
[Unit]
Description=Telegram Bot Service

[Service]
WorkingDirectory=ПУТЬ_ДО_ВАШЕГО_MAIN_ФАЙЛА_БОТА
User=ИМЯ_ПОЛЬЗОВАТЕЛЯ_ОТ_КОТОРОГО_ЛИЦА_ЗАПУСКАТЬ
ExecStart=/usr/bin/python3 main.py

[Install]
WantedBy=multi-user.target
```

Памятка:

Замените ПУТЬ_ДО_ВАШЕГО_MAIN_ФАЙЛА_БОТА на реальный путь до вашего главного файла бота.
Замените ИМЯ_ПОЛЬЗОВАТЕЛЯ_ОТ_КОТОРОГО_ЛИЦА_ЗАПУСКАТЬ на имя пользователя, от лица которого должен запускаться бот.
Сохраните и закройте файл.

* 4.3. Активация и запуск сервиса
    * 4.3.1. Для того чтобы активировать и автоматически запускать сервис при загрузке системы, используйте следующую команду:

```sh
sudo systemctl enable tgbot.service
```

* 4.3.2. Чтобы запустить вашего бота прямо сейчас с помощью созданного сервиса, используйте:
```sh
sudo systemctl start tgbot.service
```

Проверьте статус вашего бота с помощью команды:
```sh
sudo systemctl status tgbot.service
```

Это позволит вам удостовериться, что ваш бот успешно запущен и работает корректно.

## Roadmap

Список предлагаемых функций (и известных проблем) см. в разделе ["Открытые вопросы"](https://github.com/TegroTON/SMMPanel-SMOService-Telegram-Bot/issues).


## Authors

* **DeFiTON** - *CPO Telegram Bot* - [Jason Gatsby](https://github.com/DeFiTON) - *CPO*
* **Dmitrii-Kopeikin** - *CPO Telegram Bot* - [Dmitrii Kopeikin](https://github.com/Dmitrii-Kopeikin) - *Middle DevOps Engineer*
* **m1ja** - *Junior DevOps* - [Developer m1ja](https://github.com/m1ja) - *Junior DevOps*

## Acknowledgements

* [ShaanCoding](https://github.com/ShaanCoding/)
* [Othneil Drew](https://github.com/othneildrew/Best-README-Template)
* [ImgShields](https://shields.io/)
