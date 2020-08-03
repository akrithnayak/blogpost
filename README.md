# blogpost
This django application lets your users to post their blogs on site. It facilitates user login, registration and also password reset by email.
Users can also add their profile pictures to their profile


# Prerequisites
   python 3

# Installation

  Go to your project directory and follow these steps:
  
  ### Install requirements
  ``` 
        pip install -r requirements.txt
  ```
  
  ### Create a super user (admin)
  ```
        python manage.py createsuperuser
  
                Username (leave blank to use 'akrith'): akrithnayak
                Email address: akrithnayak2000@gmail.com
                Password: 
                Password (again): 
                Superuser created successfully.
  ```
  ### Seting email and password:
  ```
        Set two environmental variables (Note the casing here):
                1. EMAIL_USER="email@gmail.com"
                2. EMAIL_PASS="passwd"
        This is required because if a user forgets his/her password then he/she can retrive the 
        password by email.
        User will receive an email from email@gmail.com.
        Note: 1. You can only add gmail accounts.
              2. If your gmail account has '2-step verification' enabled then you must create an app password,
                 if not then enable 'Less Secured apps' login in security tab of your account.
  ```
  
 # Usage
  ``` 
        python manage.py runserver
  ```
  
  Type http://localhost:8000/ on your system to view the site.
  To access admin page got to: http://localhost:8000/admin
  

        
