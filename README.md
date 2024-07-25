# Kitchen restaurant
> I am glad to see you! 
> I want to present you my first project related to the service sector. 
> If you work in the kitchen you might find it useful. 
> I hope you like it!

This is a Django project that allows chefs to create dishes and assign them to specific types of dishes. 

## Installing / Getting started

A quick introduction of the minimal setup you need to get.

```shell
git clone the-link-from-your-forked-repo
git checkout -b develop
python -m venv venv
venv\Scripts\activate (on Windows)
source venv/bin/activate (on macOS)
pip install -r requirements.txt
```

The first step is to clone the repository.
Then go to the branch develop and create and move to a virtual environment.
Install the necessary packages.

## Developing

Attention. 
Please note that there is an ".env.template" file

```shell
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
```

Create and activate migrations.
Created superuser. 


## Configuration

If you want, you can fill in the database with:

```shell
python manage.py loaddata test_data.json
```
Or add it yourself.


## Contributing

If you'd like to contribute, please fork the repository and use a feature
branch. Pull requests are warmly welcome.

## Features

* You can add cooks.
* You can add type dish.
* You can add dish.
* You can update end delete any unit in the server database.


## Links

If you want to test the site (NOT TO LOCAL):

```shell
user - admin
password - TtYyUuIi1234
```

- Project homepage: https://kitchen-restaurant-91j0.onrender.com/
- Repository: https://github.com/VShveda/kitchen_restaurant

## Demo
![title.png](skrin_to_readme/title.png)
![cook_list.png](skrin_to_readme/cook_list.png)
![list_of_type.png](skrin_to_readme/list_of_type.png)
![dish_list.png](skrin_to_readme/dish_list.png)