# Educational Software for Cyber Security
# ISOE532C Project
You can also find the project Hosted on http://www.cybersec-edu.ml:8000


Download the files of this Repository and extract the shells.zip. Contents of shells folder must be in the main directory.
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

you can now check the website (Preferably Chrome Browser)
at the url  "  http://localhost:8000 "
## Usage Manual
1. Signup by providing a password with length of minimum 8 characters.
2. Login
3. Add articles if logged in.
4. If Participating in CTF. Please register as a Team. and then Login.
5. If using shell (On clicking Shell),  use  (user ID : 'guest' , password : 'guest') .If it doesn't work use (user ID : 'foo' , password : 'bar') 

#### for Admin 
go to  http://localhost:8000/admin
        id:admin
        use password said to you. :)
       
###### Extra Info : 
we have used the Amazon Web Services for Hosting.

Thank You .
