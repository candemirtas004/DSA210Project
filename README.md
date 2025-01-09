# DSA210Project

My goal in this project is to explore and anaylse my own League of Legends match data. 

How I Obtained My Dataset:

I obtained my dataset through Riot Development API. Firstly I used the API to access my puuid. With the puuid, I was able to obtain all the Solo Queue match IDs that I played in the 2024. I also included the matches that I played between 01.01.2025-01.08.2025(end of season 14) to increase the amount of data. I used the match IDs to send requests. Since my development key had a limit of 100 API request per 2 minutes, I had to induce a 1.2 second delay between each call to not exceed that limit.


Data Processing, Data Exploration and Data Visualization:

After that, I explored the data and realised that, there were remakes in the data that could potentially worsen my analysis, because of that I created my data frame only using games that lasted more than 5 minutes. I also changed True and False values into 1s and 0s and converted the date of the games into months from unix timestamps. To gather further understanding on my data I did some exploratory data analysis to see patterns. 


- Checked the amount of games that I played in each month and used a bar plot to visualize it (PNG0). From the plot it can be observed that my play count increased gradually into a spike two different times and crashed after each spike.

- Checked the champions that i played the most and used a bar plot to visualize it (PNG1). Plot indicates that I mainly play Ahri and Vladimir.

- 







