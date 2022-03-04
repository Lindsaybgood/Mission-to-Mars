## Project Overview
This project consisted on a Python script to scrape text and images from various websites that talked about Mission to Mars. Then, I created a Flask web application with a rendered HTML template designed using Bootstrap to display all the data in a central location without having to gather it manually. The data scraped and displayed was stored in a non-relational Mongo database. Additionally, I was able to connect the scraping script so that each time a button was clicked, the scraping occured once again, the database got updated, and new data was displayed. This button only works under the condition that these webpages don't change their HTML components I used for scraping. And lastly, by using Bootstrap's grid system I was able to create a responsive web app that could accomodate to any device people view it from.

## Resources
- Data Sources: [Mars News](https://mars.nasa.gov/news/), [Mars Featured Images](https://spaceimages-mars.com/), [Mars Facts](http://space-facts.com/mars/), [Mars Hemispheres](https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars)
- Software: Python 3.7.7, Anaconda Navigator 1.9.12, Conda 4.8.4, Jupyter Notebook 6.0.3, MongoDB 4.4.0, Splinter 0.14.0, BeautifulSoup4 4.9.1, Flask 1.1.2, BootStrap 3.3.7

## Screenshot

![Mission to Mars data](https://user-images.githubusercontent.com/96216509/156841426-eaa95524-795f-4314-9f03-b8b298587797.png)


