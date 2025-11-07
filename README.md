# 🛍️ Flask Clothing Store

A simple online clothing store built with **Python (Flask)**.  
Includes authentication, admin panel, cart, orders, product management, and image upload.  
Perfect for learning Flask and small business prototypes.

---

## 🌐 Features

- 👤 **User system:** registration, login, logout (hashed passwords)
- 🛒 **Cart & checkout:** add, update, remove items
- 📦 **Order management:** orders saved to JSON (viewable in admin)
- 🧍‍♂️ **Admin panel:** add/edit/delete products
- 🖼️ **Image upload:** product images saved in `/static/images`
- 💬 **Search:** filter products by name or description
- 💖 **Favorites:** add/remove from session
- 📁 **JSON data storage:** easy to edit manually
- 🎨 **Bootstrap 5 UI** for a clean, responsive layout

---

## ⚙️ Installation

```bash
(https://github.com/Vsesla/-Flask-Clothing-Store.git)
cd clothing_store
pip install -r requirements.txt
python app.py

Then open your browser at:
👉 http://127.0.0.1:5000
🧑‍💼 Admin Access

    The first registered user automatically becomes an admin.

    Admin can:

        Add/edit/delete products

        Upload product images

        View all orders

📁 Project Structure

clothing_store/
│
├── app.py
├── requirements.txt
├── data/
│   ├── products.json
│   ├── users.json
│   └── orders.json
├── static/
│   └── images/
└── templates/
    ├── base.html
    ├── index.html
    ├── product.html
    ├── cart.html
    ├── login.html
    ├── register.html
    ├── admin.html
    ├── admin_add.html
    ├── admin_edit.html
    └── admin_orders.html

🧩 Technologies

    Python 3.8+

    Flask 3.x

    Werkzeug

    Bootstrap 5

📷 Screenshots

(Add screenshots of your site here — homepage, admin panel, etc.)
📜 License

MIT License.
Free for learning and commercial use.
🛍️ Интернет-магазин на Flask

Простой интернет-магазин одежды на Python (Flask).
Поддерживает регистрацию, авторизацию, панель администратора, корзину, заказы и загрузку изображений.
Подходит для обучения Flask и создания прототипов магазинов.
🌐 Возможности

    👤 Пользователи: регистрация, вход, выход (пароли с хэшированием)

    🛒 Корзина и оформление заказов

    📦 Хранение заказов в JSON-файлах, просмотр админом

    🧍‍♂️ Админка: добавление, редактирование, удаление товаров

    🖼️ Загрузка фото в /static/images

    🔍 Поиск товаров по названию и описанию

    💖 Избранное

    📁 Хранение данных в JSON

    🎨 Bootstrap-интерфейс (адаптивный и простой)

⚙️ Установка

(https://github.com/Vsesla/-Flask-Clothing-Store.git)
cd clothing_store
pip install -r requirements.txt
python app.py

Открой в браузере:
👉 http://127.0.0.1:5000
🧑‍💼 Доступ администратора

    Первый зарегистрировавшийся пользователь получает роль admin.

    Админ может:

        Добавлять, редактировать и удалять товары

        Загружать изображения

        Просматривать заказы пользователей

📁 Структура проекта

clothing_store/
│
├── app.py
├── requirements.txt
├── data/
│   ├── products.json
│   ├── users.json
│   └── orders.json
├── static/
│   └── images/
└── templates/
    ├── base.html
    ├── index.html
    ├── product.html
    ├── cart.html
    ├── login.html
    ├── register.html
    ├── admin.html
    ├── admin_add.html
    ├── admin_edit.html
    └── admin_orders.html

🧩 Технологии

    Python 3.8+

    Flask 3.x

    Werkzeug

    Bootstrap 5
