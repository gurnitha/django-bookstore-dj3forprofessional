## BUILDING BOOKSTORE APP USING DJANGO 3.1

1. Complete basic setup - Created django project and app with sqlite db

2. Create a new app 'accounts' and installed it to project

	ing| tree -L 2 --dirsfirst
	./bookstore
	├── _docs
	├── app
	│   ├── accounts
	│   └── main
	├── config
	│   ├── __pycache__
	│   ├── __init__.py
	│   ├── asgi.py
	│   ├── settings.py
	│   ├── urls.py
	│   └── wsgi.py
	├── venv3931
	│   ├── bin
	│   ├── include
	│   ├── lib
	│   └── pyvenv.cfg
	├── README.md
	├── db.sqlite3
	└── manage.py

3. Custom user - Created and installed CustomUser to project

4. Created and connected to mysql db and run migrations

5. Created Custom User Forms

6. Created Custom User Admin

7. Created superuser

8. Created and installed a new app 'pages' and removed 'main' app

9. URLs and Views

ch 5

10. Auth URLs and Views

11. Login

12. Redirects to Home page after logging in

13. Redirects to Home page after logging out

14. Sign Up

	“Implementing a sign up page for user registration is completely up to us. We’ll go through the standard steps for any new page:

	1. create an app-level accounts/urls.py file
	2. update the project-level config/urls.py to point to the accounts app
	3. add a view called SignupPageView
	4. create a signup.html template
	5. update home.html to display the sign up page”

	Excerpt From: William S. Vincent. “Django for Professionals.” iBooks. 


