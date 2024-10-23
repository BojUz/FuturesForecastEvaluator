This program evaluates a certain forecast by making deals with energy. It takes info from files that my colegues scraped so i won't be uploading them. The program works by taking data from a sertain
day in the past that i already have all the info i need. For example let's say i take 2023-01-01 forecast and futures values. Forecast says that after 3 days the price of electricity in Germany
will be 54,44 euro for example and the price of the futures is 50,44 euro. In that case the program sends a BUY signal and checks the actual price after 3 days in the Spot.xlsx. Lets say the Spot price is
is exactly like the forecast value wich is 54,44 wich means we made a profit of 4 euro. The program also searches for the best difference in days between the current day and the forecast and also
searches for the most profitable margin buffer between the forecast and futures. For example lets say the buffer is 5 euro wich means that if the difference between forecast and futures is less than
5 euro it will not give BUY/SELL signal it will just HOLD.
![Screenshot_1](https://github.com/user-attachments/assets/1fa1a3e9-7917-426d-93aa-bf4ca219d7b5)


The program also makes a graph and searches for corelation between absolute value of the difference between futures and forecast and the actual profit from the trade.

![eb40f00a-fd48-44cc-91f0-a2c5b6daa206](https://github.com/user-attachments/assets/0ccebfd2-7614-4f77-b10d-c659d06a8236)


The scrape program just scrapes the useful data from the HTML response and converts it to a .csv file.

