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