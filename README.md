# Django Messaging App

A RESTful messaging API built with Django and Django REST Framework.

## Setup

1. Install dependencies: `pip install -r requirements.txt`
2. Run migrations: `python manage.py migrate`
3. Create superuser: `python manage.py createsuperuser`
4. Run server: `python manage.py runserver`

## API Endpoints

- `GET /api/conversations/` - List conversations
- `POST /api/conversations/` - Create new conversation
- `GET /api/conversations/{id}/` - Retrieve conversation
- `GET /api/conversations/{id}/messages/` - List messages in conversation
- `GET /api/messages/` - List all messages
- `POST /api/messages/` - Create new message
