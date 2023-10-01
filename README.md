<div align="center">
<h1 align="center">
<img src="https://github.com/TiagoIesbick/little-lemon-capstone/blob/main/src/assets/images/logo.png" width="200" />
<br>API_LittleLemon
</h1>
<h3>◦ Developed with the software and tools below.</h3>

<p align="center">
<img src="https://img.shields.io/badge/Jinja-B41717.svg?style&logo=Jinja&logoColor=white" alt="Jinja" />
<img src="https://img.shields.io/badge/Python-3776AB.svg?style&logo=Python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/Django-092E20.svg?style&logo=Django&logoColor=white" alt="Django" />
</p>
<img src="https://img.shields.io/github/languages/top/TiagoIesbick/API_LittleLemon?style&color=5D6D7E" alt="GitHub top language" />
<img src="https://img.shields.io/github/languages/code-size/TiagoIesbick/API_LittleLemon?style&color=5D6D7E" alt="GitHub code size in bytes" />
<img src="https://img.shields.io/github/commit-activity/m/TiagoIesbick/API_LittleLemon?style&color=5D6D7E" alt="GitHub commit activity" />
</div>

---

## 📖 Table of Contents
- [📖 Table of Contents](#-table-of-contents)
- [📍 Overview](#-overview)
- [📦 Features](#-features)
- [📂 Repository Structure](#-repository-structure)
- [⚙️ Modules](#modules)
- [🚀 Getting Started](#-getting-started)
    - [🔧 Installation](#-installation)
    - [🤖 Running API_LittleLemon](#-running-API_LittleLemon)
    - [🧪 Tests](#-tests)
- [🛣 Roadmap](#-roadmap)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [👏 Acknowledgments](#-acknowledgments)

---


## 📍 Overview

Fully functioning API project for the Little Lemon restaurant so that the client application developers can use the APIs to develop web and mobile applications. People with different roles will be able to browse, add and edit menu items, place orders, browse orders, assign delivery crew to orders and finally deliver the orders.

Filtering, pagination, sorting and throttling capabilities as well as authentication and authorization.

Develop  with 💜 by Tiago Iesbick

---

## 📦 Features

HTTPStatus Exception: 429

---


## 📂 Repository Structure

```sh
└── API_LittleLemon/
    ├── LittleLemon/
    │   ├── __init__.py
    │   ├── asgi.py
    │   ├── settings.py
    │   ├── urls.py
    │   └── wsgi.py
    ├── LittleLemonAPI/
    │   ├── __init__.py
    │   ├── admin.py
    │   ├── apps.py
    │   ├── migrations/
    │   │   ├── 0001_initial.py
    │   │   └── __init__.py
    │   ├── models.py
    │   ├── permissions.py
    │   ├── serializers.py
    │   ├── tests.py
    │   ├── urls.py
    │   └── views.py
    ├── Pipfile
    ├── Pipfile.lock
    ├── db.sqlite3
    ├── manage.py
    └── notes.txt
```


---

## ⚙️ Modules

<details closed><summary>Root</summary>

| File                                                                                   | Summary                                                                                                                                                                                                                                                                                                                                                                                                               |
| ---                                                                                    | ---                                                                                                                                                                                                                                                                                                                                                                                                                   |
| [Pipfile](https://github.com/TiagoIesbick/API_LittleLemon/blob/main/Pipfile)           | The code in the Pipfile file specifies the dependencies and required versions of the packages for a project. In this case, it lists Django, Django Rest Framework, Djoser, Django Rest Framework XML, Django Filter, and Bleach as the required packages. The code also specifies that these packages should be fetched from the PyPI package repository and that they should be compatible with Python version 3.11. |
| [notes.txt](https://github.com/TiagoIesbick/API_LittleLemon/blob/main/notes.txt)       | The code contains user credentials for a superuser, manager, delivery crew, and customers. Each user has a username, email, and password associated with their account.                                                                                                                                                                                                                                               |
| [Pipfile.lock](https://github.com/TiagoIesbick/API_LittleLemon/blob/main/Pipfile.lock) | Pipfile.lock replaces the requirements.txt file used in most Python projects and adds security benefits of tracking the packages hashes that were last locked. This file is managed automatically through locking actions.                                                                                                                                                                                                                                                                                                                                                                                             |
| [manage.py](https://github.com/TiagoIesbick/API_LittleLemon/blob/main/manage.py)       | A command-line utility that lets you interact with this Django project in various ways.                                                                                                                                                                                                                                                                                                                                                                                             |

</details>

<details closed><summary>Littlelemon</summary>

| File                                                                                             | Summary                                                                                                                                                                                                                                                                                         |
| ---                                                                                              | ---                                                                                                                                                                                                                                                                                             |
| [settings.py](https://github.com/TiagoIesbick/API_LittleLemon/blob/main/LittleLemon/settings.py) | The code defines the settings for a Django project called LittleLemon. It includes configuration for database, internationalization, static files, authentication, and pagination. Additionally, it installs and configures various Django applications and libraries for REST API development. |
| [urls.py](https://github.com/TiagoIesbick/API_LittleLemon/blob/main/LittleLemon/urls.py)         | Main URL dipatcher.                                                                                                                                                                                                                                                                       |
| [wsgi.py](https://github.com/TiagoIesbick/API_LittleLemon/blob/main/LittleLemon/wsgi.py)         | The Web Server Gateway Interface (WSGI, pronounced whiskey or WIZ-ghee) is a simple calling convention for web servers to forward requests to web applications or frameworks written in the Python programming language.                                                                                                                                                                                                                                                                       |
| [asgi.py](https://github.com/TiagoIesbick/API_LittleLemon/blob/main/LittleLemon/asgi.py)         | ASGI (Asynchronous Server Gateway Interface) provides an interface between async Python web servers and applications while it supports all the features provided by WSGI.                                                                                                                                                                                                                                                                       |

</details>

<details closed><summary>Littlelemonapi</summary>

| File                                                                                                      | Summary                   |
| ---                                                                                                       | ---                       |
| [tests.py](https://github.com/TiagoIesbick/API_LittleLemon/blob/main/LittleLemonAPI/tests.py)             | Create your tests here    |
| [permissions.py](https://github.com/TiagoIesbick/API_LittleLemon/blob/main/LittleLemonAPI/permissions.py) | Permissions functions and classes |
| [urls.py](https://github.com/TiagoIesbick/API_LittleLemon/blob/main/LittleLemonAPI/urls.py)               | Secondary URL dispatcher |
| [views.py](https://github.com/TiagoIesbick/API_LittleLemon/blob/main/LittleLemonAPI/views.py)             | Python functions and classes that takes http requests and returns http response. |
| [models.py](https://github.com/TiagoIesbick/API_LittleLemon/blob/main/LittleLemonAPI/models.py)           | Tables and fields of our database. |
| [admin.py](https://github.com/TiagoIesbick/API_LittleLemon/blob/main/LittleLemonAPI/admin.py)             | The admin.py file is used to display our models in the Django admin panel. |
| [apps.py](https://github.com/TiagoIesbick/API_LittleLemon/blob/main/LittleLemonAPI/apps.py)               | The apps.py convention merely allows Django to load them automatically when INSTALLED_APPS contains the path to an application module rather than the path to a configuration class. |
| [serializers.py](https://github.com/TiagoIesbick/API_LittleLemon/blob/main/LittleLemonAPI/serializers.py) | Serializers in Django REST Framework are responsible for converting objects into data types understandable by javascript and front-end frameworks. Serializers also provide deserialization, allowing parsed data to be converted back into complex types, after first validating the incoming data. |

</details>

<details closed><summary>Migrations</summary>

| File                                                                                                                   | Summary                   |
| ---                                                                                                                    | ---                       |
| [0001_initial.py](https://github.com/TiagoIesbick/API_LittleLemon/blob/main/LittleLemonAPI/migrations/0001_initial.py) | HTTPStatus Exception: 429 |

</details>

---

## 🚀 Getting Started

***Dependencies***

Please ensure you have the following dependencies installed on your system:

`- ℹ️ Dependency 1`

`- ℹ️ Dependency 2`

`- ℹ️ ...`

### 🔧 Installation

1. Clone the API_LittleLemon repository:
```sh
git clone https://github.com/TiagoIesbick/API_LittleLemon
```

2. Change to the project directory:
```sh
cd API_LittleLemon
```

3. Install the dependencies:
```sh
pip install -r requirements.txt
```

### 🤖 Running API_LittleLemon

```sh
python main.py
```

### 🧪 Tests
```sh
pytest
```

---


## 🛣 Roadmap

> - [X] `ℹ️  Task 1: Implement X`
> - [ ] `ℹ️  Task 2: Implement Y`
> - [ ] `ℹ️ ...`


---

## 🤝 Contributing

Contributions are always welcome! Please follow these steps:
1. Fork the project repository. This creates a copy of the project on your account that you can modify without affecting the original project.
2. Clone the forked repository to your local machine using a Git client like Git or GitHub Desktop.
3. Create a new branch with a descriptive name (e.g., `new-feature-branch` or `bugfix-issue-123`).
```sh
git checkout -b new-feature-branch
```
4. Make changes to the project's codebase.
5. Commit your changes to your local branch with a clear commit message that explains the changes you've made.
```sh
git commit -m 'Implemented new feature.'
```
6. Push your changes to your forked repository on GitHub using the following command
```sh
git push origin new-feature-branch
```
7. Create a new pull request to the original project repository. In the pull request, describe the changes you've made and why they're necessary.
The project maintainers will review your changes and provide feedback or merge them into the main branch.

---
