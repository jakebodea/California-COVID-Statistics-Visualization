# COVID_Visualization

## Loading the project 

Greetings, thank you for viewing my project. Please make sure that the files are all downloaded and in the same folder, afterwhich COVID_Visualization.py must be ran via the terminal:

_python COVID_Visualization.py [deaths/cases] [county]_

If the name of the county has more than one word, it must be put in quotes. Regardless, **make sure the county is capitalized correctly.** For example:

_python COVID_Visualization.py deaths "Los Angeles"_


## What it does

The project downloads current data on either cases or deaths of all the counties in California, as reported by Johns Hopkins on GitHub, and proceeds to plot points on a map of California where the size of the point is in proportion of cases per mi^2 in the county, which uses county population size data. On the right, there is also a line chart displaying the last 10 days' CA cases, selected county cases, and a 10-day rolling average of the county cases. 
