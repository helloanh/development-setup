# Django Setup

## I . Installation on Ubuntu(Debian-based Linux) Setup

1. Download python 3  
```bash
sudo apt-get install python3.5  
```  
2. Set Up Virtual environment    

Before we install Django we will get you to install an extremely useful tool to help keep your coding environment tidy on your computer. It's possible to skip this step, but it's highly recommended.   

Starting with the best possible setup will save you a lot of trouble in the future! So, let's create a virtual environment (also called a virtualenv). Virtualenv will isolate your Python/Django setup on a per-project basis.  

```bash
# make and cd to new project directory
mkdir djangogirls
cd djangogirls
# run virtualenv with python3
python3 -m venv myvenv
```  
Issues?  https://tutorial.djangogirls.org/en/installation/#fedora-up-to-21 

3. Once you are in virtualenv, then install django with pip  
```bash
# update pip
(myvenv) ~$ pip install --upgrade pip
# install django 
pip install django~=1.10.0
```

4. Activate virtualenv  
```bash
source myvenv/bin/activate
```

5. If not using virtualenv and has anaconda installation use this:
```bash
conda create -n my-dev python=3.4
source activate my-dev
```

## II. Django Demo App  

Set up mysite/settings.py  
Make sure django is installed:  
```bash
sudo pip install django --upgrade 
```

Run db, we are using default sqlite:  
```bash
python manage.py migrate  
```

Run server:
```bash
python manage.py runserver
```
Make sure you add 'localhost' to ALLOWED_HOSTS array on settings.py file.  

Create a new application inside the main directory with manage.py:  
```bash
python manage.py startapp nameofapp
#example: python manage.py startapp blog
```

Make migration:  
 ```bash
 python manage.py makemigrations blog
 ```
 
### Exceptions  
for anaconda installation already, see this thread <a href="https://github.com/ContinuumIO/anaconda-issues/issues/305">

```bash
conda create -n my-dev python=3.4
conda activate my-dev
```

