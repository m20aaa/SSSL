# Практическое задание №5. Threat Hunting

Для выполнения работы был использован стенд Wazuh из практической работы №3.

![](./screenshots/1.png)

## Установка и настройка IDS Suricata

Добавление репозитория в пакетный менеджер

![](./screenshots/2.png)

Скачивание правил обнаружения

![](./screenshots/3.png)

Изменение конфигурации Suricata

![](./screenshots/4.png)

![](./screenshots/5.png)

Настройка импорта логов Suricata в Wazuh

![](./screenshots/6.png)

## Пример атаки

На агенте был развернут простой веб-сервер Apache

![](./screenshots/7.png)

С помощью сканера веб-уязвимостей `nuclei` было выполнено сканирование агента

![](./screenshots/8.png)

События Suricata, отображаемые в Wazuh

![](./screenshots/9.png)

## Установка и настройка Yara

Скачивание, компиляция и установка Yara

![](./screenshots/10.png)

![](./screenshots/11.png)

Скачивание Yara-правил

![](./screenshots/12.png)

Создание скрипта `yara.sh`

![](./screenshots/13.png)

Изменение конфига `ossec` на агенте

![](./screenshots/14.png)

Изменение файлов конфигурации на сервере

![](./screenshots/15.png)

![](./screenshots/16.png)

![](./screenshots/17.png)