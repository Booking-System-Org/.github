# Booking System

## Установка и запуск

Для запуска системы необходимо склонировать 3 репозитория:

1. [**booking-system-infra**](https://github.com/Booking-System-Org/booking-system-infra) - инфраструктурные компоненты (базы данных, очереди, etc.)
2. [**api-service**](https://github.com/Booking-System-Org/api-service) - основной API сервис
3. [**booking-service**](https://github.com/Booking-System-Org/booking-service) - сервис бронирования

## Порядок запуска

Каждый микросервис содержит инструкцию по запуску в README-файле.

Запускать сервисы необходимо в следующем порядке:

1. Сначала запустите **инфраструктуру** (infra)
2. Затем запустите **API сервис** (api-service)  
3. В последнюю очередь запустите **сервис бронирования** (booking-service)

Такой порядок обеспечивает правильную инициализацию зависимостей между сервисами.

## Заметки по проектам
Во складке [Projects](https://github.com/orgs/Booking-System-Org/projects/1)
