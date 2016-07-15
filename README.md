# Implementation of fibonacci-rest-app in Python
* To set up app clone the project
* Install dependencies **pip install -r setup/requirements.txt**
* Run the application using **python app.py**
* Run individual test files test.py and func_test.py or use **python -m unittest discover**

**USAGE**
* By default the app runs on 5000
* Set **debug=False** in production (done via config.yaml)
* Once the app is running access the app using the following REST APIs
     * http://[ip or hostname]:[port]/v1/fibonacci/get/[num]

Tests
* There are two tests one is a functional test and other is a unittest that i have written for this project. I have tested the status code and json payload in functional testing. And fibonacci logic in unit testing.
