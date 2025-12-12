# DATASCI 306 Final Project
This is the final project for Datasci 306: Introduction to Satistical Computing

This project is a webapp built using Shiny in order to measure and analyze the predictability of NFL teams' scores under varying conditions. The webapp allows users to adjust a number of variables to analyze the predictability of teams. The variables that can be adjusted include: wind speed, home rest days, away rest days, surface type of the field, indoor/outdoor status of the field, the time of day the games are played, and whether or not games are played on a weekend. The user can also select the range of years they wish to pull data from to analyze. 


### Five windows allow for the exploration of the effect that these variables have on a teams predictability.

Rolling Predictability (plot): This is a visual representation of how the predictability of NFL teams changes over time. Each line graph represents a different NFL team. Lower scores show that a team was more predictable during that time.

Team Predictability (table): This is a table of the overall predictability of an NFL team. Again, lower scores represent a team that is more predictable.

Trend Slopes (plot): Slopes of predictability over time for each team. 

Trend Results (table): Data table used for the Trend Slopes (plot) window

Model Summary: This window is a mixed-effects regression of margin on environment variables, with random intercepts for home and away teams


### The webapp can be accessed via this link
Webapp: https://junseokpark.shinyapps.io/Project/
