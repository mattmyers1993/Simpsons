# Simpsons Series Report
This interactive [Power BI report](https://app.powerbi.com/view?r=eyJrIjoiNmEwOWMzY2EtY2Q2ZS00ZjIxLWExOWMtNDFiZjA2OTVhNjg1IiwidCI6ImJjMzM5NDJjLTE2YjQtNDcwYS04Yjc5LTk1MmNmMzY0NmJjYiIsImMiOjZ9) explores The Simpsons through viewership trends, top episodes, characters, and locations. Users can drill into any episode to explore its dialogue and see how characters and settings contribute across seasons.

## Visual Elements
**Viewers by Season** shows each season's total viewers in millions.

**Top Episodes** shows the season, episode, episode title, and the number of viewers in millions.

**Top Characters** and Top Locations show the top 10 characters and locations respectively for the reports filter context. (See below for more on filter context).  

## Drill Down
You can drill down on **Viewers By Season** to see how many millions of viewers each episode had. To drill down ensure the down arrow is checked and then click on a season to drill down into that season. 

This will change the filter state of the other visuals so that the **Top Episode Table**, **Top Characters Bar Chart**, and **Top Locations Bar Chart** are specific to that season.

If you drill down to a specific episode, the visuals will be specific to that episode.

## Cross Filter
Similarly, if you select any episode, character, or location, the other visuals will filter to show data relevant to that episode. i.e. If you click on Mr. Burns in the Top Characters Bar Chart, you will get the top episode he appears in as well as the top locations he appears in. 

## Drill Through
If you find an episode of interest right-click on it in the **Top Episodes** or **Viewers by Season** visuals and select **Drill Through > Episode Page**. This will take you to a page with all of the episode's dialogue. These visuals will cross filter in a similar manner. i.e. Clicking on Mr. Burns will filter the dialogue and locations to only his lines and locations.

## Data Credit
Data courtesy of Tod Schenider and William Cukierski via [Kaggle](https://www.kaggle.com/datasets/prashant111/the-simpsons-dataset).

