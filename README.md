# Ecommerce-flask-app
Flask shopping cart project showcasing e-commerce basics and research on AI-powered customer support chatbots.

## System Overview

Backend: Flask micro-framework (main.py) with modular routing and session/cart handling.

Database: SQLite (database.db) accessed via database.py for CRUD operations (products, cart, etc.).

Frontend: Jinja2 templates (/templates) with static assets (/static) for CSS, JS, and images.

AI Component: ChatBot.py provides chatbot functionality, supported by text resources (chatbot.txt).

## Key Technical Features

MVC-like separation: routes, logic, templates, and static files are modular.

Jinja2 template inheritance for consistent UI design.

Lightweight database integration (SQLite) with Python abstraction.

Session-based shopping cart management.

Extendable chatbot integration for customer assistance.

## Installation
```bash
git clone https://github.com/Herr-Mahin/Ecommerce-flask-app.git
cd Ecommerce-flask-app
python3 -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
pip install flask
python main.py
```
