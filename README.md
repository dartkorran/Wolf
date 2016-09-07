# Wolf #

The final work at the end of the course on django.

To run the project you need:

<b>1. Install Python</b>

Django is a Python web framework, thus requiring Python to be installed on your machine. At the time of writing, Python 3.5 is the latest version.

To install Python on your machine go to https://python.org/downloads/. The website should offer you a download button for the latest Python version. Download the executable installer and run it. Check the box next to Add Python 3.5 to PATH and then click Install Now.

<b>2. Install pip</b>

Pip is a package manage for Python. It makes installing and uninstalling Python packages (such as Django!) very easy. For the rest of the installation, we’ll use pip to install Python packages from the command line.

Pip is already installed if you're using Python 2 >=2.7.9 or Python 3 >=3.4 binaries downloaded from python.org, but you'll need to upgrade pip.

<b>3. Install virtualenv and virtualenvwrapper</b>

Virtualenv and virtualenvwrapper provide a dedicated environment for each Django project you create. While not mandatory, this is considered a best practice and will save you time in the future when you’re ready to deploy your project. Simply type:

<i>pip install virtualenvwrapper-win</i>

<b>4. Install django</b>

Django can be installed easily using pip within your virtual environment.
In the command prompt, ensure your virtual environment is active, and execute the following command:

<i>pip install django<>
This will download and install the latest Django release.

<b>5. Run project</b>

In command prompt go to the root directory of the project, and type:

<i>manage.py runserver</i>

The project will be available at http://127.0.0.1:8000/
