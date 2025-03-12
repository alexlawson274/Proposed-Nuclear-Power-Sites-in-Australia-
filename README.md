# Proposed Nuclear Power Sites in Australia
This repo contains the calculations of the distance between proposed nuclear power sites, and local cities using Geopy.

##  Methodology
The coalition government is proposing to build 7 nuclear power stations around Australia. I wanted to calculate the distance between these nuclear sites and local populations. To do this, I downloaded a CSV with every Australian city--over 1000 people-- with the city's coordinates. I then used a Geopy library to calculate the distance in kilometres between the site and the surrounding towns.   

##  Source Data 
The city population and coordinates data is available here: [https://gist.github.com/rlvaugh/f5d08b0ef8fae288e4bbcfcf5af9bf89.js]. The population data is based on the 2021 Australian census. To download geopy go to: https://pypi.org/project/geopy/

##  Output
The calculations were used as part of a data journalism project. You can see the full project here: https://aldjhome.substack.com/p/where-exactly-are-the-nuclear-power
![lwOr7- (4)](https://github.com/user-attachments/assets/4020dfeb-2f6e-4a64-b0d4-1429e15d861f)
![26XF6-collie-is-the-nuclear-site-closest-to-a-metropolitan-area (2)](https://github.com/user-attachments/assets/7f464b06-1404-4518-a8ab-f48019b5c82b)


