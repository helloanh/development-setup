# Django Setup

## Ubuntu(Debian-based Linux) Setup

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
