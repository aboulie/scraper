# Scraper
`Scraper` is a full stack application that allows users to browse and scrape news articles from the Minnesota News site, MPR.com. I did not create these articles for users, but by using Mongoose and Cheerio, users can save or unsave, add and delete comments for a specific article, and read other comments on Saved Articles. This application utilizes Cheerio to scrape the news from MPR and then store them in MongoDB using Mongoose.

Please click the following link to peruse and use the app!: https://young-temple-44428.herokuapp.com/

## Technologies Used

Front End Tech Used
  * HTML5
  * CSS
  * Bootstrap
  * Javascript
  * jQuery

Backend Tech Used
  * Node
  * Javascript
  * Express
  * Handlebars
  * MongoDB

NPM Packages Used
  * [express - Fast, unopinionated, minimalist web framework for node.](https://www.npmjs.com/package/express)
  * [express-handlebars - A Handlebars view engine for Express which doesn't suck.](https://www.npmjs.com/package/express-handlebars)
  * [mongoose - Mongoose is a MongoDB object modeling tool designed to work in an asynchronous environment.](https://www.npmjs.com/package/mongoose)
  * [body-parser - Node.js body parsing middleware](https://www.npmjs.com/package/body-parser)
  * [cheerio - Fast, flexible & lean implementation of core jQuery designed specifically for the server.](https://www.npmjs.com/package/cheerio)
  * [request - Request is designed to be the simplest way possible to make http calls. It supports HTTPS and follows redirects by default.](https://www.npmjs.com/package/request)


Deployed on: `Heroku`

## Usage

- Click on the "Scrape Articles" icon at the upper right hand Corner to Scrape News Articles from MPR News.

- Click on "Save Article" on the individual articles to store the article in MongoDB.

- Click on "Saved Articles" to bring up a List of Saved Articles.

- Click on Artical Notes to elicit a pop up modal which will allow you to see, add, and delete notes. 
- Click on the "Delete from Saved" Button to delete the article from your list.


## Requirements
- Web Browser
- Nodejs
- Mongo DB

## Installation

`Scraper` can be downloaded by cloning this repository:[`https://git.heroku.com/young-temple-44428.git`]


After installation, open node, navigate to the file and run `npm install`.

To run `Scraper` locally, please Ensure that MongoDB is running.

A link to the creator's github: https://github.com/aboulie

A link to the creator's portfolio:
https://aboulie.github.io/Bootstrap-Portfolio/

Please click the following link to peruse and use the app!: https://young-temple-44428.herokuapp.com/