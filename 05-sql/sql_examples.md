# SQL Examples / Примеры SQL

## 🇷🇺 Примеры (валидация данных)

### 1) Проверка создания пользователя
```sql
SELECT id, email, created_at
FROM users
WHERE email = 'test@example.com';
```

### 2) Проверка связи данных (JOIN)
```sql
SELECT o.id, o.status, u.email
FROM orders o
JOIN users u ON o.user_id = u.id
WHERE u.email = 'test@example.com';
```

### 3) Проверка статуса после изменения
```sql
SELECT status
FROM orders
WHERE id = 1024;
```

### 4) Агрегация (GROUP BY)
```sql
SELECT status, COUNT(*) AS total_orders
FROM orders
GROUP BY status;
```

---

## 🇬🇧 Examples (data validation)

These queries demonstrate:
- record existence checks
- relational validation with JOIN
- status verification after operation
- aggregation check with GROUP BY + COUNT
