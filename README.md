# Magic: The Gathering Statistics API

A [REST](https://en.wikipedia.org/wiki/REST)ful API to serve Magic: The Gathering cards statistics. 

[Magic: The Gathering (M:TG) is a trading card game created in 1993 by Richard  Garfield](https://www.mopop.org/resources/archive/landing-pages/science-fiction-and-fantasy-hall-of-fame/sffhof-members/magic-the-gathering/). There are over [25,000 cards that exist for M:TG as of 2023](https://mtg.fandom.com/wiki/Magic:_The_Gathering) A number of these cards are noteworthy for being exceptionally expensive, such as a copy of [“Black Lotus” selling for $540,000](https://www.ign.com/articles/magic-the-gatherings-most-sought-after-card-sells-for-record-540000
). While Black Lotus is an exceptional case, many M:TG cards fluctuate in price as the context of the game changes. This project is intended to serve statistical data regarding M:TG card attributes and prices.

## About Me

[About Me](https://github.com/AlexDarigan/DataScience-MachineLearning/wiki/About-Me)

## Project Design Layout

*You can find more detail on the [Github Wiki](https://github.com/AlexDarigan/DataScience-MachineLearning/wiki) for this Project*

The primary navigation area of the project will be on the API Hostname as of the projects 
version at that time.

| Host         | Version |
|--------------|---------|
| api.hostname | 1       |


This project will be a set of projects that exist as a single RESTful API. Each project shares the same general following structure

| Attribute        | Description                                                   |
|------------------|---------------------------------------------------------------|
| Title            | The project title                                             |
| Description      | A brief description of the project                            |
| HTTP Route       | The HTTP Route of the project                                 |
| Resources        | A tabled list of HTTP Resources                               |
| Query Parameters | A optional tabled set of HTTP query parameters                |
| Technologies     | The technologies used in the project (e.g python)             |
| Libraries        | The libraries used in the project (e.g pandas)                |
| Data Sources     | The data sources used for that project (e.g scryfall[4])      |
| Data Storage     | How and where our transformed data is stored (e.g CSV, Cloud) |

## Projects


| Project              												| HTTP Route | Description                                       |
|---------------------------------------------------------------------------------------------------------------|------------|---------------------------------------------------|
| [Statistics](https://github.com/AlexDarigan/DataScience-MachineLearning/wiki/Statistics)           		| /stats     | Get statistics about different card attributes    |
| [Price Trends](https://github.com/AlexDarigan/DataScience-MachineLearning/wiki/Trends)         		| /trends    | Get the price trend of a specific card            |
| [Price Predictions](https://github.com/AlexDarigan/DataScience-MachineLearning/wiki/Predictions)    		| /predict   | Predict the future price trend of a specific card |
| [Image Classification](https://github.com/AlexDarigan/DataScience-MachineLearning/wiki/Image-Classifiers) 	| /classify  | Extract text from an encoded card image           |

