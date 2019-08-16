# A simple API with FLASK - part I (for begginers)

This API uses Python 3.7 ...<br>
The purpose of this API is just to demonstrate the most "basic" level possible of an API using FLASK.<br>
Obviously more advanced concepts are not being "addressed", such as "creating and altering tables<br>
in the database", but ... another example will be published using a more elaborate "architecture" like MVC.

LINK to part II:<br>
https://github.com/RicardoTurco/apiWithFlaskMVC

# ROADMAP:

1) Create and activate a VIRTUALENV<br>
(Verify the appropriate form for your S.O.)

2) Install packages and dependencies:<br>
(pip install -r requirements.txt)

3) Generate SQLite database:<br>

a) Enter into python interactive SHELL:<br>
(python)

b) Import db object and generate SQLite database:<br>

'>>>' from crud import db<br>
'>>>' db.create_all()<br>
'>>>' exit()<br>

After that, just run your application.<br>
(python crud.py)


# Available Endpoints:

Add New User:<br>
(POST: localhost:5000/user)

https://github.com/RicardoTurco/apiWithFlaskBASIC/blob/master/images/000_addNewUser.jpg <br>
(The image shows the JSON template to be sent.)


Get All Users:<br>
(GET: localhost:5000/user)

https://github.com/RicardoTurco/apiWithFlaskBASIC/blob/master/images/001_getAllUsers.jpg


Get Users bu ID:<br>
(GET: localhost:5000/user/1)

https://github.com/RicardoTurco/apiWithFlaskBASIC/blob/master/images/002_getUserByID.jpg


Update User:<br>
(PUT: localhost:5000/user/1)

https://github.com/RicardoTurco/apiWithFlaskBASIC/blob/master/images/003_updateUser.jpg <br>
(The image shows the JSON template to be sent.)

Delete User:<br>
(DELETE: localhost:5000/user/1)

https://github.com/RicardoTurco/apiWithFlaskBASIC/blob/master/images/004_deleteUser.jpg
