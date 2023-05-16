# YaMDb
### The YaMDb project collects users feedback on products. The products themselves are not stored in YaMDb; you cannot watch a movie or listen to music here.
___
### Grateful or indignant users leave text reviews for the products and rate the product in the range from one to ten; from user ratings, an average rating of the product is formed. A user can leave only one review per work.
___

## Local launch

### Create a virtual environment
```
python3 -m venv venv
```
### Activate virtual environment
```
source venv/bin/activate
```
### Install dependencies
```
pip install -r requirements.txt
```
### Make migrations
```
python manage.py migrate
```
### Load test database(not necessary)
```
python manage.py download_db
```
### Start local server
```
python manage.py runserver
```
### This link has detailed documentation
```
http://127.0.0.1:8000/redoc/
```
