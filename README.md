# Kickstarter Analysis Project

This repository contains the final project done for my graduate data analytics course at Willamette University. The objective of the project was to complete an analysis on supplied Kickstarter crowdfunding data, answering macro-level questions, telling a clear story, and uncovering trends in the data which could be could be acted upon. In 72 hours, I was able to clean, wrangle, explore, and provide actionable reccomendations for stakeholders in the data.


## Table of Contents

- [About](#about)
- [Contents](#contents)
- [Skills](#skills)
- [Usage](#usage)
- [License](#license)
- [Contact](#contact)

## About

#### The Goal

The scope of this project was aimed at addressing, but not limited to:

- Which categories contain the greatest quantity of campaigns? The least?
- Is there any time trend in terms of the number of campaigns launched?
- Which project categories were tied to the most successful campaigns? The most unsuccessful campaigns? (And how do you define “successful”?)

#### The Data

The data for this project comes from [Data Golf's Free PGA Archive](https://datagolf.com/raw-data-archive), where a free sample CSV of 2021 Masters Tournament data was aqquired. Again, raw golf data is not easily accessible and since the scope of this project was visualization and not a data pipeline, the free sample CSV was data used for this project.

#### The Product

The final product was a Shiny App Dashboard that can be viewed at this [link](https://aweirth.shinyapps.io/shiny_masters/). The dashboard achieved the goal of communicating critical insights by showing the dominant performance of Hideki Matsuyama's Strokes Gained Statistics across the board and especially Tee to Green. The dashboard was also able to be understood by peers in my graduate class who are not golf fans, and by friends who are not familiar with statistics or data visualizations. This Shiny App represents how less is more sometimes when communicating data. Only two best graphics from my EDA stage were chosen which cleany and cleary communicate important findings without the dashboard turning into something that resembles an airplane cockpit (example: comparing one data point to a boxplot can communicate a lot of informatin with few pixels).

## Contents

In this repository you will see the following files:

Data:
- **raw_pga_2021.csv:** This is the raw CSV from Data Golf's Archive.
- **masters2021_cleaned111.csv:** This is the cleaned full 2021 Masters CSV from Data Golf, cleaned by the masters_wrangling.R script.
- **masters2021_lb.csv:** This is a wrangled dataframe from the above masters2021_cleaned111 file. This is the data being sent to the leaderboard on the homepage.

Cleaning Script:
- **masters_cleaning.R:** This is the script responsible for cleaning the raw csv and prodicing the cleaned CSV's.

The App:
- **App.R:** This is the R script responsible for producing the R Shiny App. It contains custom HTML/CSS styling and the GGplot code for generating the graphics.

## Skills

Data Cleaning:
- Processed the raw CSV file to handle missing values, inconsistencies, and manipulated the data strucutre to work with my project.
- Engineered new features helpful for construction of the dashboard and communicating insights.
  
Data Visualization:
- Utilized R Shiny App's visualization libraries (e.g., ggplot2, plotly) to create interactive and informative charts, graphs, and tables.
- Designed the dashboard layout to effectively present the insights derived from the data.
- Successfully selected the most effective visualizations from my EDA process.
  
Data Analysis:
- Conducted exploratory data analysis (EDA) to uncover patterns, trends, and relationships within the dataset.
- Employed statistical techniques to derive meaningful insights from the data.
  
Web Development:
- Developed a user-friendly and responsive web interface using HTML, CSS, and JavaScript within the R Shiny framework.
- Customized the appearance and layout of the dashboard to enhance user experience.

## Usage

Instructions on how to use the dashboard are in the "About" tab of the top ribbon. There, you will find helpful tips as well as hints to find the key insights I found in the graphics.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

Feel free to reach out to me if you have questions or comments!


