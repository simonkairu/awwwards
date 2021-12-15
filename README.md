# awwwards

#### 13/12/2021  

#### By **Simon Kairu** 

## Description  
 awwwards is a django application that allows users  to post projects that they have created 

 ## User Story

* User can signup & signin to the application
* User can post projects they have worked on
* Current user is able to edit there profile
* Current user is able to view their profile page with the projects they posted
* User is able to view other users posted projects and rate them
* When user clicks on a single project it navigates to another page where user is able to view the details of the project and rate it
* User is able to search for different projects

## Prerequisites

You need the following to start working on this project: On your local system; 

1. Python3.8
2. Django
3. Virtual Environment(venv)
4. A text editor

## Development Installation

To get the code..

1. Clone the repository:
 `git clone  https://github.com/simonkairu/awwwards.git`

2. Move to the folder and install requirements
 ` cd awwwards-`

3. In the projects root directory, install the virtualenv library using pip and create a virtual environment. Run the following commands respectively:
    - **`pip install virtualenv`**
    - **`virtualenv venv`**
    - **`. venv/bin/activate`**
        * Note that you can exit the virtual environment by running the command **`deactivate`**
4. Download the all dependencies in the requirements.txt using **`pip install -r requirements.txt`**
5. Launch the application locally by running the command **`python3.8 manage.py runserver`** and copying the link given on the termnal on your browser.
    - To upload photos as admin, run the command  **`python3.8 manage.py createsuperuser`** to create an admin account in order to post. Access to the admin panel is by adding the path /admin to the address bar.
6. Run tests by running the command **`python3.8 manage.py test awwwards`**

## Known Bugs
There are no known bugs so far  

## Technologies Used  
* Python v3.8  
* HTML
* Bootstrap
* Django  
* Postgres  

## Support and contact details
In case of any problem while interacting with the web application, reach out to me at simon.mureithi@student.moringaschool.com