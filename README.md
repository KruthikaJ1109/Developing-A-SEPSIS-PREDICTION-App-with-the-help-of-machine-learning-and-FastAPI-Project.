
# 🚀 Developing A SEPSIS PREDICTION App with the help of machine learning and FastAPI Project. 🚀

[![View My Profile](https://img.shields.io/badge/View-My_Profile-green?logo=GitHub)](https://github.com/justinjabo250)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5?logo=linkedin&logoColor=orange)](https://www.linkedin.com/in/jabo-justin-2815341a2/) 
[![View Repositories](https://img.shields.io/badge/View-My_Repositories-blue?logo=GitHub)](https://github.com/justinjabo250?tab=repositories)
[![View My Profile](https://img.shields.io/badge/MEDIUM-Article-purple?logo=Medium)](https://medium.com/@jabojustin250/sepsis-prediction-using-fastapi-and-machine-learning-categorization-6b0a5db6805b)
[![Docker App](https://img.shields.io/badge/Gradio-App-yellow)](https://huggingface.co/spaces/Justin-J/Building-and-Deploying-a-Machine-Learning-Models-Using-Gradio-Application)
[![Articles](https://img.shields.io/badge/My-Portfolio-darkblue?logo=Website)](https://justinjabo250.github.io/Developing-a-web-application-for-an-online-portfolio./)
[![View GitHub Profile](https://img.shields.io/badge/GitHub-Profile-darkgreen)](https://github.com/justinjabo250)


# Developing A SEPSIS PREDICTION App with the help of machine learning and FastAPI Project.

![Sepsis_predict](https://github.com/justinjabo250/Developing-A-SEPSIS-PREDICTION-App-with-the-help-of-machine-learning-and-FastAPI-Project./assets/115732734/32699bd0-6446-4cf3-a7a7-45bbc329d682)

## Introduction


We will explore a comprehensive machine learning project focused on predicting sepsis using classification techniques. By leveraging FastAPI, we were able to deploy the model as a user-friendly API, enabling real-time predictions. The combination of machine learning and web development has immense potential in healthcare and can significantly contribute to early sepsis detection and patient care.

![Sepsis_Pedit](https://github.com/justinjabo250/Developing-A-SEPSIS-PREDICTION-App-with-the-help-of-machine-learning-and-FastAPI-Project./assets/115732734/39545265-9dbb-41b7-a817-0d70da523e0a)

## The Goals of this Project

The major goal of this project is to develop a classification model that can accurately differentiate between sepsis and non-sepsis cases by using a dataset that contains essential information, such as blood test results, blood pressure, BMI, and patient age. A Docker container will be used to deploy the created model as a FastAPI-based API.

## Description

## Importance of Project  

The dataset used includes a list of hospital patients, their characteristics, and whether or not they have sepsis.

Severe and potentially fatal illness known as sepsis develops when the body's reaction to an infection results in widespread inflammation. It's frequently called "blood poisoning."

In order to anticipate the occurrence of sepsis, the goal of this study is to investigate the numerous conditions that can result in sepsis.

Sepsis prediction is crucial because early detection and treatment can dramatically enhance patient outcomes. Sepsis can advance quickly and turn life-threatening in a short amount of time. In order to stop the disease from getting worse, healthcare professionals can identify people who are at risk of developing sepsis and start timely treatment and treatments.

# Dataset Description -

The data for this project is in a csv format. The following describes the columns present in the data.

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

Install the required packages to be able to run the evaluation locally.

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

1. **Create the Python's virtual environment** that isolates the required libraries of the project to avoid conflicts;
2. **Activate the Python's virtual environment** so that the Python kernel & libraries will be those of the isolated environment;
3. **Upgrade Pip, the installed libraries/packages manager** to have the up-to-date version that will work correctly;
4. **Install the required libraries/packages** listed in the `requirements.txt` file so that it will be allow to import them into the python's scripts and notebooks without any issue.

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
![ezgif com-optimize (1)](https://github.com/ikoghoemmanuell/Machine-Learning-API-using-FastAPI/assets/102419217/a8352c5f-afea-43b1-8bf5-c24607cf3481)
![ezgif com-crop](https://github.com/ikoghoemmanuell/Machine-Learning-API-using-FastAPI/assets/102419217/df0ed5a8-2daf-47ca-a4f5-e6128429d5d3)

## Resources

Here are some ressources you would read to have a good understanding of FastAPI :

- [Tutorial - User Guide](https://fastapi.tiangolo.com/tutorial/)
- [Video - Building a Machine Learning API in 15 Minutes ](https://youtu.be/C82lT9cWQiA)
- [FastAPI for Machine Learning: Live coding an ML web application](https://www.youtube.com/watch?v=_BZGtifh_gw)
- [Video - Deploy ML models with FastAPI, Docker, and Heroku ](https://www.youtube.com/watch?v=h5wLuVDr0oc)
- [FastAPI Tutorial Series](https://www.youtube.com/watch?v=tKL6wEqbyNs&list=PLShTCj6cbon9gK9AbDSxZbas1F6b6C_Mx)
- [Http status codes](https://www.linkedin.com/feed/update/urn:li:activity:7017027658400063488?utm_source=share&utm_medium=member_desktop)

## 👏 Support

If you found this article helpful, please give it a clap or a star on GitHub!

## Author

- [Justin Jabo](https://www.linkedin.com/in/jabo-justin-2815341a2/)
