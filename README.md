# dataViz

## Requirements

Python 2.7 or later version


## Setting up

Choose a location where you want your application to live and create a new folder 'VDT' there to contain it. 
VDT is the application folder.

### For Windows,

        $ mkdir VDT
        $ cd VDT
        
#### Install virtual environment:

For python version older than 3.4,

        $ pip install virtualenv
        $ virtualenv venv
        
venv is the name of your virtual environment folder. You can call it anything you want.

For python version 3.4 and above,

        $ python -m venv venv
        
#### Install Flask:

        $ venv\Scripts\pip install Flask 
        
        
### For Mac OS X,

#### Install virtual environment

        $ sudo easy_install virtualenv
        $ virtualenv venv
    
#### Install Flask

       $ venv/bin/pip install flask

##### You will end up with a folder named 'venv' that contains a complete Python environment ready to be used for this project


## Running the application:

### For Windows,

#### Activate virtual environment:

        $ venv\Scripts\activate

#### Run the application:

        $ venv\Scripts\python run.py
        
### For Mac OS,

#### Activate virtual environment:

        venv/bin/activate

#### Run the application:

        ./run.py


##### By default the server runs at http://localhost:5000


