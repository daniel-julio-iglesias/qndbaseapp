# qndbaseapp

===============================================

A kind of REAME.first file
... but in reality the content are my notes

===============================================


This is an example application featured in Miguel Grinberg's blog
 [Flask Mega-Tutorial](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world). 
 See the tutorial for instructions on how to work with it.


===============================================

This is the very basic base application
to use as template for your own 
functionality implementation.
It is wrapped into a Web Framework.

The application is web based using Flask.

===============================================

Install these packages after app sources download


(venv) $ pip install flask
(venv) $ pip install --proxy http://user:pass@proxyAddress:proxyPort flask

(venv) $ pip install flask-wtf
(venv) $ pip install flask-sqlalchemy
(venv) $ pip install flask-migrate
(venv) $ pip install flask-login


===============================================

Apply the next db steps after downloading your app sources


Linux
(venv) $ export FLASK_APP=qndbaseapp.py
MS
(venv) $ set FLASK_APP=qndbaseapp.py

(venv) $ flask db upgrade

===============================================

You can run the application
(after installing it
as intended with the below section notes)

Linux
(venv) $ export FLASK_APP=qndbaseapp.py
MS
(venv) $ set FLASK_APP=qndbaseapp.py

(venv) $ flask run

..register your user...
..test introducing file name "01.txt" ...

The below initial project notes are from my exercises based on
The Flask Mega-Tutorial
https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world

Enjoy it and please, let me know any comments to make it better/useful.
Thank you.


===============================================

TO DO: app sources download
$ git config --global http.proxy http://proxy.mycompany:80
$ git clone https://github.com/daniel-julio-iglesias/sectionsextractor
(...)




===============================================

TO DO: If migrations directory doesn't exists
apply the next db steps after downloading your app sources

Linux
(venv) $ export FLASK_APP=qndbaseapp.py
MS
(venv) $ set FLASK_APP=qndbaseapp.py

(venv) $ flask db init
(venv) $ flask db migrate -m "users table"
(venv) $ flask db upgrade

===============================================

Run the application

Linux
(venv) $ export FLASK_APP=qndbaseapp.py
MS
(venv) $ set FLASK_APP=qndbaseapp.py

(venv) $ flask run


URL: http://localhost:5000/
URL: http://localhost:5000/index

===============================================


TODO: Adapt to your functionality


===============================================




===============================================




===============================================

