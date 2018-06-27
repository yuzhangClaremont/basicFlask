# leaning flask

## postgresql

create database learningflask;

uninstall
```
$ cd /Library/PostgreSQL/10
https://www.enterprisedb.com/docs/en/10.0/instguide/PostgreSQL_Installation_Guide.1.21.html
```

## virualenv - flask
isolate env for python library installed

```
virtualenv venv
```
to create venv environment with fresh python 


```
source venv/bin/activate
```

```
pip install flask
```
## deployment app heroku

after download in command line input

    ```
    heroku login
    ```

# request - response cycle

## homepage

# Deploy to Heroku

in project venv
    ```
    pip install gunicorn
    ```

log the library needed for project
    ```
    pip freeze > requirement.txt
    ```

add Procfile to tell Keroku run Flask using Gunicorn
    ```
    touch Procfile
    ```
add "Web: gunicorn routes:app" to Procfile

create subdomine 
    ```
    heroku create
    ```
https://salty-atoll-16806.herokuapp.com/ | https://git.heroku.com/salty-atoll-16806.git

git add commit push

push to heroku

    ```
    git push heroku master
    ```

error logs
    ```
    heroku logs
    ctrl+c
    ```

# database
pip install flask-sqlalchemy

# login form

    ```
    pip install flask-wtf
    ```

# map funciton 
wikipedia geodata api

https://www.mediawiki.org/wiki/Extension:GeoData

    ```
    pip install geocoder
    ```