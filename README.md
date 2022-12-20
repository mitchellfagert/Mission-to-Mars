# Mission-to-Mars
***HTML Web scraping on Mars data to create a Flask web application using Python and MongoDB***

## Overview
For this project I wrote a `Python` script that web scrapes text and images from various websites that discuss the planet Mars. The scraped data was then displayed in a central location through a `Flask` web application with a rendered `HTML` template designed using `Bootstrap`. The data was stored in a non-relational `Mongo database` and could be updated by clicking a button, provided the HTML components used for scraping on the relevant webpages remained unchanged. The web application was also designed to be responsive on any device using Bootstrap's grid system.

## Resources
* Web pages:
  * https://redplanetscience.com/
  * https://spaceimages-mars.com/
  * https://galaxyfacts-mars.com/
  * https://marshemispheres.com/
 
* Software:
  * Python
  * Jupyter Notebook
  * Pandas, BeautifulSoup, Splinter, ChromeDriverManager, Flask, PyMongo
  * MongoDB
  * HTML5
  * Bootstrap 3

<img width="314" alt="tools_for_scraping" src="https://user-images.githubusercontent.com/107579508/207735633-555267f1-9709-4b35-8aff-7aa2370c06ea.png">

## Summary

The end result of the project was a fully operational web application built with Flask, which featured images, a table comparing Mars to Earth, and the latest scraped article title and description from NASA's website. When the "Scrape New Data" button is clicked, the website and MongoDB are updated with new information.

![webpage_header](https://user-images.githubusercontent.com/107579508/208746095-6543ea51-ea5d-4676-8624-56236c754eb1.png)

![webpage_ss](https://user-images.githubusercontent.com/107579508/208746182-d7c8b9f3-642a-4935-a470-979fab921a6f.png)


