# MKDocs for the Seedling Project
A static documentation webpage for the Seedling Project.

https://www.mkdocs.org/getting-started/

## Commands (For Maintainers)

- ```git clone https://github.com/kyle-zheng-fati/Seedlingmkdocs.git``` - git command (configured with https rather than ssh) to get the repo on your machine

- ```pip install -r requirements.txt``` - Install dependencies if you are planning to contribute to docs.

- ```pip freeze > requirements.txt``` - Run this command if adding any new dependencies.
    - Note that best practice would be to start a python virtual environment with ```python3 -m venv .venv``` and ```cd .venv && source bin/activate```
    - Substitute ```python3``` with your version of python 
    - To deactivate python virtual environment, ```deactivate```
    - ```.venv``` can be replaced with another name if so desired 


