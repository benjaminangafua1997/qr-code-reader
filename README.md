### About
Project Title:   Ekklesia
Built By:  Benjamin A. Ngafua
Location: Monrovia, Liberia
Description: Church Management Software
Video Demo: [Benjamin A. Ngafua's cs50x Final Project](https://youtu.be/nzqE3m4DkJ8)

### What is Ekklesia app?
- Ekklesia is a church management software that aids churches and similar in managing, automating and organizing daily operations.

### Ekklesia aim?     
- It allows church members to see God's hand through ministries

### What it is used for?
1. It tracks and manages resources
2. It enhances communication
3. It monitors church growth

### Who to use it currently?
 - Currently use for administrator.

### Technology used
- **Framework:**
    - Flask
    
- **Templates :**
    - Jinja2
- **Frontend**
    - >Template from: [TEMPLATEMO](https://themewagon.com/)

- **Backend Language:** 
    - Python
- **Database**
    - SQLite3
- **Images use:**
    - > The images are from: [PEXELS](https://www.pexels.com/)


### Feature
|Description |Status |
|---------|------|
|Dashboard statistics | 80%|
| Store users | 80% |
|Create Members | 80% |
|Communicate to members| Yet to start|
| Track financial transaction | Yet to start |

### Setup
Install all the modules in requirements.txt file manually or 

Run 
> ```pip3 freeze > requirements.txt``` 

To run the app locally run
>```flask run```


If you are new to flask, you might want to learn a bit about flask [here](https://flask.palletsprojects.com/en/2.2.x/quickstart/) to get you started


### Directories and Files:
- **churchAPP:**
    - Comprises of all code that runs the application.
    - **static:**
        > Contains the css, js, fonts and  images files with important 
        links that enhance the layout and the performances
    - **templates**
        > Contains html file layouts and structure
        
    - **__init__.py**
        > This makes the 'churchAPP directory' a python package
        > Once churchAPP is imported the ``_init_.py``  runs automatically
    - **modules.py** 
        > This file heavily comprises of databases
    - **views.py** 
        > Main views, it controls all url endpoints for routing
        > It also deals with functionality on the frontend data 
- **app.py**
    This file will be run when starting the webserver of this application
    
