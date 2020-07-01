# GALLERY
A personal gallery application that you display your photos for others to see.

### Description
The application allows users to view images according to their categories and location. The admin is the one responsible for uploading, editing and deleting images. The users can search for images according to their categories.

## Features
As a user of the web application you will be able to:

1. View different photos that interest me.
2. Click on a single photo to expand it and also view the details of the photo. The photo details must appear on a modal within the same route as the main page.
3. Search for different categories of photos. 
4. Copy a link to the photo to share with my friends.
5. View photos based on the location they were taken.

### BDD Specifications Table
|        User Requirements                 |           Input                           |           Output                         |
|------------------------------------------|-------------------------------------------|------------------------------------------|
| View all images                          |  Go to the home page                      |    All images will be displayed          |
| Search for an image                      | Input the category name in the search bar | All images in that category will display |
| View the image details                   | Click on the image                        | All the image details will be displayed  |
| Copy image                               | Click on the copy link button             | The image link is copied                 |


## Setup/Installation/Running the Application
* Install virtual environment using `$ python3.6 -m venv --without-pip virtual`
* Activate virtual environment using `$ source virtual/bin/activate`
* Download pip in our environment using `$ curl https://bootstrap.pypa.io/get-pip.py | python`
* Install all the dependencies from the requirements.txt file by running `pip3 install -r requirements.txt`
* Create database `CREATE DATABASE gallery`
* run migrations `python3.6 manage.py makemigrations` then `python3.6 manage.py migrate`
* run app `python3.6 manage.py runserver `



## Technologies Used
* Python3.6
* Django
* HTML
* Bootstrap

## Support and Team
Crystal Alice

### Licence [https://github.com/ivxxi/django1/blob/master/Licence]
Copyright(c) 2019  crystal alice
