# Cognizance Club Management System (CCMS)
[![Docker](https://github.com/cognizance-amrita/cms/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/cognizance-amrita/cms/actions/workflows/docker-publish.yml)
[![Django CI](https://github.com/cognizance-amrita/cms/actions/workflows/django.yml/badge.svg)](https://github.com/cognizance-amrita/cms/actions/workflows/django.yml)
[![Django Security Check](https://github.com/cognizance-amrita/cms/actions/workflows/django_security_check.yml/badge.svg)](https://github.com/cognizance-amrita/cms/actions/workflows/django_security_check.yml)  
<br/>
Club Management System (CMS) is django-based web-app which is specially made for our club. 

---

## Installation Instructions
The portal is primarily a django based application, and to set it up we require to have 
python environment with django and other project dependencies installed. Though one can
work with the project without an virtual environment,  it is recommended to use one so 
as to avoid conflicts with other projects.

0. Make sure that you have `Python 3`, `python-3-devel`, `gcc`, `virtualenv`, and `pip` installed.     
1. Clone the repository

    ```bash
        $ git clone https://github.com/cognizance-amrita/cognizance_cms.git
        $ cd cognizance_cms
    ```  
2. 
    a. Docker image (First option)  
  
    ```bash  
        $ docker-compose build  
        $ docker-compose up  
    ```  

    b. Create a python 3 virtualenv, activate the environment and Install the project dependencies. (Second option)  

    ```bash
        $ virtualenv -p python3
        $ source bin/activate
        $ pip3 install -r requirements.txt
    ```   

You have now successfully set up the project on your environment. 

---

### After Setting Up
From now when you start your work, run ``source bin/activate`` inside the project repository and you can work with the django application as usual - 

* `python3 manage.py migrate` - set up database
* `python3 manage.py createsuperuser` - create admin user
* `python3 manage.py runserver`  - run the project locally

*Make sure you pull new changes from remote regularly.*

---
### Contributors
* [Sanjay](https://github.com/sanjay-thiyagarajan)
* [Naresh Kumar](https://github.com/TechieNK)
* [Tejendra Saradhi](https://github.com/tejas15802)
* [Sanjai Siddharthan](https://github.com/SSpirate)  
* [Mukesh](https://github.com/mukesh663)
* [Pranavan](https://github.com/Techipeeyon)
* [Abhinandhan S](https://github.com/STRIZERORTIX)

