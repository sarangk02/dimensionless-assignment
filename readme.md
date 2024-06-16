# Project Name

## Backend Setup

1. **Open Backend Folder**:

   Navigate to the `Backend` folder in your project directory.

2. **Run Docker Compose**:

   Open a command prompt or terminal in the `Backend` folder and run the following command:


3. **Run Migrations and Create Superuser**:

After your Docker containers are up and running, execute the following commands:

```bash
docker-compose exec django python manage.py makemigrations shop
docker-compose exec django python manage.py migrate
docker-compose exec django python manage.py createsuperuser
```

4. **Frontend Setup**:

Open a command prompt or terminal in the frontend folder and run:

```bash
npm start
```

