This final project aims to create a blog to be used internally by a travel agency or similar to share among employees client reviews and experiences. 
For doing this, employees should register to build a centralized database of client's trips around the world, to serve as inspiration to potential 
customers and encourage them to explore what’s out there.
Among the different functionalities that it has, we can find:
- Register and create new users
- Update existing users
- Create new posts to share trips experiences
- Update content in posts that were already created
- Delete old material that is no longer relevant

INSTALL
For installing this software you need to:

1. CHECK PYTHON VERSION
This project was written with python 3.10.6. 
Test this project with this version or higher to avoid any compatibility issues.
To check python version,

- in *nix systems:
> python --version
> Python 3.8.0

- in windows:
c:\> py --version
c:\> Python 3.8.0

2. INSTALL DEPENDENCIES
You need to run pip install (or pip3), make sure you are in the project folder and you can see the requirements.txt file when you do a ls or dir:

> pip install -r requirements.txt
This last will return a bunch of stuff in the terminal.

> pip install whitenoise

> pip install pillow

Some operative systems will required you to use pip3 instead of pip

3. SETTING UP DJANGO APPLICATIONS
Once you finish the dependencies installation you need to run some django commands.

a. MIGRATIONS
Initialize the database *nix:

> python mananage.py migrate
windows:

c:\> py mananage.py migrate

b. RUN THE TEST SERVER
> python mananage.py runserver
windows:

c:\> py mananage.py runserver

Finally, go to localhost:8000/blog/list/  to access to the app.

If everthing goes well you should be able to open the browser and see the blog running.