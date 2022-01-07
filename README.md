## Домашнее задание к Основы работы с Kubernetes (часть 3) 


### Установка postgres
helm install pg bitnami/postgresql -f pg_values.yaml

### Установка приложения
helm install userservice .

Первоначальные миграции оформлены в приложении с использованием flyway

Исходники - https://github.com/petrovichs/user-service

Модель и REST сгенерированы openapi-generator-maven-plugin

Коллекция POSTMAN с запросами в файле otus.postman_collection
