
### Instructions

  

* Clone this project and create your own challenge branches.

* Create a public repository and push your commits using git flow.

* Share us the repository url and postman collection when you finish.

  

### Introduction

The soccer is the most popular sport in the world, around 265 million people plays soccer. There're some countries blessed of having the best players in the world.

We collect some data about the most important national level tournaments like UEFA, CONMEBOL, CONCACAF and the World Cup.

Your mission, if you decide to accept it... is get some statistical data about the tournaments and the teams.

#### Challenges



* Create a nestjs api and use mongodb as your database engine.
* Run tournaments seeder script located at db/seeders/tornaments.js
* Create the necessary endpoints to provide the following premises:
	* The championsest countries filtered by confederation.
	* The most runnerUp countries filtered by confederation.
	* Tournaments without headquarter.
	* Headquarters Champions.
	* All finals solved in penalties.
	* Total goals filtered by confederation.
	* Consecutively Championships filtered by confederation.
	* Runner up countries without championships.
	* All finals solved with more than one match.
	* World cup tournament in leap year.

  

### Recommendations

  

* Try to use the fewest deep loops.
* Try to make challenge as mush as you could.
* Try to use providers (services and repositories) and dependencies injection.
* All extra features will be considered.

  

### Nice to have

 * A little bit of unit testing.
* Docker containers.
* Heroku deployment.
* Remotely mongodb connection.

### Important data

* Finals solved with penalties contains P at the end of score.
* Finals solved with more than one match contains scores separated by comma: 2-1, 1-0, 0-0.
* Tournament without fixed headquarter were resolved with more than one match.
* Germany was divided in two by the Berlin Wall (East Germany and West Germany) from 1961 until 1989 but today Germany is unified and it has 4 world championships. Yes, Brazil 2014 is the first world cup winned by Germany with a completed clasification as unified country.

### References
 
* MongoDB https://mongodb.com/
* Heroku https://heroku.com/
