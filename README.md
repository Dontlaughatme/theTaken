## Quick Start
1. Check environment
```
	python --version
	#Python 2.7.10
```
	Command Line run python, then:
```
	import django
	django.VERSION
#1.10.1
```
	Please keep the versions of Python and Django synchronized.


2. Checkout project
```
	cd /app
	git clone https://github.com/scutbrother10/theTaken.git
	cd /app/theTaken
```

3. Add new app
```
	python manage.py startapp APPNAME
```
	in Settings.py:
```
	add 'APPNAME' to INSTALLED_APPS
```

4. Database migration
```
	python manage.py makemigrations
	python manage.py migrate
```

