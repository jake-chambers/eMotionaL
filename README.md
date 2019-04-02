<!-- PROJECT LOGO -->
  <h1>eMotionaL</h1>
<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
* [Built With](#built-with)
* [Contact](#contact)
* [Installation](#installation)


<!-- ABOUT THE PROJECT -->
## About The Project
Awarded most innovative project. Fourth year capstone project that can predict human emotion through vocal input using      machine learning techniques (Keras & Tensorflow).

This project set out to determine the emotion of the user based on only vocal analysis. To do this a convolutional neural network was used to train a model that could predict emotions with ~%80 accuracy.

### Built With
Here is the tech used to create this project.
* [JavaScript](https://www.javascript.com/)
* [JQuery](https://jquery.com)
* [Python](https://www.python.org/)
* [Flask](http://flask.pocoo.org/)
* [Tensorflow](https://www.tensorflow.org/)
* [Keras](https://keras.io/)


<!-- CONTACT -->
## Contact

Jacob Chambers - [LinkedIn](https://www.linkedin.com/in/jacob-chambers-3bb06112b/) - jake_chambers12@hotmail.com


<!-- Installation -->
## Installation
1. Install virtualenv: https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/26/python-virtual-env/ 
2. Make sure you have python 3.7 installed on you computer. You can download it here at: [Python](https://www.python.org/)
3. Once you have your virtualenv installed, cd to the directory which your virtual env is stored. Next run this command: `virtualenv --python=/Library/Frameworks/Python.framework/Versions/3.7/bin/python3 ./emotional/` 
4. Next, run your virtualenv.
5. Once in your virtualenv, cd to the directory where eMotionaL was downloaded then cd into eMotional.
6.  Run: `pip install -r requirements.txt`. This will install all the required dependencies.
7. cd into the second eMotionaL folder in the project and then run: `python server.py`. This will host eMotionaL at: http://localhost:5000/ 
