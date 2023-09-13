# DjangoLearningApp
This application was built as a part of learning Django. So far we just have a simple 'Hello World' page being displayed. A dockerfile is also included for ease of development/future deployment.

## Setup
1. Pull repo down.
2. If you wish you can use [venv](https://docs.python.org/3/tutorial/venv.html) for a local dev environment.
3. Dockerfile is also provided. To use first build with: 

` docker build -t django-learning-app .`
4. Then:

` docker run -it -p 8000:8000 django-learning-app`

5. Go to [http://localhost:8000/](http://localhost:8000/) to see the app running. 

## Resources
To setup the initial structure of this app I used [this link](https://dockerize.io/guides/python-django-guide). 