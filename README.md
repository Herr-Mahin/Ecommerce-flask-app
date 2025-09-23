# Ecommerce-flask-app
Flask shopping cart project showcasing e-commerce basics and research on AI-powered customer support chatbots.

## System Overview

1. Backend: Flask micro-framework (main.py) with modular routing and session/cart handling.

2. Database: SQLite (database.db) accessed via database.py for CRUD operations (products, cart, etc.).

3. Frontend: Jinja2 templates (/templates) with static assets (/static) for CSS, JS, and images.

4. AI Component: ChatBot.py provides chatbot functionality, supported by text resources (chatbot.txt).

## Key Technical Features

1. MVC-like separation: routes, logic, templates, and static files are modular.

2. Jinja2 template inheritance for consistent UI design.

3. Lightweight database integration (SQLite) with Python abstraction.

4. Session-based shopping cart management.

5. Extendable chatbot integration for customer assistance.

## Installation
```bash
git clone https://github.com/Herr-Mahin/Ecommerce-flask-app.git
```
```bash
cd Ecommerce-flask-app
```
```bash
python3 -m venv venv
```
```bash
source venv/bin/activate   # On Windows: venv\Scripts\activate
```
```bash
pip install flask
```
```bash
python main.py
```
