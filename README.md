# Analysing-Web-Statistics
## Problem Statement :
We have dataset (web_taffic.tsv) which contains :
- Hour
- Number of users visited our website in the given hour.

We will be predicting the hour at which we will cross 100,000 hits/hour on our website.

***100,000 hits/hour = 100,000 users visited our website in 1 hour.*

## Pre-Requisites :
### For Mac user:
Create a project directory and open a terminal instance in project directory. Run following commands to setup environment and pre-requisites.
- Get source code : git clone https://github.com/x-coderx/Analysing-Web-Statistics.git
- Install Python : brew install python@3.9
- Create your virtual environment : python3.9 -m venv venv
- Activating your virtual environment : source venv/bin/activate
- Install Requirements : python3.9 -m pip install -r requirements.txt
- Finally, run "analyzw_webstats.py"

### For Windows user:
Create a project directory and open a cmd instance in project directory. Run following commands to setup environment and pre-requisites.
- Get source code : git clone https://github.com/x-coderx/Analysing-Web-Statistics.git
- Download latest python version from : https://www.python.org/ftp/python/3.12.1/python-3.12.1-macos11.pkg and install.
- Create your virtual environment : python -m venv venv
- Activating your virtual environment : venv\scripts\activate
- Install Requirements : python -m pip install -r requirements.txt
- Finally, run "analyzw_webstats.py"

## Idea :
Idea is to use curve-fitting and Logistic Regression on our data in order to predict the hour at which we will cross 100,000 hits/hour on our website.

