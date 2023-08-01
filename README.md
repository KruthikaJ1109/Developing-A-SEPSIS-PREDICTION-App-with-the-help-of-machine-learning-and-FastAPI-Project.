# ML-based prediction using the FastAPI

[![View Repositories](https://github.com/justinjabo250?tab=repositories)](https://github.com/justinjabo250?tab=repositories)
[![View My Profile](https://www.linkedin.com/in/jabo-justin-2815341a2/)](https://github.com/justinjabo250?tab=repositories)


# Developing-A-Machine-Learning-API-Project-Using-FastAPI
The major goal of this project is to develop a classification model that can accurately differentiate between sepsis and non-sepsis cases by using a dataset that contains essential information, such as blood test results, blood pressure, BMI, and patient age. A Docker container will be used to deploy the created model as a FastAPI-based API.

Develop a Machine Learning API (Application Programming Interface) using FastAPI.

![ai(3)](https://github.com/justinjabo250?tab=repositories)

## Introduction

We will examine a complete machine learning project that uses classification methods to forecast sepsis. We were able to expose the model as a user-friendly API and provide real-time predictions by utilizing FastAPI. Web development and machine learning have enormous promise in the healthcare industry and can considerably improve patient care and the early detection of sepsis.

## Description

## Importance of Project  

The dataset used includes a list of hospital patients, their characteristics, and whether or not they have sepsis.


Severe and potentially fatal illness known as sepsis develops when the body's reaction to an infection results in widespread inflammation. It's frequently called "blood poisoning."


In order to anticipate the occurrence of sepsis, the goal of this study is to investigate the numerous conditions that can result in sepsis.


Sepsis prediction is crucial because early detection and treatment can dramatically enhance patient outcomes. Sepsis can advance quickly and turn life-threatening in a short amount of time. In order to stop the disease from getting worse, healthcare professionals can identify people who are at risk of developing sepsis and start timely treatment and treatments.


# Description of the dataset

This project's data is in csv format. The columns that make up the data are described below.


| Column Name | Target | Description                                                                   |
| ----------- | ------ | ----------------------------------------------------------------------------- |
| ID          | N/A    | Unique number to represent patient ID                                         |
| PRG         | False  | Plasma glucose                                                                |
| PL          | False  | Blood Work Result-1 (mu U/ml)                                                 |
| PR          | False  | Blood Pressure (mm Hg)                                                        |
| SK          | False  | Blood Work Result-2 (mm)                                                      |
| TS          | False  | Blood Work Result-3 (mu U/ml)                                                 |
| M11         | False  | Body mass index (weight in kg/(height in m)^2                                 |
| BD2         | False  | Blood Work Result-4 (mu U/ml)                                                 |
| Age         | False  | patients age (years)                                                          |
| Insurance   | N/A    | If a patient holds a valid insurance card                                     |
| Sepssis     | True   | Positive: if a patient in ICU will develop a sepsis , and Negative: otherwise |

## Setup

To execute the evaluation locally, install the necessary packages.


You need to have [`Python 3`](https://www.python.org/) on your system (**a Python version lower than 3.10**). Then you can clone this repo and being at the repo's `root :: repository_name> ...` follow the steps below:

- Windows:

```python
python -m venv venv; venv\Scripts\activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirements.txt
```

- Linux & MacOs:

```python
python3 -m venv venv; source venv/bin/activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirements.txt
```

The both long command-lines have a same structure, they pipe multiple commands using the symbol `;` but you may manually execute them one after another.

1. **Create the Python's virtual environment** that isolates the project's necessary libraries To prevent conflicts;
2. **Activate the Python's virtual environment** So that the isolated environment's Python kernel and libraries are used;
3. **Upgrade Pip, the installed libraries/packages manager** to the most recent release that will function properly;
4. **Install the necessary libraries and packages** as specified in the requirements.txt file to ensure trouble-free importation into Python scripts and notebooks;

**NB:** For MacOs users, please install `Xcode` if you have an issue.

## Run FastAPI
To run the fastAPI, paste this code to your terminal: 
```python
uvicorn main:app — reload
```

When you run the script and start the web server using Uvicorn, your FastAPI application becomes accessible at
```python
http://127.0.0.1:8000
```
To access the documentation of your API, you can simply add “/docs” to the URL:
```python
http://127.0.0.1:8000/docs
```

## Screenshots
![ezgif com-optimize (1)](https://github.com/justinjabo250?tab=repositories)
![ezgif com-crop](https://github.com/justinjabo250?tab=repositories)

## Resources

You can read the following materials to gain a thorough grasp of FastAPI:


- [Tutorial - User Guide](https://fastapi.tiangolo.com/tutorial/)
- [Video - Building a Machine Learning API in 15 Minutes ](https://youtu.be/C82lT9cWQiA)
- [FastAPI for Machine Learning: Live coding an ML web application](https://www.youtube.com/watch?v=_BZGtifh_gw)
- [Video - Deploy ML models with FastAPI, Docker, and Heroku ](https://www.youtube.com/watch?v=h5wLuVDr0oc)
- [FastAPI Tutorial Series](https://www.youtube.com/watch?v=tKL6wEqbyNs&list=PLShTCj6cbon9gK9AbDSxZbas1F6b6C_Mx)
- [Http status codes](https://github.com/justinjabo250?tab=repositories)

## 👏 Support

If you found this article helpful, please give it a clap or a star on GitHub!

## Author

- [Justin Jabo](https://www.linkedin.com/in/jabo-justin-2815341a2/)

