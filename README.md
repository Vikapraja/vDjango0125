# vDjango0125
How to install Django Software :-

2 ways:-

1.Using Virtual Environment
=>install through pip to virtualenv [pip install virtualenv]

#Creating virtual environment
-------------------------------
=>Create a folder and open in cmd and run comamnd [python -m virtualenv myenv]

=>After making virtual environment :-
	i)	Lib		(folder)	
	ii)	Scripts		(folder)
	iii)	.gitignore 	(text file)
	iv)	CACHEDIR.TAG	(Tag file)
	v)	pyvenv		(Configration source file)

=>Go On myenv\scripts and activate in cmd by [activate] ,it command are in scripts folder

=>[deactivate] for deactivate virtual environment, 

=>Make src folder in myenv and in it install django [pip install django]

=>To know version of django [pip freeze], after installation folder are be empty

=>now make your project in src

2.Direct

===============================================================
#project creation
=>After django stallation

=>open any folder(src) in cmd to make django project

=>run command [djando-admin startproject project-name(mysite)]

=>you should see mysite folder in src

=>and you can see mysite folder again and manage.py in mysite(project) folder

=>1)manage.py(package-folder) is reposible to runs and stop django's server 

=>2)in mysite\mysite you can see 
	i)	__init__.py	(blank[should not be delete, it initialize package-folder(manage.py)])
	ii)	asgi.py		(never make changes at code time)
	iii)	settings.py	(it is used to register app,db,templates,statics,email-configer)
	iv)	urls.py		(it is used for defining routes for differents pages of project,urls managements)
	v)	wsgi.py		(webs erver getway interface, for server configration,it should be use at host time otherwise don'nt change it)

=>now make app in project-folder(mysite) by [python manage.py startapp appname(demo)] 

=>After making app in project django add (2 entity)
	i)	appname		(folder)
	ii)	db.sqlite3	(sqlite3-database file)	
				(default database connection)


=>in appname(demo) you can see (7):-
	i)	migrations	(folder)
	ii)	__init__.py	
	iii)	admin.py	(for django default admin pana le creator)
	iv)	apps.py		(for testing purpose, not for work)
	v)	models.py	(for models coding of projects by class creation)
	vi)	tests.py	(for testing purpose, not for work)
	vii)	views.py	()


=>django commands
------------------
i)	djando-admin startproject project-name	(To create django project folder)
ii)	python manage.py run server		(To statrt django server)
iii)	ctr+C					(To stop server)
iv)	python manage.py startapp app-name(demo)(To create app of project , we can make many app of a single project)
v)	python manage.py migrate		(To connect all tables)
vi)	python manage.py createsuperuser	(To create project admin, for register different different tables)
vii)	python manage.py help			(for all django commands list)
viii)	




