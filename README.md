# Data Science Portfolio

## About Me

	Name: David Darigan
 	Email: C00263218@setu.ie
	LinkedIn: https://www.linkedin.com/in/daviddarigan/

__Experience__

__DELL Technologies Undergraduate Internship March 2023 - August 2023__
- Resolved several thousand vulnerabilities
- Deployed a PowerShell script to reduce workload by 2 days a year
- Improved CI / CD KPI by 14%

__Education__

* BSc Honors Undergraduate in Software Development in South East Technological University
* First Class Honors from Level 7 Exams

__Technologies__

Kotlin, Java, Python, Spring, Maven, Git, Docker, PowerShell, C#, HTTP, C, C++, SQL, SQLite

## Projects

	Title: Magic The Gathering Card Statistics
 	Description: TBD
  	Host Endpoint: TBD
   	Quickstart: TBD

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


### Project - Price Trends

	Title: Price Trends
 	Description: TBD
  	API Endpoint: /
   	REST Resources
    		REST Methods
      	Technologies
       	Libraries
	Data Sources

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

