# A simple API with FLASK

This API uses Python 3.7 ...<br>
The purpose of this API is just to demonstrate the most "basic" level possible of an API using FLASK.<br>
Another example will be published using a more elaborate "architecture" like MVC.

# ROADMAP:

1) Create and activate a VIRTUALENV<br>
(Verify the appropriate form for your S.O.)

2) Install packages and dependencies:<br>
(pip install -r requirements.txt)

3) Generate SQLite database:

a) Enter into python interactive SHELL:<br>
(python)

b) Import db object and generate SQLite database:<br>

'>>>' from crud import db<br>
'>>>' db.create_all()<br>
'>>>' exit()<br>

After that, just run your application.<br>
(python crud.py)


# Available Endpoints:

Add New User:
(POST: localhost:5000/user)

[a link] (https://github.com/RicardoTurco/apiWithFlaskBASIC/blob/master/images/000_addNewUser.jpg)


Get All Users:
(GET: localhost:5000/user)

[a link] (https://github.com/RicardoTurco/apiWithFlaskBASIC/blob/master/images/001_getAllUsers.jpg)


Get Users bu ID:
(GET: localhost:5000/user/1)

[a link] (https://github.com/RicardoTurco/apiWithFlaskBASIC/blob/master/images/002_getUserByID.jpg)


Update User:
(PUT: localhost:5000/user/1)

[a link] (https://github.com/RicardoTurco/apiWithFlaskBASIC/blob/master/images/003_updateUser.jpg)


Delete User:
(DELETE: localhost:5000/user/1)

[a link] (https://github.com/RicardoTurco/apiWithFlaskBASIC/blob/master/images/004_deleteUser.jpg)
