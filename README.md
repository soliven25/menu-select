# heroku connection practice

This github proect is connected to the pesonal heroku node project.
In this repositoy, you can learn how to add add-on in node & express project in heroku.

## Running Locally

Make sure you have [Node.js](http://nodejs.org/) and the [Heroku Toolbelt](https://toolbelt.heroku.com/) installed.

```sh
$ git clone https://github.com/soliven25/menu-select.git
$ cd menu-select
$ npm install
$ npm start
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## add-on (ex: mongodb)

```
$ cd menu-select
$ npm install mogodb --save
$ git add .
$ git commit -m "add mongodb add-on"
$ git push
```
These commands update local node-modules & pakage.json. and it's automatically deployed in heroku by pushing git.

## heroku deploy

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## Documentation

For more information about using Node.js on Heroku, see these Dev Center articles:

- [Getting Started with Node.js on Heroku](https://devcenter.heroku.com/articles/getting-started-with-nodejs)
- [Heroku Node.js Support](https://devcenter.heroku.com/articles/nodejs-support)
- [Node.js on Heroku](https://devcenter.heroku.com/categories/nodejs)
- [Best Practices for Node.js Development](https://devcenter.heroku.com/articles/node-best-practices)
- [Using WebSockets on Heroku with Node.js](https://devcenter.heroku.com/articles/node-websockets)
