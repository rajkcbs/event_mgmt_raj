Readme

This is an event management web app designed to locally manage personal obligations and plan availability for the end user. The web app consists of Python and HTML code. The Python code is the backend code managing the application, and the HTML is the front-end interface intended to visualize the user's calendar for a more intuitive way to communicate the general events being handled.

The Front end code will run on the localhost port of 8000. The site is given as: 

http://localhost:8000/api

The main project files will be named as: main.py

The Project requires python 3.10 or newer and requires the given python packages: 

1. fastapi
2. uvicorn

To run the application:

1. open a terminal session in the file location: ~.\eventhub-backend
2. run the command: uvicorn main:app --reload
3. verify no errors occur and read the terminal logs for what port on the local host the app is running on

To open the HTML interface:

1. Open the HTML file Event_Board.html  
2. Click "+ New Event"
3  Enter the relevant information to create an event in the event creation submenu
4. and the verify the event was registered correctly




