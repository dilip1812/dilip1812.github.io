# Social_network_site_using_python_and_django

Social network app built with python and django.
User login and user registration authenticate.
Enter User Profile.
user can add post.

## how to start project on local server.

**First make one new Directory**
> mkdir social_network_site_using_django

> cd social_network_site_using_django

**make virtual env using venv**
> python3 -m venv myvirtualenv

> source myvirtualenv/bin/activate

**clone social_network_site_project**
> git clone https://github.com/dilip1812/Social-network-Site-using-python-and-django-.git

**install requiremnt file from requirement.txt**
> pip install -r requirement.txt

**migrate initial model**
> python manage.py migrate

**run project on local server**
> python manage.py runserver

> open browser on http://127.0.0.1:8000/

**To Login Admin interface we need to create superuser**
> python manage.py createsuperuser
  ADD DETAILS
  
> python manage.py runserver 

> open browser on http://127.0.0.1:8000/admin/



