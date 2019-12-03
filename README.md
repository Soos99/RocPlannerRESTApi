# RocPlannerRESTApi
Hosting RESTful API server for [RocPlanner Project](https://github.com/dle8/RocPlanner) using Heroku

## Setup
1. Create a [Heroku account](https://signup.heroku.com/)</br>
2. Install [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli) </br>
3. Clone this repository on your local machine
```
$ git clone https://github.com/Soos99/RocPlannerRESTApi.git
$ cd RocPlannerRESTApi
```
4. Login using Heroku CLI
```
$ heroku login -i
//Type in login credentials
```
5. Add your repository to the remote one
```
$ heroku git:remote -a {your-project-name}
```
6. Pushing it to Heroku
```
$ git push heroku master
```
### In the log that has been shown in the console you will find a link for your application at: </br>
https://{your-project-name}.herokuapp.com/
