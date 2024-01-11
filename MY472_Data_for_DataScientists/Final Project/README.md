Project Details 
--- 
The repository contains codes, files for the final project of the course MY472. 

## About the Project: 

**Research question:** “Rolling Stone Magazine ranked their 100 greatest musical artists of all time. At the end of 2023, how has their music endured? Are there any features or characteristics that seem to explain enduring engagement?”

The flow of the project is as follows: 
![image](https://github.com/RiyaChhikara/LSE-MSc-Projects/assets/115228191/6c306548-9c9c-4e28-8190-8bf08eb3fa1f)

The Rolling Stones ranking of 100 artists was webscraped to extract the titles of all the artists. Further analysis is entirely focused on understanding audio features of their tracks, and music style. Their popularity is re-looked at by using the latest Spotify stats, which were extracted for each of the artist. 
The file 'Top_100_Artists.csv' contains: 
1. Names of the Artists
2. Spotify ID
3. Popularity count
4. Followers count

This file has been used in the code, and the code was used to generate it is included in the R Markdown file (commented out). I interact with the artists data mainly using this file, and expand on it further in the Markdown.

**Analysis:**
Using Spotify API, the genres of the artists was assessed, both who were top rankers in the Rolling Stones list, as well as the Spotify ranks (included in csv). The audio features of the top tracks of these artists were analysed, and a comparitive study was done of one artist to another. One of the visualisations could be seen as follows: 


![image](https://github.com/RiyaChhikara/LSE-MSc-Projects/assets/115228191/4fb21ddd-dbd7-41b0-8d21-ad55877ba154)


Note: Most graphics are interactive, which helps to read the numbers. 

To run the code, you can follow these steps: 

## Prerequisites
![spotify Web API ](https://github.com/RiyaChhikara/API-Projects-/assets/115228191/b30df1e1-241e-4ad9-90f1-cce032f1a02b)

Before using this script, you need to have the following:
1. Spotify Developer Account: You should create a Spotify Developer account to obtain the CLIENT_ID and CLIENT_SECRET. Replace these placeholders with your credentials.
2. Spotify Redirect URI: Define a redirect URI when creating your Spotify Developer app, and replace REDIRECT_URI with it.


## Configuration
You need to set the following variables in the script:

- CLIENT_ID: Replace this with your Spotify Developer App's Client ID.
- CLIENT_SECRET: Replace this with your Spotify Developer App's Client Secret.

Sources: 
1. [Rolling Stones Ranking of 100 Greatest Artists](https://www.rollingstone.com/music/music-lists/100-greatest-artists-147446/the-rolling-stones-6-30731/)
2. [Spotify API](https://developer.spotify.com/documentation/web-api)
3. [Billboard Rankings 2023](https://www.billboard.com/charts/year-end/2023/top-artists/)
4. [Spotify Playlist](https://open.spotify.com/playlist/37i9dQZF1DX8YNmLOBjUmx?si=d5e16b95268c4826)
