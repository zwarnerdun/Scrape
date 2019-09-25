# Scrape 
All the News That's Fit to Scrape is an application that lets users scrape news articles from fashionweekdaily.com. Users can then view and leave comments on saved articles. This app uses Cheerio to scrape news from fashion week daily and stores them in MongoDB using Mongoose. 

## Getting Started

1. Click on the button "Scrape newest articles" from fashion week daily in the upper left hand corner.
2. Click on the "All articles" in the same area as the scrape button to see what was scraped.
3. The articles will show below and it will show the title and summary of the article. 
4. Click on the article and it will take you directly to the article for further information.
5. The list of articles that show also have an option to add a note.
6. Click on the "saved articles" to see what you saved and edit your note if you feel the need to. 

## Prerequisites
Make sure to install express, express-handlebars, mongoose, cheerio, axios.

* How to install

1. Type "npm i" for all packages in your terminal
2. Run this command in your Terminal/Bash window: heroku addons:create mongolab

• This command will add the free mLab provision to your project.

## Demo
Try it here https://still-earth-18704.herokuapp.com/
![scrape](https://user-images.githubusercontent.com/49568886/65647968-67d85a80-dfce-11e9-9c58-226d0424c35e.PNG)

![scrape2](https://user-images.githubusercontent.com/49568886/65647971-69098780-dfce-11e9-90fb-28adfec1f417.PNG)

## Built With
* Javascript
* MongoDB
* Cheerio
* Logger
* Axios
* Method
* Express
* Handlebars
* Deployed on Heroku



