# nsemedy_microservices
nsemedy microservices repository

# Homework 12
- Установлен докер
- Создан и запущен контейнер
- Создан image из контейнера
- Вывод команды docker images сохранен в репозитории

# Homework 13
- Создан docker host
- Создан свой образ
- Образ запушен на Docker Hub
- Локально запущено приложение из своего образа с Docker Hub

# Homework 14
- Приложение разбито на несколько компонентов
- Запущено микросервисное приложение

# Homework 15
- Запущены контейнеры с разными network driver
- Созданы две сети: front_net, back_net
- Создан и параметризован файл docker-compose
Имя проекта можно задать с помощью переменной COMPOSE_PROJECT_NAME или ключом -p при старте

# Homework 16
- Установлен gitlab
- Подготовлен репозиторий с кодом приложения
- Описаны стейджи CI в gitlab-ci.yml

# Homework 17
- Создан новый проект в gitlab
- Расширен пайплан
- Определены окружения

# Homework 18
- Установлен prometheus
- Произведено знакомство с ui prometheus
- Мониторинг состояния микросервисов
- Собраны метрики хоста с использованием экспортера

Ссылка на докерхаб:
https://cloud.docker.com/u/semedy/repository/list

# Homework 19
- Мониторинг докер-контейнеров
- Импорт готового дашборда в графану
- Сбор метрик работы приложения и бизнес метрик
- Настроен алертинг

Ссылка на докерхаб:
https://cloud.docker.com/u/semedy/repository/list

# Homework 20
- Сбор неструктурированных логов
- Визуализация логов
- Сбор структурированных логов
- Сбор структурированных логов

# Homework 21
- Kubernetes развернут вручную, используя The Hard Way
- Созданы деплоймент-манифесты приложений ui, comment и монго

# Homework 22
- Установлен миникуб
- Локально развернуто приложение
- Запущено приложение reddit в GKE

# Homework 23
- Создан ingress для сервиса ui
- Убран балансировщик из ui-service.yml
- Ingress настроен на прием трафика HTTPS
- Включен network-policy для GKE
- Ограничен трафик, поступающий на mongodb отовсюду, кроме сервиса comment
- Использован Volume gcePersistentDisk
- Подключен PVC к mongo
- Создан StorageClass Fast для создания хранилищ в автоматическом режиме

# Homework 24
- Установлен и настроен helm
- Установлен и настроен gitlab в kubernetes

# Homework 25
- Prometheus развернут в k8s
- Prometheus и Grafana настроены для сбора метрик
- Шаблонизированные дашборды для reddit кластера лежат в папке kubernetes/grafana/dashboards
