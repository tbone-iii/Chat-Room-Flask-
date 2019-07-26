# Project 2 (with Harvard's CS50web)

Web Programming with Python and JavaScript

This project follows the <a href="https://docs.cs50.net/web/2019/x/projects/2/project2.html">guidelines outlined</a> by the CS50 web course.

I employed HTML5, CSS, JavaScript (ES6), and of course the Pythonic Flask.

The chatroom incorporates sockets to process live broadcast information in realtime
and displays it in other users's browsers without needing to refresh.


<h1>Installation</h1>
To install this web app, download all of the files in this repository and set an the environment secret key to whatever you would like (or use the "generate_secret_key.py" file to generate one automatically).

Then, install the Python requirements outlined in the "requirements.txt" file and in a terminal, set the flask application as "application.py" and run the app as follows:
<pre>
<code>set FLASK_APP=application.py
flask run</code>
</pre>

<h1>Usage</h1>
The chatroom app should be fairly intuitive. Users can create a new username
that is remembered by the web browser. Any user can create a new channel and move to rooms
by clicking on the chatroom buttons. Only a maximum of 100 messages are saved for any chatroom.