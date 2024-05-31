  # Blog Proyect With Django 

  This Project was created to remember the basics of Django follow the steps
  to set up this project

  ## Get Started 🚀  Run Locally  

  Create and enter the project directory
  ~~~bash
  mkdir blango_project
  cd blango_project
  ~~~
  
  Create and activate virtual environment
  ~~~bash  
  python3 -m venv env
  source env/bin/activate  
  ~~~

  Clone the repository
  ~~~bash  
    git clone https://link-to-project
  ~~~
  
  Go to the project directory  
  ~~~bash  
    cd my-project
  ~~~
  
  Install dependencies  
  ~~~bash  
  pip install -r requirements.txt
  ~~~

  Create Superuser and apply migrations 
  ~~~bash
  python3 manage.py createsuperuser
  python3 manage.py makemigrations
  python3 manage.py migrate
  ~~~

  Start the server 
  ~~~bash
  python3 manage.py runserver 
  ~~~
