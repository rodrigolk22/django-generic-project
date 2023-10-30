<h1>Simple Django VS Code Project</h1> 

<p align="center">
  <img src="https://img.shields.io/badge/VS%20CODE-IDE-green?style=flat&logo=visual-studio-code" alt="VS CODE" />
  <img src="https://img.shields.io/badge/Python-v3.10-green?style=flat&logo=Python" alt="Python" />
  <img src="https://img.shields.io/badge/Django-v4.2.6-green?style=flat" alt="Django" />
  <img src="https://img.shields.io/badge/Status-Under%20developement-orange?style=flat" alt="Status" />
  <img src="https://img.shields.io/badge/LICENSE-MIT-green?style=flat" alt="LICENSE" />
</p>

> Under develepoment: :warning:

### Topics 

:small_blue_diamond: [Description](#project-description)

:small_blue_diamond: [Functions](#functions)

:small_blue_diamond: [Requirements](#requirements)

:small_blue_diamond: [How to run](#how-to-run-arrow_forward)


## Project Description 

<p align="justify">
  A simple Django project using VS Code IDE. 
</p>

## Functions

:heavy_check_mark: Run a Django application

## Requirements

:warning: [Visual Studio Code](https://code.visualstudio.com/download)


## How to run :arrow_forward:

In the terminal, clone the project:

> https://github.com/rodrigolk22/django-generic-project

Steps:

:white_check_mark: Search for Python Extension [Python extension](https://marketplace.visualstudio.com/items?itemName=ms-python.python) in IDE Extensions (ctrl + shift + X) and install.

:white_check_mark: create a virtual environment: for windows user run these commands:

> py -3 -m venv .venv
> .venv\scripts\activate

If you get UnauthorizedAccess error, you will need to run this command before start environment:

> Set-ExecutionPolicy -ExecutionPolicy Unrestricted -Scope CurrentUser

Update pip in the virtual environment by running the following command in the VS Code Terminal:

> python -m pip install --upgrade pip

Install Django in the virtual environment by running the following command in the VS Code Terminal:

> python -m pip install django

In the VS Code Terminal where your virtual environment is activated, run the following command:

> django-admin startproject web_project .

Create an empty development database by running the following command:

> python manage.py migrate

To verify the Django project run:

> python manage.py runserver

Ctrl+click the http://127.0.0.1:8000/ URL in the terminal output window to open your default browser to that address

stop the server in VS Code using Ctrl+C


## How to run tests

> :warning: pending tests


## Languages, dependencies and libs used :books:

- [Python](https://www.python.org/)
- [Python extension](https://marketplace.visualstudio.com/items?itemName=ms-python.python)


## Issues :exclamation:

If you get UnauthorizedAccess error, you will need to run this command before start environment:

> Set-ExecutionPolicy -ExecutionPolicy Unrestricted -Scope CurrentUser



## To Dos

:memo: Create test tasks 



## Developer :octocat:

| [<img src="https://avatars.githubusercontent.com/u/26410295?v=4" width=115><br><sub>Rodrigo Luiz Kovalski</sub>](https://github.com/rodrigolk22) |
| :---: |


## License 

The [MIT License]() (MIT)

Copyright :copyright: 2023 - Simple Django VS Code Project