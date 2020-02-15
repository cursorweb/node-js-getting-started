# Node js getting-started

A barebones Node.js app using [Express 4](http://expressjs.com/).  
  Removed EJS (I don't think it's quite necessary)


## Running Locally

Make sure you have [Node.js](http://nodejs.org/) and the [Heroku CLI](https://cli.heroku.com/) installed.

```bash
git clone https://github.com/cursorweb/node-js-getting-started.git
cd node-js-getting-started
npm install
npm start
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Heroku

```
heroku create
git push heroku master
heroku open
```

## Dynos

```
heroku ps:scale web=1
```

## Making Changes
**Heroku**
```
git push heroku master
```
**After cloning, make a repostiory and link it from there**
```
git remote set-url origin [url]
```
**Usual stuff**
```bash
git add . # or your files
git commit -m "[desc]"
git push origin master
```
