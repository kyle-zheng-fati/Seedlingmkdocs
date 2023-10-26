# Getting Started

## Maintainers

1. Clone the repository onto your local machine 
    - ```git clone https://github.com/ImmaculateDivinity/SeedlingEducation```
    - This uses HTTPS which may require a different format if ```git clone``` is configured with SSH
2.  Create a feature/release/patch/fix branch depending on what you are trying to contribute and switch to that branch
3. Install dependencies (assuming proper installation of npm and pip, and a python virtual environment)
    - ```npm install && pip install -r requirements.txt``` - dev-build dependencies
    - ```pre-commit install``` - pre-commit hooks
4. Periodically update your branch 
``` bash
git checkout <branch_name> # switch to dev branch
git fetch origin           # update dev branch with main branch
git merge origin/main
``` 

## Outside Collaborators 

1. Fork the repository onto your profile 
2. Clone your fork onto your local machine
3. ```git remote add  upstream https://github.com/ImmaculateDivinity/SeedlingEducation``` to add a remote to main repository 
> Please keep your fork updated with the main repository before opening a pull request [Always pull before push]
4. ```git fetch upstream``` to grab changes from the main repository. Alternatively, GitHub offers and option on the website to *Sync Fork*.
5. Create a feature/release/patch/fix branch depending on what you are trying to contribute and switch to that branch
6. Install dependencies (assuming proper installation of npm and pip, and a python virtual environment)
    - ```npm install && pip install -r requirements.txt``` - dev-build dependencies
    -```pre-commit install``` - pre-commit hooks 
7. Periodically update your fork's main branch
> To keep development branch up to date with main, first make sure to have your main branch on your fork up-to-date with upstream via #4 then 
``` 
git checkout <branch_name> # switch to dev branch
git fetch origin           # update dev branch with main branch of fork
git merge origin/main
``` 

    

