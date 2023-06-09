# IS4242_Group7 Course Project (AY22/23 Sem 2)

## Predicting Property Prices
Contributed by Arjan, XiaoDong, Marco, Lucas, Ludvig and Gerald :)

## About
This project aims to accurately forecast property prices in Singapore to assist buyers and investors to make better-informed decisions.

## Requirements
- Jupyter Notebook [Jupyter](https://jupyter.org/install) or [Install Anaconda and run Jupyter Notebook from it](https://docs.anaconda.com/anaconda/install/index.html)
- Python

There are some general library requirements for the project and some which are specific to individual methods. The general requirements are as follows.

- `numpy`
- `scikit-learn`
- `scipy`
- `seaborn`
- `matplotlib`

The library requirements specific to some methods are:

- `keras` with `TensorFlow` backend for Neural Network.
- `xgboost` for XGBoost.

Note: It is recommended to use Anaconda distribution of Python.

## Installation

For a true interactive use of the notebooks you need to install Python, Jupyter Notebook and the required libraries scikit-learn, matplotlib and numpy. More tips on installing scikit-learn can be found on the [scikit-learn website](https://scikit-learn.sourceforge.net/dev/install.html#installing-an-official-release).

Install Python's package installer `pip`  
Download the script [get-pip.py](https://bootstrap.pypa.io/get-pip.py) then run `$ python get-pip.py` on terminal/command prompt

`pip install` the following libraries and modules
- `selenium`
- `webdriver_manager`

## Structure
- `data/api_responses`: contains data files retrieved from Urban Redevelopment Authority, Land Transport Authority and OneMap
- `data/data_ingestion`: contains Jupyter Notebooks detailing the merging of the datasets
- `data/web_scrape`: contains a Jupyter Notebook used to web scrape ratings for properties
- `data/Transactions with MRT, Bus, Taxi, Crime, Ratings.csv`: Final dataset obtained after data ingestion
- `data/X_test.csv` `data/X_train.csv` `data/y_train.csv` `data/y_test.csv`: Data split into their respective train and test sets after preprocessing

- `preprocessing/`: contains EDA & Preprocessing Jupyter Notebook and preprocessing objects to be used during preprocessing

- `models`: contains ML models used in this project

## Usage
Before running the notebooks, ensure that all required libraries have been installed and required datafiles are in the same working directory as the notebooks.
