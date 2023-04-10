# End to End Project
## Create a virtual environment

```
C:/ProgramData/Anaconda3/Scripts/activate

conda activate base

conda create -p venv python=3.8

conda activate venv/
```

## Create README.md file to add info regarding the project

## Create a requirement.txt file to mention all the libraries needed to be installed

## Create setup.py file to make modules of projects into package

## Then install libraries mentioned in requirements.txt into project by using following code:

```
pip install -r requirements.txt
```

## Now form folder src and create following files and folders in it:
### folder: components - create following files in it- __init__.py , data_ingestion.py, data_transformation.py, model_trainer.py
### folder: pipeline - create following files in it- __init__.py , prediction_pipeline.py, training_pipeline.py
### file: __init__.py



## Create .gitignore in vs code to remove unwanted folders and files from github and:
### in that file copy-paste  following things in the github link:
FSDSRegression/.gitignore at main · krishnaik06/FSDSRegression (github.com) 



## Make github repository and connect it with project folder
```
git init

git add .

git commit -m "first commit"

git remote -v

git branch

git branch -M main

git remote add origin https://github.com/RSRemya/Regression_gemstone_endtoend.git

git push -u origin main
```