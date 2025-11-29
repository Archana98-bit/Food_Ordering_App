# 🍴 Food Ordering App (Django)

## Overview
A web application for customers to order food online. Features include:
- Menu browsing
- Cart management
- Discounts (10% off orders above ₹500)
- User authentication
- Checkout with persistent orders
- Order history per user
- Admin dashboard for menu and order management

## Tech Stack
- Django 5.x
- SQLite (default DB)
- Bootstrap (optional for styling)

## Features
- Database-backed cart
- Discounts applied automatically
- Order history tracking
- Admin customization for menu and orders
- Seeded menu items for demo
- Unit + integration tests with coverage reports

## Setup
```bash
git clone <repo-url>
cd food_ordering
pip install -r requirements.txt
python manage.py migrate
python manage.py loaddata menu.json
python manage.py createsuperuser
python manage.py runserver
