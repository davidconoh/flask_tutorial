# flask_tutorial

A simple web app that demonstates building with Flask and deploying to the cloud at [https://flask-tutorial-demo.herokuapp.com/](https://flask-tutorial-demo.herokuapp.com/).

This application supports the [Getting Started with Python on Heroku](https://devcenter.heroku.com/articles/getting-started-with-python) article - check it out.

## Running Locally

Make sure you have Python 3.8 [installed locally](http://install.python-guide.org). To push to Heroku, you'll need to install the [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli).

```sh
$ git clone https://github.com/davidconoh/flask-tutorial-demo.git
$ cd flask-tutorial-demo
```

Setup your Python environment and install the required dependencies:

```sh
$ virtualenv myvenv
$ source myvenv/bin/activate

$ pip install -r requirements.txt

$ python main.py
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Heroku

```sh
$ heroku create
$ git push heroku master

$ heroku open
```
or

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Documentation

For more information about using Python on Heroku, see these Dev Center articles:

- [Python on Heroku](https://devcenter.heroku.com/categories/python)

# Resources

- Heroku Dev Center [Getting Started on Heroku with Python](https://devcenter.heroku.com/articles/getting-started-with-python?singlepage=true)
- Salvador Villalon [How to build a web application using Flask and deploy it to the cloud](https://www.freecodecamp.org/news/how-to-build-a-web-application-using-flask-and-deploy-it-to-the-cloud-3551c985e492/)