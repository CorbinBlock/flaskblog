To run this project (if using Pycharm and Powershell in Windows Environment):

Download and install Git

--Open Git *insert username from PycharmProjects directory path*
cd /c/Users/*InsertUsername*/PycharmProjects/
git clone https://github.com/CorbinBlock/flaskblog.git

--Open Powershell - set environment variable to run flask_app
cd /c/Users/*InsertUsername*/PycharmProjects/flaskblog
$env:FLASK_APP = "flaskblog"
flask run

--Open Powershell/CMD and run the following one-by-one
pip install flask-sqlalchemy
pip install flask-bcrypt
pip install flask-login
pip install Pillow
pip install flask-WTF
cd C:\Users\*InsertUsername*\PycharmProjects\flaskblog\venv\scripts
python run.py

--Open Google Chrome
enter http://localhost:5000/home into address bar and press Enter
