# Flask-Web-App
Great tutorial at https://www.digitalocean.com/community/tutorials/how-to-make-a-web-application-using-flask-in-python-3<br/>
Dependencies:
- [Bootstrap](https://getbootstrap.com/docs/5.0/getting-started/introduction/)
- [jQuery](https://code.jquery.com)

### Setup
```
$ source bin/activate

(Flask-Web-App) $ pip3 install --upgrade pip

(Flask-Web-App) $ pip3 install flask
```

____

### Run from CLI
```
(Flask-Web-App) $ export FLASK_APP=app && export FLASK_ENV=development

(Flask-Web-App) $ python3 init_db.py

(Flask-Web-App) $ flask run --host=0.0.0.0
 * Serving Flask app "app" (lazy loading)
 * Environment: development
 * Debug mode: on
 * Running on http://0.0.0.0:5000/ (Press CTRL+C to quit)
 * Restarting with stat
 * Debugger is active!
 * Debugger PIN: ***
192.168.1.1 - - [13/Jan/2021 17:11:25] "GET / HTTP/1.1" 200 -
192.168.1.1 - - [13/Jan/2021 17:11:26] "GET /about HTTP/1.1" 200 -
192.168.1.1 - - [13/Jan/2021 17:11:27] "GET /create HTTP/1.1" 200 -
192.168.1.1 - - [13/Jan/2021 17:11:41] "POST /create HTTP/1.1" 302 -
```
