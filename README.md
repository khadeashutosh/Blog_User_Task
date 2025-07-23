# Blog API with JWT & MySQL

## Features

- JWT Authentication
- User Registration & Login
- CRUD operations on Blog Posts
- Authenticated users can create/update/delete
- Anyone can view posts

## Setup Instructions

```bash
git clone <repo>
cd <project>
python -m venv user_blog_env
user_blog_env\Scripts\activate
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
