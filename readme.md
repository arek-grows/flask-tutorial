
# Flask App

Follow [flask tutorial to start](https://github.com/pallets/flask/tree/main/examples/tutorial)


Create a virtualenv and activate it (Mac):

```console
$ python3 -m venv venv
$ . venv/bin/activate
```

Or on Windows cmd:

```console
$ py -3 -m venv venv
$ venv\Scripts\activate.bat
```

Install Flaskr:

```console
$ pip install -e .
```

Or if you are using the main branch, install Flask from source before installing Flaskr:

```console
$ pip install -e ../..
$ pip install -e .
```

If not working, try to install misisng things: 

```console
$ pip install Flask
$ pip install Flask-Scss
```

## Development

```console
$ bash flask-start.sh
```

Visit http://127.0.0.1:5000/auth/register
