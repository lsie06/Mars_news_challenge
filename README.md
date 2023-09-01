# Mars_news_challenge

The purpose of this challenge is to scrape titles and preview text from Mars news articles on mars_part_1 and on mars_part_2 scrape and analyze Mars weather data, which exists in a table.

On part one automated browsing was used to visit the website, while there the page was inspected to identify the elements to scrape. A beautiful soup object was created which allows to extract the desired text from the website. The following were extracted: title and content. The text was stored in a dictionary created and finally printed on a list. 

On part two automated browsing was used to visit the website that contains the temperature data, this page was inspected, like in the first part a beautiful soup object was created to help extract the data. The extracted data was reorganized using a Pandas Data Frame with the same headings and information as the webpage. The following was analized: 
- How many months exist on Mars?
- How many Martian (and not Earth) days worth of data exist in the scraped dataset?
- What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
- Find the average minimum daily temperature for all of the months.
- Plot the results as a bar chart.
- Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
- Find the average daily atmospheric pressure of all the months.
- Plot the results as a bar chart.
- About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
- Consider how many days elapse on Earth in the time that Mars circles the Sun once.
- Visually estimate the result by plotting the daily minimum temperature.
- Export the DataFrame to a CSV file.

