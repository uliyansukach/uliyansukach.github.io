# San Francisco Crime Data Story

**Live Website:** [https://uliyansukach.github.io/](https://uliyansukach.github.io/)

This repository contains a short, interactive data story exploring the patterns of Larceny/Theft in San Francisco from 2003 to the present. This project was created for the Social Data and Visualization course at DTU (Assignment 2 / Exercise 2.1).

## File Directory

This project is built using a "Magazine Style" linear layout. The live website relies strictly on the following four core files:

* **`index.html`** * **The Main Code:** This is the core HTML/CSS file that structures the website, contains the narrative text, and weaves the visualizations together into a single, readable article.
* **`average_weekly_thefts_heatmap.html`** * **Interactive Heatmap:** A Plotly visualization embedded in the article that shows the time of day and day of the week when thefts are most likely to occur, filterable by district.
* **`theft_district_interactive.html`** * **Interactive Map:** A Plotly choropleth map demonstrating the relative concentration of Larceny/Theft across different SF police districts over time.
* **`SF_yearly_crime_trends.png`** * **Static Chart:** A bar chart comparing total historical crime volumes (2003-2018) to modern trends (2018-Present).

> **Note on other files:** Any other files, folders, or Jupyter Notebooks present in this repository are from previous exercises, data cleaning steps, or alternative drafts. They are **not** used or required to run the final live website.

## Built With
* Python (Pandas) for data wrangling
* Matplotlib & Plotly for data visualization
* HTML5 / CSS3 for the front-end layout
