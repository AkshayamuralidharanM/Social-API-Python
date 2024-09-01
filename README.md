# Social API in Python

This is a Django-based Social API project that allows users to send, accept, or reject friend requests. The project includes user authentication and an admin interface for managing users and friend requests.

## Postman Collection

Download this file [Postman Collection](collection.json). and import in Postman desktop


## Installation

### Prerequisites

- Python 3.x
- Git

### Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/AkshayamuralidharanM/Social-API-Python.git
   cd Social-API-Python

2. **Create a Virtual Environment**

   ```bash
   python -m venv venv

3. **Activate the Virtual Environment**

   ```bash
   venv\Scripts\activate
4. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
5. **Apply Migrations**
   ```bash
   python manage.py migrate
   
6. **Create a Superuser**
   ```bash
   python manage.py createsuperuser
7. **Run the Development Server**
   ```bash
   python manage.py runserver


