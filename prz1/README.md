# Практическое задание №1. Сбор логов

## `rsyslog`

### Установка `rsyslog` на сервер

![](screenshots/rsyslog-install-server.png)

### Настройка модулей `rsyslog`

![](screenshots/rsyslog-modules.png)

### Добавление правил сбора логов

![](screenshots/add-rules-server.png)

### Применение конфигурации `rsyslog` на сервере

![](screenshots/apply-changes-server.png)

![](screenshots/network-sockets.png)

### Установка `rsyslog` на клиент

![](screenshots/rsyslog-install-client.png)

### Добавление правила пересылки логов на сервер

![](screenshots/add-rule-client.png)

### Применение конфигурации `rsyslog` на клиенте

![](screenshots/apply-changes-client.png)

### Просмотр логов клиента на сервере

![](screenshots/check-logs-on-server.png)

## Grafana Loki

### Загрузка compose-файла Loki

![](screenshots/wget-loki.png)

![](screenshots/loki-docker-compose.png)

### Запуск Loki

![](screenshots/start-loki.png)

### Файл конфигурации `promtail` на клиенте

![](screenshots/promtail-config.png)

### Сompose-файл `promtail`

![](screenshots/promtail-docker-compose.png)

### Запуск `promtail` на клиенте

![](screenshots/start-promtail.png)

### Просмотр логов клиента в Grafana

![](screenshots/logs-grafana.png)

## Signoz

### Запуск Signoz

![](screenshots/start-signoz.png)

### Стартовая страница Signoz

![](screenshots/signoz-start-page.png)

### Используемое приложение на клиенте для отправки данных в Signoz - https://github.com/SigNoz/sample-nodejs-app/

![](screenshots/nodejs-docker-compose.png)

### Запуск клиентского приложения

![](screenshots/start-nodejs.png)

### Информационная панель в Signoz

![](screenshots/dashboards.png)
