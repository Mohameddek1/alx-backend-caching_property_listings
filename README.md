# alx-backend-caching_property_listings

A Django property listing app with Dockerized PostgreSQL and Redis caching.

## Setup
1. Build and start services:
   ```bash
   docker-compose up -d
   ```
2. Install Python dependencies:
   ```bash
   pip install django django-redis psycopg2-binary
   ```
3. Run migrations:
   ```bash
   python manage.py migrate
   ```
4. Start the Django server:
   ```bash
   python manage.py runserver
   ```

## Services
- PostgreSQL: Database for property listings
- Redis: Cache backend for Django

## Features
- Property model: title, description, price, location, created_at
- Multi-level caching (to be implemented)
