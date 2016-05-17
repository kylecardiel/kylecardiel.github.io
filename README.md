## Website Performance Optimization portfolio project

####Part 1: Steps required to successfully run the application

1. Go to: http://kylecardiel.github.io. This will take you to the portfolio page
1. Click on Cam's Pizzeria link on the portfolio page to see the pizza page


####Part 2: Website Performance Optimization Made

Portfolio page I made the following changes:
1. Decreased the size of the pizzeria picture while still keeping it large enough to see clearly. The Original JPEG iimage was way larger than needed to be to display so small on the site.
1. Made the javascript call for google-analytics an async call since it was not needed during the load.
1. Based on Google-PageSpeed test I changed the implementation of the font family download with the @font-face annotation.
1. Created a "min" version of CSS and linked that for the index.html to load.

Pizzeria page I made the following changes:
1. I removed repetitive and costly calcuations from inside of loops to outside.  This was done for both the changing pizza sizes and position of the background pizzas.
