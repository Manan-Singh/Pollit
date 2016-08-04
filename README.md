# Pollit
###A web app for creating and viewing polls

Pollit is a small scale web app I made to emulate the much larger Reddit. It is not completely intended to be an entirely complete website to the extent of reddit as I did not use production quality resources for this project. This was more of a demo to see what I could do with node and express. In Pollit, users can create and vote on different Polls made from other users. It's pretty simple.

Functionality Implemented currently: 
  - User registration and validation
  - User account authentication
  - User account deletion and logout
  - Poll creation
  - Upvote/Downvote polls
  - View poll statistics
  - Comment on a poll
  - Vote for a specific choice on a poll
  - Sort between newest, oldest, and hottest(most upvoted) polls

Functionality still to Implement:
  - Make the entire website responsive (oh god, even bootstrap can't save me now)
  - Make password management system a little stronger
  - Add functionality to allow users to change their passwords, aka "Forgot Username?" and "Forgot Password?"
  - IDK what else, I accomplished most of what I wanted
 
 
**NOTE**: If you want to try out the site, that's fine. However, I am not, nor have I ever been a cyber security expert. The password system is a little (don't worry, they're safely stored and hashed with bcyrpt). As of right now, the passwords can be literally anything which means it's up to you, the user, to use whatever you want as a password. I personally would use a joke password since (a) I'm still working on this project so you can expect accounts to be deleted occasionally and (b) if someone were to hack this site, I wouldn't want you all to lose your passwords.

**NOTE**: I don't know if I will make the source code available on Github. Not only is there a lot of code, but it also contains account information and credentials to access the database. In the future, I may just upload all of the files anyway except for the app.js. 
 

Right now, the website is hosted on heroku and can be found here: https://cryptic-peak-19776.herokuapp.com

Since it's on Heroku and I'm only using the free dyno, I only get 55 minutes of server time a month currently :( 
