# YOUR PROJECT TITLE
#### Video Demo:  <https://youtu.be/tqHPGLuSMZc>
#### Description:

Hello CS50, This project is a blog web-application that was made using Django framework. I've used Django instead of Flask, because it adapts better at larger scales, it is more of an industry standard, and because I wanted to learn a new web framework. Django also tends to be more organized in file management, and has more built-in functionalities, so I had less of a headache to implement common functions such as user registration, login, list views, etc.  

In the project directory, there are multiple folders that correspond to multiple functions in the web app. The first one I want to address is the venv folder, which stands for virtual-environment; I've used a venv so that I can install python modules (like Django) directly into the folder, and I can upload the whole project as a package on github, with all the modules included.

The website folder contains the main Django app, it has autogenerated files that I could configure, such as the settings, and urls python files. The urls file can be configured to route a user into a different Django app; I've specifically configured the website's home route into the homepage folder.

There are three other Django apps; homepage, users, and media. Think of homepage as the main body of the website, it contains the homepage, the templates, the css, and the blog posts. The users app contains more of the user functionalities, such as login, logout, register, and viewing the user's profile. Lastly, the media folder stores the default profile picture, and the custom user profile pictures. 

#### How to start the website:
```
venv/scripts/activate
py manage.py livereload
py manage.py runserver
```