# BR-API-001 — Некорректная обработка невалидного petId / Invalid petId handling

**Endpoint:** /pet/{petId}  
**Method:** GET  

## 🇷🇺 Ожидаемо
400 Bad Request или 404 Not Found + понятное сообщение об ошибке.

## 🇷🇺 Фактически
Возвращается некорректный статус и/или невалидный/пустой ответ.

## Steps to reproduce / Шаги
1. Send / Отправить: `GET /pet/abc`
2. Check status code and response body

**Environment:** Public Petstore API, Postman
