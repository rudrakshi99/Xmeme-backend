# Xmeme-backend

[![Run in Postman](https://run.pstmn.io/button.svg)](https://documenter.getpostman.com/view/14143990/TWDRtfoy)
[![View in Swagger](http://jessemillar.github.io/view-in-swagger-button/button.svg)](https://rudrakshi-xmeme.herokuapp.com/swagger-ui/)
## Features :

* It is capable of receiving the posted meme inputs from the frontend and store them in a database.

* It is capable of fetching the list of memes from the database and send them to the frontend.

### Backend Technologies used:
- Django
- Django Rest Framework
- Heroku
- Sqllite3

<details>
  <summary><strong>Backend Setup Instructions</strong></summary>

- Fork and Clone the repo using
```
git clone https://github.com/rudrakshi99/Xmeme-backend.git
cd backend
```
- Install dependencies using
```
pip3 install -r requirements.txt
```
- Make migrations using
```
python3 manage.py makemigrations
```
- Migrate Database
```
python3 manage.py migrate
```
- Create a superuser
```
python3 manage.py createsuperuser
```
- Run server using
```
python3 manage.py runserver
```
</details>

### Important Links :
* **Publicly Deployed Link :** https://rudrakshi-xmeme.herokuapp.com/memes/
* **End-Point :** /memes
