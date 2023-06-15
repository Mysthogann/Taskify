# Taskify

A scalable To-do application built with Flask and React. The app is integrated with Google for authentication and for syncing with Google Calendar.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them:

* [Node.js](https://nodejs.org/en/)
* [Python](https://www.python.org/)
* [Pip](https://pip.pypa.io/en/stable/installing/)

### Installing

A step by step series of examples that tell you how to get a development env running.

1. Clone the repo: `git clone https://github.com/mysthogann/taskify.git`
2. Navigate into the `Taskify` directory: `cd taskify`
3. Install backend dependencies: 
    1. Navigate into the `backend` directory: `cd backend`
    2. Install virtualenv: `pip install virtualenv`
    3. Create a virtual environment: `virtualenv env`
    4. Activate the virtual environment: `source env/bin/activate` 
    5. Install Flask and other dependencies: `pip install -r requirements.txt`
4. Install frontend dependencies:
    1. Navigate into the `frontend` directory: `cd ../frontend`
    2. Install dependencies: `npm install`

### Running the App

1. To run the backend: 
    - Navigate into the `backend` directory and activate the virtual environment: `source env/bin/activate`
    - Start the Flask server: `flask run`
2. To run the frontend:
    - Navigate into the `frontend` directory: `npm start`

## Running the tests

Explain how to run the automated tests for this system.

## Built With

* [React](https://reactjs.org/) - The web framework used
* [Flask](http://flask.palletsprojects.com/) - Backend framework
* [Google Calendar API](https://developers.google.com/calendar) - Used to sync with user's calendar

## Authors

* **Alejandro Chavarria** - *Initial work* - [Mysthogann](https://github.com/mysthogann)
