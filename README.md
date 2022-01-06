# Phase 1 Project Template - Minimum Viable Product (MVP)

![director shot](.images/director_shot.jpeg)

**Author**: Rachel Fein
 

## Overview
 This project analysis movie databases to give Microsoft recommendations on a few key characteristics the Movie should have to help it be sucessful. Descriptive analysis was done on movie runtime, release month, and budget in relationship to the movies' success based off of net profit. 


## Business Problem

Microsoft has decided to enter the movie industry and wants to find out what type of movie will do best. Investigating the different characteristic of movies that have been released in the past will help give insight and advice to Microsoft on what key characteristics their movie should have to be sucessful.


## Data

The data for this analysis is from IMBd and The Numbers (TN), two repulable online movie database websites.  The IMDb data set that was used consited of the columns: `release date`, `movie`, `production_budget`, `domestic_gross`, `worldwide_gross`. The TN dataframe that was used consisted of the columns: `primary_title`, `original_title`, `start_year`, `runtime_minutes`, `genres`. These two datasets were joined on `movie` and `primary_title`. 

## Methods

This project used descriptive analysis, which included comparing specific data to find trends. The methods of analysis helped pinpoint common trends among the most sucessful movies.

## Results

The analysis concluded that runtime, release month, and production budget all impact the sucess of a movie. 

## Conclusions

This analysis has lead to three recommendations: 
- The movie should last approximently 110 to 120 minutes
- The movie should be released in between May and June
- There is a positive linear regression with production budget and net profits amoung the top movies and it is expect the higher budget the higher the net profit will be. 

## Next Steps

The analysis completed could be further improved by looking deeper into the production budget. Further analysis into budget will allow the client to get more detailed advice which will help guarantee their movie's success. For example, budget put towards special effects or marketing might have a greater impact than the budget spent on the talent/actors.

Other analysis that would further answer the buisness problem would be data modeling of movie genres. An analysis on genre can show insight on if specific genres lead to higher net profit movies. 

## For More Information

See the full analysis here: LINKKK or review this presentation: LINKKK

## Repository Structure


### Notes

- The visualizations in the notebook use best practices for visualization that you should try to emulate. For example, they have clear axes, descriptive titles, and appropriate number formatting
- The `dsc-phase1-project-template.ipynb` is intended to be the _final version_ of your project. The first notebook you create will not look like this. You are encouraged to start with a very disorderly notebook and clean it as you go
