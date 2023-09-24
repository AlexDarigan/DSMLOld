# Data Science Portfolio

## About Me

__Name__: David Darigan

__Email__: C00263218@setu.ie

__LinkedIn__: https://www.linkedin.com/in/daviddarigan/

### Experience

__DELL Technologies Undergraduate Internship March 2023 - August 2023__
- Resolved several thousand vulnerabilities
- Deployed a PowerShell script to reduce workload by 2 days a year
- Improved CI / CD KPI by 14%

__Google Developers Student Club Core Team Member 2021 - 2022__

__Google Developers Student Club Team Lead 2022 - Present__

### Education

* BSc Honors Undergraduate in Software Development in South East Technological University
* First Class Honors from Level 7 Exams

### Technologies

Kotlin, Java, Python, Spring, Maven, Git, Docker, PowerShell, C#, HTTP, C, C++, SQL, SQLite

## Project - Magic The Gathering Card Data Science APIs

A set of standalone RESTful APIs that measure data about Magic: The Gathering taken from the [Scryfall API](https://scryfall.com/docs/api) with an 		additional web frontend that call into them.

__API Host__: http://api.insertnamehere

### Project - Measure of Central Tendency of Magic The Gathering Cards

Given a collection of a Magic: The Gathering card attribute type, return the mean, median, and mode of the values that occurred for that attribute

*API Route*: /measures 

| Resource 	| Description								|
|---------------|-----------------------------------------------------------------------|
| names    	| The mean, median and mode of card names				|
| colors   	| The mean, median and mode of card colors				|
| types    	| The mean, median, and mode of card types (land, creature etc)		|
| creatures	| The mean, median, and mode of creature classes			|
| artists	| The mean, median, and mode of artists					|

__Usage Example__

```http
GET /measures/colors
```

returns

```json
{
    "mean": "red"
    "mode": "black"
    "median": "green"
}
```
_values subject to change_

You can also request a specific value by appending the measure to the path

```http
GET /measures/types/mode
```

returns

```
"land"
```

Technologies: HTTP, JSON, ?

Libraries: ?

Data Source: [Scryfall API](https://api.scryfall.com)

_____________

### Project - Price Trends

	# Project - Card Price Trends

Get the price trend of a specific card day-by-day

*API Route*: /trends

| Resource | Description                     |
|----------|---------------------------------|
| cards    | A paginated collection of cards |
| {id}     | A specific card via id          |

Usage

```http
GET /trends/cards
```

returns

```json
{
    page: 1,
    pages: 20,
    cards: {
        "1": "Black Lotus",
        "2": "Azure Mage",
        "3": "Archivist",
        "..": "..",
    }
}
```

```http
GET /trends/cards/1
```

returns

```json
{
    "name": "Black Lotus"
    "prices": [
        {
            "year": 1993,
            "month": 02,
            "day": 24,
            "price": 0.40,
        },
         {
            "year": 1993,
            "month": 02,
            "day": 25,
            "price": 1.00,
        },
         {
            "year": 1993,
            "month": 02,
            "day": 26,
            "price": 2.00,
        },
        ....
    ]
}
```

Technologies: HTTP, JSON, ?

Libraries: ?

Data Source: [Scryfall API](https://api.scryfall.com)


### Project - Price Predictions

	Title: Price Predictions
 	Description: TBD
  	API Endpoint: /
   	REST Resources
    		REST Methods
      	Technologies
       	Libraries
	Data Sources

### Project - Image Classification

	Title: Image Classification
 	Description: TBD
  	API Endpoint: /
   	REST Resources
    		REST Methods
      	Technologies
       	Libraries
	Data Sources

### Project - GUI Frontend

	Title: WEB GUI Frontend
 	Description: TBD
  	API Endpoint: /
   	REST Resources
    		REST Methods
      	Technologies
       	Libraries
	Data Sources

