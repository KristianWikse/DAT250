# Laboratory report

### Technical Problems

__Installation__
* Forgot to add PATH variable for maven bin folder. Windows powershell could therfore not find the mvn commands. This problem was quickly fixed. 


__Testing and compiling__
* Mvn clean install could not delete my .jar extension file which meant that the original getting started project would not get modified. This was fixed by just closing and opening the windows cli session.
* Creating a heroku project in the wrong firectory also resulted in an error.  

### Validation
The steps taken to ensure that the heroku app enviroment was working.

__Running on the Web__
* Preparing the app
* Deploying the app on heroku
* Scaling the app by modifing number of dynos the app run on
* Modifining app dependencies and addons
* Using the heroku database 

__Running Locally__
* Run the app locally
* Pushing local changes to modify app
* Changing the .env file and adding it to gitignore to avoid security issues
* Starting a one-off dyno
 
### Pending issues

None, error logs can be found in file error.txt.
 