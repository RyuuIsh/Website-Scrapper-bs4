# Website-Scrapper-bs4
A Python script that scrapes the Empire Online's list of the 100 Greatest Movies and saves them to a text file. This project uses BeautifulSoup to extract movie titles from a web archive version of the article.

## Features
- Scrapes movie titles from a structured webpage.
- Stores the top 100 movies in a .txt file.
- Uses BeautifulSoup for HTML parsing.

## Tech-Stack
- Python – Core programming language
- Requests – Fetching webpage content
- BeautifulSoup – Web scraping

## Working
1. Fetch Webpage Data – Uses requests to retrieve the webpage HTML.
2. Extract Movie Titles – Parses the HTML using BeautifulSoup.
3. Reverse the Order – Saves the list in the correct ranking order.
4. Write to a File – Stores the movie names in movies.txt.

## Future-Enhancements
- Convert results into a JSON or CSV file.
- Automate scraping for updated lists.
- Integrate with a movie database API for additional details.

🎥 Get your next movie recommendation from this curated list! 
