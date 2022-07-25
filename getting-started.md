# Getting Started

**It is recommended to use Google Colab to run all this project notebooks.**

## Using Python Virtual Environment

To run this project in a Python virtual environment, we need to create a virtual environment.

````
python -m venv .venv
````

To activate the virtual environment in Windows, run:

````
.venv\Scripts\activate.bat
````

To deactivate the virtual environment in Windows, run:

````
.venv\Scripts\deactivate.bat
````

To check if the virtual environment is active and you're using the virtual environment `pip` command, run:

````
pip -V
````

If the path it displays points to a subdirectory of your virtual environment, then you're using the virtual environment.

## Installing Python Packages

If you need to recreate the virtual environment, you can reinstall all of the needed packages with the command:

````
pip install -r requirements.txt
````

## Removing the Virtual Environment

When you no longer need the virtual environment, you can just delete its directory.