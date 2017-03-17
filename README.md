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
venv  <virtual_env_folder>

For python version 3.4 and above,
cd into VDT and then create a virtual environment with the following command

        $ python -m venv venv

You will end up with a folder named 'venv' that contains a complete Python environment ready to be used for this project

#### Install Flask:

        $ venv\Scripts\pip install Flask

## Running the application:

### For Windows,

#### Activate virtual environment:

        $ venv\Scripts\activate

#### Run the application:

        $ venv\Scripts\python run.py
        
### For Mac OS,

#### Activate virtual environment:

        $ venv\Scripts\activate

#### Run the application:

        $ venv\Scripts\python run.py


By default the server runs at 
http://localhost:5000


