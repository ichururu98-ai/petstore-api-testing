# Petstore API Testing

Тестирование REST API (Swagger Petstore) с использованием Postman

## Что протестировано:
- CRUD операции (POST, GET, DELETE)
- Позитивные и негативные сценарии
- Валидация данных (id, name, status)

## Инструменты:
- Postman
- Swagger

## Как использовать:
1. Импортировать коллекцию в Postman
2. Запустить запросы

## Примеры проверок

- Проверка валидного создания пользователя (200 OK)
- Проверка невалидного id (ожидается 400)
- Проверка пустого имени
- Проверка длинного имени
## Структура коллекции

- Create pet with ID-1
- Create pet with long ID 
- Create pet with ID 1.5
- Create pet with ID 2f
- Find pet with hollow request
- Create pet with valid status
- Delete pet
