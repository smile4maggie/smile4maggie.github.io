---
title: BearMaps
made: MADE IN CS 61B
weight: 5
icons:
- title: Java
  icon_name: devicon-java-plain-wordmark
---
BearMaps is a web-mapping application that uses real-world map data to visualize
roads, locations, and shortest paths. Using rastering to generate the best map possible for a specified zoom depth, I created a QuadTree class that recursively stored tile image file names, and depending on the user’s desired query box or ‘viewing rectangle’ on the map, I returned the set of images at the best resolutions needed to form that map. I also added shortest-path finding and autocomplete functionality, where I used the A* algorithm to visualize and locate the shortest drivable path between two points and a Trie to store and prefix match locations.
