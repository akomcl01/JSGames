JSGames was a part of my final project for my Internet Programming class which I collaborated on with Joshua Vanatter as well.

Basically, 


This site uses SQLAlchemy to store user information and game scores. 
There are six tables in all, with a one to many relationship. 
We used the python module bcrypt to hash passwords, and it also is used to verify passwords, 
while protecting against time-attacks. 

There is a file called createdb.py which will create the sqlite database (or whatever the source is specified as)
file from scratch when it's run. 

There is some commented out code that was being used for protection against malicious redirects, 
at the suggestion of flask-login, but it wasn't working properly. 

WTForms is used to validate the forms for register, login, change password, and delete account. 

There is a small api system that can get accessed by calling one of:

/api/flappypong

/api/gravitygolf

/api/pacman

/api/fifteen

/api/lander


These will return all the scores for all users of one of the games.

I believe it is currently not set up with CORS. It's on the to-do list. 

## The Games

My collaborator Josh took these games from open source sites like github, and the game 'Fifteen' was written by his roommate Ryne Hanson.
Josh edited the javascript games to make a couple of them harder, or easier, based entirely on my own opinions.

Clinton Akomea-Agyin,

Joshua Vannatter
