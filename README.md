
# Adult Census Income Prediction

## Table of contents
  * [Demo](#demo)
  * [Overview](#overview)
  * [Project Goal](#project-goal)
  * [Technical Aspect](#technical-aspects)
  * [Installation](#installation)
  * [Bug / Feature Request](#bug-/-feature-request)
  * [Technologies Used](#technologies-used)
  * [License](#license)

## Demo

• Link for web application : https://RC4AY4PAPGU43DRW.anvil.app/64HFEKAECYBC2L6EWO2BEZ2Q

• Working of web application on a PC

![image](https://drive.google.com/uc?export=view&id=1U-FilTN57By-6lA3TTEFZ2-JUfK5sILH)

• Working of application on mobile phone

![Alt Text](https://drive.google.com/uc?export=view&id=1TyHE6cXdYE8tPb74qwqUxbz7sXwa5b8b)

## Overview

This is a classification problem where we need to predict whether a person earns more than a sum of 50,000 USD anuually or not. This classification task is accomplished by using a CatBoost Classifier trained on the dataset extracted by Barry Becker from the 1994 Census database. The dataset contains about 33k records and 15 features which after all the implementation of all standard techniques like Data Cleaning, Feature Engineering, Feature Selection, Outlier Treatment, etc was feeded to our Classifier which after training and testing, was deployed in the form of a web application.

## Project Goal

This end-to-end project is made as a part of data science internship for [Ineuron.ai](https://ineuron.ai/).

## Technical Aspects

The whole project has been divided into three parts. These are listed as follows :

• Data Preparation : This consists of storing our data into cassandra database and utilizing it, Data Cleaning, Feature Engineering, Feature Selection, EDA, etc.

• Model Development : In this step, we use the resultant data after the implementation of the previous step to cross validate our Machine Learning model and perform Hyperparameter optimization based on various performance metrics in order to make our model predict as accurate results as possible.

• Model Deployment : This step include creation of a front-end using Anvil, running the model in our local system and connecting it to webapp with the help of anvil uplink.

## Installation

The Code is written in Python 3.9. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after cloning the repository:
```bash
pip install -r requirements.txt
```

### Run on your Local Machine

Jupyter Notebook connected to anvil webapp is used to predict outcomes using tarined model.pkl file.

## Bug / Feature Request
If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue [here](https://github.com/kldpsh7/income-prediction/issues/new) by including your search query and the expected result.

If you'd like to request a new function, feel free to do so by opening an issue [here](https://github.com/kldpsh7/income-prediction/requests/new). Please include sample queries and their corresponding results.

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

• Python Programming language

• Jupyter Notebook

• Anvil framework

## Appendix

Link for youtube video regarding description of the project : https://youtu.be/b9UdJ8RHMvI

Link for App Documentation : [Here](https://github.com/Kldpsh7/income-prediction/tree/main/docs)

## Author

[Kuldeep Sharma](https://github.com/kldpsh7)
## License

[GNU](https://choosealicense.com/licenses/gnu/)
GNU GENERAL PUBLIC LICENSE
                       Version 3, 29 June 2007

 Copyright (C) 2007 Free Software Foundation, Inc. <https://fsf.org/>
 Everyone is permitted to copy and distribute verbatim copies
 of this license document, but changing it is not allowed.
