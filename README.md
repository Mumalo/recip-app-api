# Django Recipe App

## Introduction
The goal os this project is to provide a simple recipe api using Django and Django REST.
The Django version used for this project is 2.1.15


## Getting Started

This project is run with docker using docker-compose. To install Docker Compose, you must first install
Docker Engine. [Check instructions here](https://docs.docker.com/compose/install/)
The DockerFile contains instructions for the docker image called app. It contains instructions for installing 
our requirements for the app and it is based from the python alpine image because it is very light weight. 

To get started, first clone the project from git hub. Run
  ```git clone https://github.com/Mumalo/recip-app-api.git```
  
Since this is run in docker, you dont need any dependencies installed locally. 
Run ```docker-compose build``` to build your images and then run 
    ```docker-compose run app sh -c "python manage.py makemigrations core" ``` To make migrations
    ```docker-compose up``` to start the app
    
## Usage


## Features

* Creating and managing user accounts
* Getting authentication tokens
* Creating and Managing Recipes
* Creating and Managing Tags and Ingredients
* Adding Ingredients and Tags to Recipes
* Filtering Tags and Ingredients by assigned (those assigned to recipes)

## Contributing
I love contributions, so please feel free to fix bugs, improve things, provide documentation. Just send a pull request.
