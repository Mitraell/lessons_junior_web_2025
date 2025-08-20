# 📦 Мини-каталог товаров (учебный проект)

Учебный проект для отработки микросервисного подхода и совместной командной разработки.  
Состоит из двух частей PHP и Python:
- **PHP/API** для работы с каталогом товаров
- **Python-миграции** для управления базой данных (SQLite)
- **Frontend (HTML+CSS+JS)** для отображения каталога в браузере

---

## 📂 Структура проекта


php - Директория PHP-сервиса (API каталога)

php/frontend - Директория фронтенда (статический сайт)

backend-python  Директория Python-скриптов (миграции и др.)


---

## 🚀 Запуск проекта

### 1. Установите окружение
- [Python 3.x](https://www.python.org/downloads/)
- [PHP 8+](https://www.php.net/downloads) (есть во многих XAMPP/MAMP/WAMP)

### 2. Примените миграцию (создание базы)
Перейдите в папку миграций и выполните:

```bash
cd backend-python/migrations
python 001_create_products.py
```

## Запустите PHP-сервер
cd php
php -S localhost:8000

# 🚀 http://localhost:8000/frontend/index.html