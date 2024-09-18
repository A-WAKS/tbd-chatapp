To run our chatapp
you need to follow these steps one by one

we recommend you to use pycharm
make sure you have python installed on your system
make sure you have node.js installed on your system
these all can be gotten online

open the terminal
type these five commands in order

make sure you're not using a VPN

if there is no .venv file make one using this command
python -m venv .venv


there should be .venv file so just run these command
.\.venv\Scripts\activate
Pip install -r requirements.txt
python manage.py makemigrations 
python manage.py migrate
python manage.py runserver

after the last command runs successfully

click the generated web address and it'll load 

once there, register an account and enjoy 
P.s make sure to use a profile photo when creating to ensure smooth running

delete db.sqlite3 if you want to remove all previous users and chats

if you want to run tests between two different accounts we recommend you to use two different browser applications e.g Chrome and Microsoft edge