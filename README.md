# NetworkAnalysis

This work has done as a course project "Network Analysis" in Sabanci University.

Intuitively, one can think neighbouring countries have similar taste for music. How can we show, indeed, this is the case? In this analysis, we will utilize network analysis on the dataset scraped from Spotify. <br>
 <br>
We will use top 200 chart for every country listed on Spotify. After gathering several features regarding these songs, a bipartite network will be constructed on songs and countries using Networkx library. After that, unipartite projection of network will indicate number of common songs between countries listed on their top 200 charts- weighted with the rank of song. Thus, we will be able identify whether song preference is strong with countries that are geographically close. <br>
 <br>
Analysis is composed of two steps: <br>
Gathering Dataset From Spotify <br>
Network Analysis <br>
