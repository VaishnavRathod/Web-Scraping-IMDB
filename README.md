# Web-Scraping-IMDB
This project aims to develop a Python program that can automatically scrapes the data from the IMDB top 250 rated movies website amd extracts essential information such as 
- Rank
- Title (Movie Name)
- Released (Year)
- Rating (Out of 10)
- Genre (Drama, Crime,...)
- Description
- And other details (Commented in the script).
  
The Extracted data is further store in the structured format like .csv file and can be used for further analysis and exploration.

The script also includes the *progress bar with time elasped* which will help to know how much data has been extracted into structured format. 

# What is IMDB?
IMDb (an acronym for Internet Movie Database)[2] is an online database of information related to films, television series, podcasts, home videos, video games, and streaming content online – including cast, production crew and personal biographies, plot summaries, trivia, ratings, and fan and critical reviews. IMDb began as a fan-operated movie database on the Usenet group "rec.arts.movies" in 1990, and moved to the Web in 1993. Since 1998, it has been owned and operated by IMDb.com, Inc., a subsidiary of Amazon.

![Alt text](https://upload.wikimedia.org/wikipedia/commons/thumb/6/69/IMDB_Logo_2016.svg/575px-IMDB_Logo_2016.svg.png)

# Project Objective:
- Design and implement a Python script using libraries like requests and BeautifulSoup to access and parse HTML content from the IMDB Top 250 Shows website. [LINK](https://m.imdb.com/chart/top/)
- Extracting specific data elements from HTML content including show title, rating, release year, genre and description of the movies.
- The data extracted is stored in the structured file format like .csv file ensuring proper formatting and organization of data.
- Test the scraper script to ensure it accurately extract data from the website and produces a valid csv file.

# Project Result:
The following project has the output of Top 250 Rated IMDB Movies list in the .CSV file format. It is available in the repository as top_250_shows.csv.  

