# Natours

Udemy Course: Advanced CSS and Sass: Flexbox, Grid, Animations and More!

Requirement
------------------

* NodeJS 10.15.0

  - Install it from https://nodejs.org/en/

Getting Started
------------------
This guide outline the steps needed to start Natours in a development enviroment.

 * Fork the ngkangting/Natours repository on Github under your username. You’ll end up with something like your_user_name/Natours.

 * Clone your forked repository on your development machine.

```sh
 git clone git@github.com:ngkangting/Natours.git
```

* Add a git remote with the git url of the main repository

```sh
 git remote add upstream git@github.com:ngkangting/Natours.git
```

Install npm dependencies
------------------

* Install node-sass

```sh
npm install node-sass --save-dev
```

* Install dependencies

```sh
npm install
```

* Install concat

```sh
npm install concat --save-dev
```

* Install autoprefixer

```sh
npm install autoprefixer --save-dev
```

* Install postcss-cli

```sh
npm install postcss-cli --save-dev
```

* Install npm-run-all

```sh
npm install npm-run-all --save-dev
```

Development
------------------

* Start Natours Project in development environment

```sh
npm run start
```

Production
------------------

* Build Natours Project for production environment

```sh
npm run build:css
```

View Natours Project in development environment
------------------
To view Natours Project in development environment, go to http://localhost:8080