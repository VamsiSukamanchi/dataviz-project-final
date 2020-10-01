# Data Visualization Project

## Data

The data I propose to visualize for my project is that of the videogame sales This dataset contains a list of video games with sales greater than 100,000 copies. It was generated by a scrape of vgchartz.com. Fields include Rank - Ranking of overall sales, Name - The games name,Platform - Platform of the games release (i.e. PC,PS4, etc.), Year - Year of the game's release, Genre - Genre of the game, Publisher - Publisher of the game, NA_Sales - Sales in North America (in millions), EU_Sales - Sales in Europe (in millions), JP_Sales - Sales in Japan (in millions), Other_Sales - Sales in the rest of the world (in millions), Global_Sales - Total worldwide sales.

## Prototypes

I’ve created a proof of concept visualization of this data. It's a scatter plot with low opacity points and it shows the global sales of a game with respect to their platform.

[![image](https://github.com/VamsiSukamanchi/dataviz-project-template-proposal/blob/master/Screenshot%202020-09-30%20215515.png)](https://vizhub.com/VamsiSukamanchi/dcec3d913e2a46eaaef900af26dbde56)



## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * Do the sales of games increase every year, if so, which publisher is gaining more popularity?
 * How much correlated are the sales of a game in different regions?
 * Does a region favor any publisher, genre or platform?
 * How many sequels or remakes have made it to the list?

## Sketches
[![image](https://github.com/VamsiSukamanchi/dataviz-project-template-proposal/blob/master/IMG20201001174437.jpg)]

The axes represent the year and total global sales, using the publisher variable as color in bar (stack). Hopefully, the number of publishers are not high making it hard for viz. The first question will be answered through this. If the bars are like a waterfall, then then there is increase in sales every year. Using tooltip, we can see which stack of the bar is increasing in length, to see which publisher is gaining popularity.

[![image](https://github.com/VamsiSukamanchi/dataviz-project-template-proposal/blob/master/IMG20201001174458.jpg)]


## Open Questions
Can rows be parsed word by word into a dictionary to find common words?
Can we take a sample set to represent the whole fairly?
