# Django Basic Commands a developer Should be know
All These commands based on Windows OS

1. Installing Virtualenv 
    
    ```
    pip install virtualenv
    ```
    
2. Creating Virtualenv
    ```
    virtualenv (environment name)
    ```

    OR

   ```
    python -m venv (environment name)
    ```
    
4. Activating Environment:
    ```
    (environment name)\Scripts\activate  (Windows OS)
    ```

5. Deactivating Environment:
    ```
    venv\Scripts\deactivate.bat (Windows OS)
    ```

6. Installing django:
    ```
    pip install django
    ```

7. Starting Django Project:
    ```
    django-admin startproject (project name) .
    ```

8. Running Django Project:
    ```
    python manage.py runserver
    ```

9. Creating app:
    ```
    django-admin startapp (app name)
    ```

10. Migrating the Model(Step-1):
    ```
    python manage.py makemigrations
    ```

11. Migrating the Model(Step-2):
    ```
    python manage.py migrate
    ```

12. Translating  ORMS into SQL statements:
    ```
    python manage.py sqlmigrate (migrationfilename)
    ```
13. Activating Python Shell:
    ```
    python manage.py shell
    ```
