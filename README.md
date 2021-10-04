# Deploy Heroku

Go to [Heroku](https://heroku.com) and Login

Create New App ( App Name For Example : tes-api)

<img src="https://i.postimg.cc/Z5T8Btw2/newapp.png" width="300">

Install [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli)

Open `CMD` and Login Heroku

```cmd

> heroku login

```

Initialize a git repository in a new or existing directory

```cmd

> cd isonemydo

> git init

```

Remote Your App, Use `heroku git:remote -a app-name`

```cmd

> heroku git:remote -a tes-api

```

Commit your code to the repository and deploy it to Heroku using Git.

```cmd

> git add .

> git commit -am "make it better"

> git push heroku master

```

Log Success

<img src="https://i.postimg.cc/j5bzy0NP/deploy.png" width="300">
