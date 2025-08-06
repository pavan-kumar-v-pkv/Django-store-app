# Django Store Application

A Django-based online marketplace application with user authentication, item management, and conversation system.

## Features

- **User Authentication**: Login, signup, and admin access
- **Item Management**: Create, view, edit, and delete items
- **Categories**: Organize items by categories
- **Image Upload**: Support for item images
- **Conversation System**: Users can start conversations about items
- **Dashboard**: User dashboard for managing personal items
- **Responsive Design**: Built with Tailwind CSS

## Apps Structure

- **core**: Main app with authentication, homepage, and base templates
- **item**: Item management (create, view, edit, delete items)
- **conversation**: Messaging system between users
- **dashboard**: User dashboard functionality

## Technologies Used

- Django 5.2.4
- Python 3.12
- SQLite Database
- Tailwind CSS
- HTML/CSS

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd store
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install django pillow
   ```

4. Run migrations:
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

5. Create a superuser:
   ```bash
   python manage.py createsuperuser
   ```

6. Run the development server:
   ```bash
   python manage.py runserver
   ```

## Usage

- Visit `http://127.0.0.1:8000/` to access the application
- Visit `http://127.0.0.1:8000/admin/` to access the admin panel
- Create an account or login to start using the marketplace
- Add items, browse categories, and start conversations with other users

## Admin Access

- Username: admin
- Password: admin

## Project Structure

```
store/
├── conversation/          # Messaging system
├── core/                 # Main app with auth and base templates
├── dashboard/            # User dashboard
├── item/                 # Item management
├── media/               # Uploaded files
├── store/               # Main project settings
└── manage.py            # Django management script
```
