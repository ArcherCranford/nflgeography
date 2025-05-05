## Overview of the Map ##
  This map was designed to allow the user to browse the NFL teams across the United States. When opeaning the application, you are greeted with a welcome page that explains the map and where the inspiration of the map came from. The original article I gained inspriation is from National Geograhpic about [sports tourism](https://www.nationalgeographic.com/travel/article/why-sports-tourism-is-on-the-rise). Now, the user is allowed to click on point data of the locations of each NFL team. After the user clikcs on a team's location they are given a side bar of information including; Team name, stadium, team record, team rival, division, year established, superbowl count, top players, and a brief history. The map zooms to the stadium if the point icon of a football is clicked. However, if a user were to search the team in the search bar, the map will only give a general state overview. 

## Libraries ##
### Leaflet.js: ###
- CSS: https://unpkg.com/leaflet@1.7.0/dist/leaflet.css
- JavaScript: https://unpkg.com/leaflet@1.7.0/dist/leaflet.js
- Leaflet-AJAX: https://cdnjs.cloudflare.com/ajax/libs/leaflet-ajax/2.1.0/leaflet.ajax.min.js
### jQuery: ###
- JavaScript: https://ajax.googleapis.com/ajax/libs/jquery/3.1.0/jquery.min.js
- Chroma.js: https://cdnjs.cloudflare.com/ajax/libs/chroma-js/1.3.4/chroma.min.js

## Objectives of Map ##
1. Provide users with an interactive experience to explore the NFL.
2. Giving the user a description of each team with information that would allow them to get a general overview of the team.
3. Understanding the spatial distribution of the teams. Seeing how close some team are and seeing which state has more teams than the others.

## Limitations and Lessons Learned ##
### Limitations ### 
Previously I planned on making the map give the information about each major 4 North American Sport (NFL, MLB, NBA, NHL). As I began to work on the NFL portion I realized how big the project would be. Plus I needed to learn how to include a drop down menu and chnage the data depending on the sport. So, I limited myself to just the one sport (NFL) and decided to add more information.
### Lessons Learned ###
There were a couple features in this map I previous had to clue how to make and I had to learn. That being the search bar and the welcome pop up menu. There were other smaller piece of code I had to look up but those were the major ones. The welcome pop up, though not super complicated, still required a little bit of research to make sure I could make it correctly. Next, the searchbar was a lot more difficult because I realized how much I needed to do to make the search bar work efficiently. Firstly, I needed to allow searches that could be partial. So, I made it if you type part of the name it will take (e.g. "ravens" would tkae you to the Baltimore Ravens). Other smaller parts of the code included; making sure clicking enter would start the search and properly displaying the team data. When searching the team it will not take you directly to the stadium like the click. It takes you to a 6 zoom over the state. 
