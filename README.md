## Glowing Potato

- A fully functional blog and a simple portfolio 

Build Versions: python 3.6, django==3.1.3

**Special thanks** to [**Jasmin Finer**](https://realpython.com/get-started-with-django-1/#author) from [RealPython](www.realpython.com) for her this [blog](https://realpython.com/get-started-with-django-1/) to help me to build this project.

## Quick Start

To get this project up and running locally on your computer:

1. Set up the [Python development environment](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/development_environment). Using a Python virtual environment recommended.

2. First activate virtual environment: 

   ```
   source env/bin/activate
   ```

   Then type: 

3. ```
   python3 manage.py makemigrations
   python3 manage.py migrate
   python3 manage.py test # Run the standard tests. These should all pass.
   python3 manage.py createsuperuser # Create a superuser
   python3 manage.py runserver
   ```

4. Open a browser to `http://127.0.0.1:8000/admin/` to open the admin site

5. Create a few test objects of each type.

6. Open tab to `http://127.0.0.1:8000` to see the main site, with your new objects.