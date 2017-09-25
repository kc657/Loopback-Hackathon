## Inspiration
One of our favorites aspects about watching a new show with friends was not actually the show itself, but rather coming together after to argue about things we liked/didn't like, characters we enjoyed, or characters that turned us off. While it was interesting to see the conviction each person showed toward their opinion, it was more crazy to see just how different everyone's opinions actually were.  These differences was the spark behind the creation of Juxtaposr

## What it does
Juxtaposr is  a platform that allows users to voice their opinion regarding their favorite characters and maps out the results in relation to other users. 

## How we built it
- We built 2 web scrapers to get a complete character list from The Walking Dead show
- We built a RESTful API with IBM Loopback and connect to our character list stored on a MySQL database
- We built web interface for user to input their preference of every character of a show
- We built a smart backend to save users' preferences and show them to other users

## Challenges we ran into
- Connecting loopback to remote database
- Translating values of coordinates onto the screen
- Finding a complete character list manually, we solved it by building a web scraper
- Building a Drag and Drop function in React, we switched to Vanilla JS to resolve it

## Accomplishments that we're proud of
- Connecting Loopback to MySQL
- Our web app is engaging and simple for users (Drag and Drop)

## What's next for Juxtaposr
- Visualize the data collected through additional solutions that benefits other parties such as show producers
- Apply this concept of data collection to different industries, such as menus at a restaurant which would further simply the review process

## Tech
- Cheerio for web scraping
- Loopback for RESTful API
- Proto.io for prototyping
- Now by zeit for microservice
- Amazon ec2 for hosting

## Links
- [loopback](http://54.219.178.230/explorer/)
- [project resource](https://github.com/stupoid/tacos4dinner)
- [walking dead web scrapper](https://github.com/amazingandyyy/walking-dead-scrapper)
