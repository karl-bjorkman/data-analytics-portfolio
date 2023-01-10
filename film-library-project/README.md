# Film Library Project

## Why I created this application

My favorite online platform for film content is called Letterboxd. The company is based in New Zealand and have provided what I believe to be the most polished social media site and film log for cinephiles. However, there are a couple of functions that I do not believe the site offers its users:

1. Personalized movie recommendations by year, selected from a custom list (created by the user)
2. An easy way to access the date when a user last saw a particular film (provided they logged this information on the platform)

This small application provides this very information, provided .CSV files for the user's custom lists (in this case, my personal film collection library) and the user's diary (a chronological list of films the user has watched and logged on the site).

## Walkthrough

1. Read-in datasets, examine their first five rows, and then wrangle the datasets for easy analysis/manipulation
2. Define a function that returns a randomized film recommendation that was released in a particular year, which is inputted by the user (e.g. the user inputs 1999 and the program returns 'The Matrix,' provided the user owns that title)
3. Define another function that returns the most recent date (and elapsed days) that the user saw a particular film
4. Finally, I wrote a prompt for the user that gives them the ability to select which of these two functions they wish to use (given an input of either 1 or 2)

## Tools used:

* Data wrangling
* Custom functions
* Date functions/calculations