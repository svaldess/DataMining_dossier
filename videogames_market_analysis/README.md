# Analysis of the global video games market
## #Business #WebScraping #Plotly

Since the release of the first video game in early 1970s, a ping pong game by Arcade, the video game industry has grown considerably. According to a [report](https://www.zionmarketresearch.com/report/cloud-gaming-market) from the Zion Market Research, the global gaming market was valued at 802 USD million in 2017 and is expected to grow for the following years.

This project explores the growth of the global gaming industry. This sector has become extremely dynamic and complex. Therefore, it is relevant for publishers and developers of video games to understand the major changes in the gaming industry over the last decades and can we expect for the upcoming years.

To answer these questions, this project explores the following topics:

* Most popular video games by genre
* Most popular video games by region
* Most popular consoles

## About the source

The data of this project was extracted from [VGCchartz](http://www.vgchartz.com/gamedb/), a video game sales tracking website. It has information about the consoles, developers, scores, sales, genre, and the year when the video games were released. VGChartz has a vast information of video games since the 1970s. 

The information was scrapped from VGChartz website and `BeautifulSoup` was used for parsing the page. The code used for extracting the information is presented in a separate Jupyter Notebook, called **Project3_WebScrapper**. After the information was successfully extracted, it was stored in a csv file, called "vgames.csv", that was used for reading and manipulating the data.

## About the project

This project was part of an assignment from Introduction to Data Mining class at GWU in Fall 2019.
**Python 3.7.6** was used for cleaning, processing and analyzing the data. **Plotly** were used for data visualization.

The code for scrapping the data can be found in a separate file **web-scrapper-code**. The analysis and visualization of the data can be found in the file **videogames-analysis**. It it necessary to insert *username* and *API key* for connecting to Plotly and for displaying the graphs. An example of the data visualization can be found in the file **vg-presentation**.

## Findings

- **There is a steady rise of number of video games released between 1980 to 2010.** After 2010, the trend has been unclear. This might be a result of the recent development of new online web-based and mobile digital platforms, such as Steam that may become strong competitors for traditional publishers and consoles in the industry.
- **The gaming industry is extremely dynamic.** In the last 10 years the composition of the industry by genres have completely changed with the rise of new genres, such as visual+novel, party, and music. Nonetheless, sports has continuously appeared as one of the top 3 most profitable genres throughout the years.
- **The gaming industry is becoming more profitable.** Total sales in 2010s are 33 times larger than total sales in 1980s. PC games might not be as profitable as other brands, but it compensates this gap by releasing vast amounts of video games.
PC games are more popular in PAL region. Also, in recent years, Play Station has gained terrain in PAL region with its console PS4. On the other hand, Nintendo and Xbox have not been able to expand their market beyond North America (US, Canada, Mexico) as opposed to Play Station.
- **Innovation is what drives the business, and not quantity.** Between 2007 and 2011, publishers flooded the market with vast amounts of video games (specially PC publishers that attempted to gain terrain in the industry). However, this did not translate into higher profits. In 2006, on the other hand, Nintendo registered the highest profit of the past 2 decades. In this year, sport games became extremely profitable (perhaps due to the World Cup in Germany) and Wii was introduced into the market.
