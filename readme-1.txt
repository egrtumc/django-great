1. Create Folder "name"
2. google => install virtual environment python => for window  creat: " py -m venv env "
	2.1 Activate => source env/Scripts/activate
	2.2 Exit vir env => deactivate
3. look for package in global => pip freeze
4. Django installation  =>(env) pip  install django==3.1 or django(lastest version)
	4.1 django-admin startproject "projectname" .
	4.2 run command to start: python manage.py runserver
	4.3 access webiste : 127.0.0.1:8000

5. After create static folder => to make it work => python manage.py collectstatic

6. to create startapp => python manage.py startapp category
6.1 after startapp => go to greatkart folder => settings.py => INSTALLED_APPS = [...]
6.2 after create all necces sql fn. model => python manage.py makemigrantions
6.3 error Pillow => pip install pillow

7. Create admin ID&Password
7.1 python manage.py migrate
7.2 winpty python manage.py createsuperuser
egrtumc
port4000
8. after create all model for admin and staff and babababa
8.1 delete db.sqlite3(existing file before execute)
8.2 In category older => migrations => 00001_initial.py and 00002_auto_20201005_0245.py
	=> delete 2 files
8.3 python manage.py runserver
8.4 python manage.py makemigrations
8.5 python manage.py migrate

9. when git => create .gitignore => gitignore.io (they list all files that should
be ignored)
