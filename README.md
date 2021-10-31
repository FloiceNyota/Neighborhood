# My Neighborhood

#### By Floice Nyota Ndiiya

---
# Description  
This is a Django web application where users can set profile about them and a general location and their neighborhood name.
 
---
## User Stories  
User Can :-

* Sign in with the application to start using.
* Set up a profile about me and a general location and my neighborhood name.
* Find a list of different businesses in my neighborhood.
* Find Contact Information for the health department and Police authorities near my   neighborhood.
* Create Posts that will be visible to everyone in my neighborhood.
* Change My neighborhood when I decide to move out.
* Only view details of a single neighborhood.

---
## Access the website
Need the latest browser to be able to View

Follow this link https://floice-neighborhoo-web.herokuapp.com/

It is hosted by heroku

---

## Setup and Installation  
To get the project .......  
  
##### Clone Repository:  
 ```bash 
https://github.com/FloiceNyota98/Neighborhood.git
```
##### Install and activate Virtual Enviroment virtual  
 ```bash 
cd Neighborhood && python3 -m venv virtual && source virtual/bin/activate 
```  
##### Install Dependencies  
 ```bash 
 pip install -r requirements.txt 
```  
##### Setup Database  
  SetUp Database User,Password, Host then following Command  
 ```bash 
python manage.py makemigrations awwards_app 
 ``` 
 Now Migrate  
 ```bash 
 python manage.py migrate 
```
##### Run Application  
 ```bash 
 python3 manage.py server 
```
##### Test Application  
 ```bash 
 python manage.py test photo
```
Open the application on your browser `127.0.0.1:8000`.  
  
  
## Technology used  
  
* HTML, CSS, Bootstrap

* Git

* Python, Django Framework

* Heroku 
  
  
## Bugs  
* It may take a while to load due to the size of the photos
  
## Contact Details
nyotafloice@gmail.com

@FloiceNyota (Twitter)

@Floice Nyota `Slack Moringa`

---

### License
This Project is under the [MIT](LICENSE) license