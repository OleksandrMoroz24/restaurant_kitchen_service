# restaurant_kitchen_service
Imagine you are the owner of restaurant, and you want to improve the communication & rules 
between your cooks on the kitchen.

Problem
For this purpose you want to build management system, in which Cooks can create new Dishes & Dishtypes, 
and also specify, Cooks which are responsible for every Dishes cooking.

Usage scenarios
Chefs can easily add new recipes and assign people who are responsible for their preparation.
Management can quickly get an overview of who is responsible for preparing certain dishes,
which improves planning in the kitchen.


DB Structure:
![DB Structure](https://media.mate.academy/Kitchen_Service_d1fcaa4cdb.png)
## Site:
My project deployed to render.com
with using aws3 for media files

Link to the site:
https://restaurant-kitchen-service-s8sj.onrender.com

Test user:
Login: testuser
Password: User1337

## Setting up the environment:

Python3 must be already installed

Windows
```shell
git clone https://github.com/OleksandrMoroz24/restaurant_kitchen_service.git
cd restaurant_kitchen_service
python -m venv venv
.\\venv\\Scripts\\activate
pip install -r requirements.txt
python manage.py runserver
```

MacOS
```shell
git clone https://github.com/OleksandrMoroz24/restaurant_kitchen_service.git
cd restaurant_kitchen_service
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python manage.py runserver
```
