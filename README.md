# Практическая работа №1

**ФИО:** Гуляева Владислава Олеговна
**Группа:** ИНБО-21-23
**Вариант:** 9

## Способ развёртывания
PostgreSQL 17 установлен локально через Homebrew на macOS Apple Silicon.  
Подключение: host=localhost, port=5432, user=student, db=olist.

## Способ импорта
Импорт выполнен через psql \copy из CSV-файлов набора Olist (Kaggle).  
Ключи добавлены после загрузки данных согласно Приложению А.

## Фактическое число строк
- customers: 99441
- orders: 99441
- order_items: 112650
- order_payments: 103886
- order_reviews: 99224
- products: 32951
- sellers: 3095
- geolocation: 1000163
- product_category_name_translation: 71