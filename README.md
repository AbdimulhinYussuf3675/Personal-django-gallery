# Adams~~Gallery

## Author
### [Abdimulhin Adan](https://github.com/AbdimulhinYussuf3675)
## Description
Adams ~~ Gallery is a picture gallery made with django application that allows users display their photos for others to see.

)

## Setup Instructions:
### Requirements

##### 1. Clone the repository
Clone the the repository by running

   ```bash
   git clone https://github.com/AbdimulhinYussuf3675/Personal-django-gallery.git
   ```
 or download a zip file of the project from github


Navigate to the project directory
```bash
cd Personal-django-gallery
```

##### 2. Create a virtual environment
 Install `Virtualenv`

   ```prettier
   pip install virtualenv
   ```

To create a virtual environment named `virtual`, run

   ```prettier
   virtualenv virtual
   ```
To activate the virtual environment we just created, run

   ```bash
   source virtual/bin/activate
   ```

##### 3. Create a database
You'll need to create a new postgress database, Type the following command to access postgress
   ```bash
    $ psql
   ```
   Then run the following query to create a new database named ```picha```
   ```
   # create database picha
   ```


#####  4.Install dependencies
To install the requirements from `requirements.txt` file,

   ```prettier
   pip install -r requirements.txt
   ```

#####  5.Create Database migrations
Making migrations on postgres using django

```prettier
python manage.py makemigrations gallery
```


then run the command below;

 ```bash
 python manage.py migrate
 ```

##### 6.Run the app
To run the application on your development machine,

    python3 manage.py runserver

## Technologies Used
* Django
* Python
* Html
* Css
* Bootstrap3


## User stories
>As a user of the application I should be able to:

* View different photos that interest me.
* Click on a single photo to expand it and also view the details of the photo. The photo details must appear on a modal within      the same route as the main page.
* Search for different categories of photos. (ie. Travel, Food)
* Copy a link to the photo to share with my friends.
* View photos based on the location they were taken.


## Bugs
There are no known bugs at the moment

## License
[![License](https://img.shields.io/packagist/l/loopline-systems/closeio-api-wrapper.svg)](http://opensource.org/licenses/MIT)
>MIT license &copy;  2021 Abdimulhin

# Collaboration Information
* Clone the repository
* Make changes and write tests
* Push changes to github
* Create a pull request

# Contacts
adam.abdimulhi.001@gmail.com