# GitHub News App



### Author
 **[Stephen Ndele](https://github.com/stephenndele)**

## Description

A web application made using Python's Flask that uses the News API to allow a user to keep up with the World News by providing them with daily highlights straight from their preferred sources.

**[Live-Link to site.](https://hapakule-latest-news.herokuapp.com/)**
## Features
* A landing page with a list of some of the most popular news publishers that exists in the world right now.
* A display of articles from a selected news publisher.
* A navigation bar with a link to navigate back to the landing page.

## Behaviour Driven Development (BDD)
|Behaviour 	           |    Input 	                 |       Output          |
|----------------------------------------------|:-----------------------------------:|-----------------------------:|       
|    Page loads, landing page with a list of the various, news sources.    |    The user , once in the landing page, can click on a news source to get articles from that specific news publisher.    |    The day's articles from that news publisher as well as an option to read the full article from the publisher's website, are displayed.    |                       |


## Setup/Installation Requirements
Here is a run through of how to set up the application:
* Step 1 : Clone this repository using the git clone link:
  * **`git clone  https://github.com/stephenndele/news.git`**
* Step 2 : Open the directory created with your favorite IDE. If Atom type **`atom .`** if VSCode type **`code .`** . This will lauch the editor with the project setup,
* Step 3 : Navigate to the directory:
  * **`cd news`**
Then install all the requirements through pip: `$ pip install -r requirements.txt`

Make the file executable: `$ chmod +x start.sh`

Run the application: `$ ./start.sh`

Now navigate to your browser at: localhost:5000



* Now feel free to hack around the project.

## Known Bugs
* None currently.


## Technologies Used

- Python 3.6.8
- HTML
- CSS
- Bootstrap 4.3.1


### License
*MIT License* [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](license/MIT)

Copyright (c) 2021 **Stephen Ndele**