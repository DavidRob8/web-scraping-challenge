Dependencies for Part 1:
from splinter import Browser
from bs4 import BeautifulSoup as soup

Dependencies for Part 2:
from splinter import Browser
from bs4 import BeautifulSoup as soup
import matplotlib.pyplot as plt
import pandas as pd

Part one was about scraping titles and preview texts from a Mars News website. I used Splinter to access the website and I used BeautifulSoup to scrape the information I needed.
Part two was much more complex. I used Splinter to access the website. and I used Beautiful Soup and comprehensive lists to create a Pandas DataFrame. I cleaned the data for analysis to answer the following questions:

1) How many months exist on Mars?
2) How many Martian (and not Earth) days worth of data exist in the scraped dataset?
3) What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
  - Find the average the minimum daily temperature for all of the months.
  - Plot the results as a bar chart.
4) Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
  - Find the average the daily atmospheric pressure of all the months.
  - Plot the results as a bar chart.
5) About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
  - Consider how many days elapse on Earth in the time that Mars circles the Sun once.
  - Visually estimate the result by plotting the daily minimum temperature.

I then saved the Pandas DataFrame as a CSV file in my repo.

Code Source:

I received assistance from a Tutor in Part 2 of the module, specifically when it came to comprehensive lists. 
