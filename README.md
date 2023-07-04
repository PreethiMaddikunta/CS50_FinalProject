# CS50 final project:Note-taking Flask Web Application with User Authentication

It's a python web application, where the user can add notes, delete the notes.

## ***Description***

Note-taking is a web application that allows users to securely create, manage, and delete their notes. The web app will provide user authentication functionality to ensure that each user's data remains private and accessible only to them. The key features of the application include:

User Registration and Authentication:

Users can create new accounts by registering with their email and password.
The application will securely store user credentials and manage authentication processes.
User authentication will be implemented to protect user data and ensure secure access to the note-taking features.

Note Creation and Management:

Authenticated users can create new notes by providing a title and content for each note.
Notes will be stored in a database and associated with the respective user account.
Users will have the ability to view, edit, and delete their own notes.

User Interface and Experience:

The web app will feature a clean and intuitive user interface, allowing users to easily navigate and interact with their notes.


- Demo video: [YouTube](https://www.youtube.com/).

## Setup & Installation

Make sure you have the latest version of Python installed.

```bash
git clone <repo-url>
```

```bash
pip install -r requirements.txt
```

## Running The App

```bash
python main.py
```

## Viewing The App

Go to `http://127.0.0.1:5000`

### ***Requirements***

- python
- flask
- Flask-SQLAlchemy
- flask-login

## ***Step-by-step implementation guide***

1. Download an application IDE like [VS Code](https://code.visualstudio.com/Download).

2. Install the [Python extension](https://marketplace.visualstudio.com/items?itemName=ms-python.python).

3. Right-click on the source code folder and select Open by IDE (VS Code).

4. Open a new terminal and copy one of the following codes and run it in the terminal.

```
# Linux
sudo apt-get install python3-venv    # If needed
python3 -m venv env

# macOS
python3 -m venv env

# Windows
python -m venv env
```

5. Hold (Ctrl + Shift + P) at the same time and select Python: Select Interpreter.

6. Click on Python 'env'.

7. Hold (Ctrl+Shift+`) to Open a new terminal again.

8. Run down codes on terminal.

```
python -m pip install -r requirements.txt
python -m pip install --upgrade pip
```

9. At the end type down code on terminal.

```
python -m flask run
```
- Full description [link](https://code.visualstudio.com/docs/python/tutorial-flask) of Python web application implementation guide.

## Info:

This project is final project of [Computer Science 50 course of Harvard](https://cs50.harvard.edu/).
