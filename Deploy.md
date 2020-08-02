//create requirement document .
pip freeze > requirement.txt



//create a Procfile file with no extension
Procfile:
//edit Procfile to contain
web: gunicorn script1:app



//gunicorn ->is what heroku needs for setup environment
//script1 ->is the name for the file you want to run.
//app ->is the variable that is hold the Flask instance. (app = Flask(__name__))




//create a runtime.txt
If you want heroku to run your application with needed runtime

