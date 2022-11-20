# Insights on the Film & Movie Industry


## Introduction

There are numerous companies producing films/ movies every year. Determining what attributes contribute to the success of a film is therefore important before one ventures into the industry. 

## Business Problem
### The Problem tatement

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they do not know anything about creating movies.

### The Main Objective
To explore what types of films are currently doing the best at the box office and translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

## Data Understanding
### The Data
The data set used was extracted from movie sites such as IMDB. In addition to this, the following files were read and analysed to produce the data and recommendations detailed herein; im.db, bom.movie_gross.csv and tn.movie_budgets.csv. Lastly, to validate this data reference was made to an article by Toptal which can be accessed using the this link https://www.toptal.com/data-science/improving-imdb-rating-system. To confirm the validity of the data a a Kernel Distribution Estimation (KDE) graph was plotted.

 
### Data Preparation
The data was read first then cleaned before any analysis was done on it.This was done by identifying the null values and their percentage. Next, columns with large percentage of data missing and unecessary columns were dropped to create a cleaner and easier to work with dataframe. For the genres, since the percentage data missing was 0.4%, these were replaced with the title unknown. Lastly, the budget and revenue amounts were converted from strings to intgeres in preparation for the next steps which involved carrying out mathematical operations. 

### Exploratory Data Analysis
The data was analysed based on the metrics highlighted to determine a successful genre. This process involved identifying the highest and lowest profits, ROI, ratings and budgets based on the vaious genres. Next, a bar graph would be plotted to visualize this information. 

### Data interpretation
The Pearson correlation coefficient was used to measure a linear correlation to establish relationships between variables. This was done for each of the data set, that is, profits, ROI, ratings and budgets.

## Conclusions and Recommendations
a. A high production budget would lead to high revenue generated. Thus, Microsoft should not shy away from incurring costs as they will eventually yield high returns.

b. A high ranking would lead to higher revenues. Due to the good quality film produced, a high rating would follow leading to increased revenues and returns for the film.

c. A high production budget leads to higher ratings. This could be due to the type of writers, actors, directors and producers hired to produce the film.

d. The budget has little to no impact on the ROI.

Action and Adventure movies check the various metrics and would be a good venture if taken up by Microsoft. Not only will the profits and ranking be high, but the ROI will be even greater.


## Repository Guide
The data set used can be found under https://github.com/Mitchege/Phase1-Project/blob/main/bom.movie_gross.csv
The presentation can be viewed under https://github.com/Mitchege/Phase1-Project/blob/main/Insights%20on%20the%20Film%20Industry-%20Microsoft%20by%20Mitchell.pdf
