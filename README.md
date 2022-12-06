# edmon blog project 
 Edmon Blog 


Title: Edmon Blog 

Edmonblog is a Python and Django full stack web application for publishing dynamic posts from PostgreSQL DB on web-browsers. The app follows MVT architecture design. 

Installation: 

python -m pip install Django

pip install -r requirements.txt

Setup PostgreSQL database and create a database in your enviorment:

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': ‘database_name’,
        'USER': ‘username’,
        'PASSWORD': ‘password_for_username’,
        'HOST': ‘hostname_or_ip_address ’ ,
        'PORT': ‘port’_number,
    }
}


Usage: 

# Open a Terminal window 

# Start the development server 
Python manage.py run server (optional port number) Default Port 8000

#  Click on the URL on the terminal 
 http://127.0.0.1:8000/

	- Accessing the Admin page
	
	# Create a new superuser with a password
	python manage.py createsuperuser 

	# Visit the admin page 
	 http://127.0.0.1/admin 

	# Create a new blog post 
	Click “Posts” or “+ Add”

	# Click “ADD POST +” and add post details 
		- Author: 
		- Title: 
		- Text: 
		- Created date: 
		- Published date: 
	
	# Click “SAVE” and visit http://127.0.0.1:8000/ to read the new blog post. 

License: 

MIT (C) Edmon Sebit 
