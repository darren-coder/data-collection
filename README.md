# data-collection

- This was an assignment using Splinter to open and navigate Chrome and Beautiful Soup to automatically scrape data from the web.

# Mars News

- Part 1 of the assignment was to design a notebook that automatically scraped and collected data from a website. All of the text elements from the titles and previews of the articles were scraped from the website using Beautiful Soup. After using list expressions to seperate just the text from the html syntax, the text from the titles and previews was looped through, added to a dictionary and finally appended to a list that was exported to a json file in the results folder.

# Mars Weather

- A table of Mars weather data was automatically scraped from the website using Splinter and Beautiful Soup. Then, the find() and find_all() functions were used to scrape the data needed for the names of the columns and the data contained in rows. Only the text was removed from all the data and it was combined into a list and then into a Pandas dataframe for viewing. Pandas functions were used to sort the data and Pandas.plot was used to make several plots that answered various questions given in the homework instructions.
- An analysis is given at the bottom of the 'part_2_mars_weather.ipynb' file and a csv file of the table was exported to the results folder. 

