# dataViz

## Requirements

Python 2.7 or later version


## Setting up

### For Windows,

Choose a location where you want your application to live and create a new folder 'VDT' there to contain it. 
VDT is the application folder.

        $ mkdir VDT
        $ cd VDT
        
#### Install virtual environment:

For python version older than 3.4,

        $ pip install virtualenv
        $ virtualenv venv
        
venv is the name of your virtual environment folder. You can call it anything you want.

For python version 3.4 and above,
cd into VDT and then create a virtual environment with the following command

        $ python -m venv venv
        
#### Install Flask:

For Windows,

        $ venv\Scripts\pip install Flask 
        
For Mac OS X,

        $ venv/bin/pip install flask

        
### For Mac OS,

#### Install virtual environment

        $ sudo easy_install virtualenv
        
#### Install Flask

        virtualenv venv
. venv/bin/activate
 



You will end up with a folder named 'venv' that contains a complete Python environment ready to be used for this project


## Running the application:

### For Windows,

#### Activate virtual environment:

        $ venv\Scripts\activate

#### Run the application:

        $ venv\Scripts\python run.py
        
### For Mac OS,

#### Activate virtual environment:

        virtualenv venv
        . venv/bin/activate

#### Run the application:

        ./run.py


By default the server runs at 
http://localhost:5000


