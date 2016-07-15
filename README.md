# Implementation of fibonacci-rest-app in Python

### Prerequisites
    1. Python >= 2.7.X, < 3.X

**Steps to build the Project**
* To set up the app, clone the project
* Install dependencies **pip install -r setup/requirements.txt**
* Run the application using **python app.py**
* Run individual test files test.py and func_test.py or use **python -m unittest discover**

**USAGE**
* By default the app runs on 5000
* Set **debug=False** in production (done via config.yaml)
* Once the app is running access the app using the following REST APIs
     * http://[ip or hostname]:[port]/v1/fibonacci/get/[num]

**Features**
Implemented using flask-restful module in python.
The Web service accepts get call at the defined endpoints and throws forbidden error otherwise
The Rest API exposes a novel implementation of Fibonacci which serves a fibonacci series for a given * integer value n as a response to a GET call.
If a negative value is passed error message will appear in response.
If a non-numeric value is passed error message will appear in response.
As problem size grows option of using caching
All configurable parameters are placed in a central yaml config file

Tests
* There are two tests one is a functional test and other is a unittest that i have written for this project. I have tested the status code and json payload in functional testing. And fibonacci logic in unit testing.
