# DJANGO AUTHENTICATION API.
This project is done with the aim of learning about **Django REST framework** and also building an **AUTHENTICATION API**.

## Programming Language Used:
* Python Programming Language

## Technologies Used:
All of the following are technologies used in this project:

| Backend | Django |
| -------- | ----------- |
| Api | Django REST framework |
| -------- | ----------- |
| Project Management and Version Control | Github |
| -------- | ----------- |
| Database | sqlite |
| -------- | ----------- |
| Test of Endpoints | Postman |

## Features
[__Register__]- Anyone can register by filling up thr registeration form by giving their details like email, firstname, lastname, password and username.

[__Login__] - Only Registered users can login using just their username and password.

[__Logout__] - Login user can logout using their token.

[__UserDetails__] - user details which includes id, email, and username can be viewed by using the users token.

[__ResetPassword__] - user can reset password sending a request to the registered email and a token will be given which you can use to reset the account password.

[__ChangePassword__] - registered user can change the password by giving the old password and giving a new password and also the account token.


## EndPoints Test
* Application used for testing the endpoints - *POSTMAN*

[__REGISTER ENDPOINT__]

USER REGISTERATION TEST. 
| Request | POST |
| -------- | ----------- |
| Url | http://127.0.0.1:8000/api/register/ |
| -------- | ----------- |
| Select body, and then click on form-data | fill in these keys  : username, password, email, first_name and last_name *fill in your values for the keys and send* |
| -------- | ----------- |
| status | 200_OK - Registeration was successful.|
| -------- | ----------- |
| status | 400 Bad Request - Error in registeration |


[__LOGIN ENDPOINT__]

LOGIN REGISTERATION TEST.


* UserDetails Endpoint - 
* Change Password Endpoint - 
* Reset Password Endpoint - 
* Logout Endpoint - 

## Project Status
Project is : *in progress*

## Collaboration 
Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated** 🤝

## Dependencies
* asgiref==3.6.0
* cffi==1.15.1
* cryptography==40.0.1
* Django==4.1.7
* django-rest-knox==4.2.0
* django-rest-passwordreset==1.3.0
* djangorestframework==3.14.0     
* pycparser==2.21
* pytz==2023.2
* sqlparse==0.4.3
* tzdata==2023.2
### Getting Started
Setting up project locally is a pretty easy step.

1. Clone the repo
  ```sh
  git clone https://github.com/Kis123mas/API-AUTHENTICATION.git
  ```
2. Move into the project directory
  ```
  cd authentication
  ```
3. Create a virtual environment
  ```
  python -m virtualenv venv 
  ```
4. Activate the virtual environment
  ```
  venv\Scripts\activate
  ```
6. Install pip dependencies
  ```
  pip install -r requirements.txt
  ```
8. Make Migrations
  ```
  py manage.py makemigrations
  ```
9. Migrate to Database
  ```
  py manage.py migrate
  ```
10. Create a superuser
   ```
   py manage.py createsuperuser
   ```
11. Run Server
   ```
   py manage.py runserver
   ```

<br/>
