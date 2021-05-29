# to-do-full-stack :page_facing_up:

##### `About:`
Full-Stack To Do web app.  The backend is built with Python on the Django framework, which stores data in an SQLite database and passes the data out through an API to the front end which is built with React.

---

##### `Requirements:`
* Python
* pipenv
* Node.js

---

##### `Run Locally:`
###### `Backend:`
* In a terminal window `cd` into the root directory (Pipfile.lock), create a virtual environment and install developer dependencies:
	`pipenv install --dev`
* Activate the virtual environment:
	`pipenv shell`
* `cd` into backend directory (manage.py) and start the Django development server:
	`python3 manage.py runserver`
* In a browser navigate to:
	`http://localhost:8000/`
###### `Frontend:`
* `cd` into the frontend directory and install developer dependencies:
	`npm install`
* Start the React development server:
	`npm start`
* In a browser navigate to:
	`http://localhost:3000/`
