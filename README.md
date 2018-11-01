# Educational Software for Cyber Security
# ISOE532C Project

Download the files of this Repository and extract the shells.zip
## Initial Configurations
The Project's backend is Python.
We have used Python's frameworks (Django and Flash) .

### Installing Python 2.7
``` sudo apt-get install python
        
```

Virtual Envirement wraps all the dependencies and doesn't mess the main python framework versions.
#### Virtual Env
```
sudo apt-get install python-virtualenv
mkdir project
cd project
virtualenv venv
source venv/bin/activate
```
Move the downloaded files to the project folder.
```
sudo apt-get install python-pip
```
This installs Python-PIP
Now Install Django requirements.
```
pip install -r requirments.txt

```
Install Flask
```
cd CTFd
pip install -r requirements.txt
sudo apt-get install nodejs
```
Now all the requirements have been installed.

You can run the base website servers  (  on port 8000)
```
(in the root directory: cybersecurity ) 

python manage.py runserver
```
To run the CTF (Capture the Flag) (Quizzes-like) Module..
```
python CTFd/serve.py
```
Since we are giving the BASH Shell : It could be given by runnning on port 3000
```
node websehell-server app.js -p 3000
```



