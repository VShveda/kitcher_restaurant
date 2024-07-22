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


## Links


- Project homepage: .....
- Repository: https://github.com/VShveda/kitchen_restaurant

## Demo
![title.png](title.png)
![cook_list.png](cook_list.png)
![list_of_type.png](list_of_type.png)
![dish_list.png](dish_list.png)