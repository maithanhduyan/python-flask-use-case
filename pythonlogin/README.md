### pythonlogin

[pythonlogin](https://morioh.com/p/c61187faa9be)

### Python environment
using python version 3
~~~~
  python -m pip install --user --upgrade pip
  python -m pip --version
  python -m venv venv
  .\venv\Scripts\activate
  pip install flask
  pip install flask-mysqldb
~~~~
Run app
~~~~
  set FLASK_APP=main.py
  set FLASK_DEBUG=1
  flask run
~~~~

#### File structure
~~~~
  \-- pythonlogin
  |-- main.py
  \-- static
    |-- style.css
  \-- templates
    |-- index.html
    |-- register.html
    |-- home.html
    |-- profile.html
    |-- layout.html
~~~~