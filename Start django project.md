<h1><p align="center">Virtualenv</p></h1>
 
### Create Folder

```
mkdir Shoriot
cd Shoriot
```


### Create virtualenv

```python
$ pip install virtualenv
$ virtualenv --version
```

### To activate virtualenv
```python
$ virtualenv venv
$ venv\Scripts\activate 
```


### To install django

```python
$ pip install django 
```

### To install specific django version

```python
pip install Django==3.1

$ python -m django --version

or type 

$ pip freeze 
```


### To Start project

```python
django-admin startproject sms
cd sms
```

### To create app

```python
python manage.py startapp account
```

### To runserver

```python
python manage.py runserver
```