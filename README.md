# Simple Chat using Django Channels

This project was created following Django Channels official (documentation)[https://channels.readthedocs.io/en/latest/tutorial/index.html].

## Steps to run this project:
- Create a virtualenv: `mkvirtualenv simple-chat`
- Active created virtualenv: `workon simple-chat`
- Install project requirements: `pip install -r requirements.txt`
- Run Django project: `./manage.py runserver`

## Steps to test Channels:
- Open a browser tab to the room page at `http://127.0.0.1:8000/chat/lobby/`
- Open a second browser tab to the same room page
- In the second browser tab, type the message "Hello" and press enter. You should now see “hello” echoed in the chat log in both the second browser tab and in the first browser tab