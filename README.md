<div align="center">
 
# Source Codes - TOBI REST APIs
<p align="center">
<a href="#"><img title="TOBI APIs" src="https://img.shields.io/badge/TOBI APIs-blue?colorA=%23ff0000&colorB=%23017e40&style=for-the-badge"></a>
</p>
<p align="center">
<a href="https://github.com/ekadanuarta"><img title="Author" src="https://img.shields.io/badge/Author-DANU GANS-orange.svg?style=for-the-badge&logo=github"></a>
</p>

<p align='center'>
   <a href="https://wa.me/380944292908?text=assalamualaikum"><img height="30" src="https://c.top4top.io/p_1837yybbf0.jpeg"></a>&nbsp;&nbsp;
   <a href="https://instagram.com/ekagans_02"><img height="30" src="https://raw.githubusercontent.com/TobyG74/TobyG74/main/instagram.jpg"></a>
</P>


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
