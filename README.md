# Overview
This project began back in February when I was learning Pandas for the first time. There were two particular parts of grade administration that were very tedious, and I thought that a good way to improve my use of pandas would be to use list comprehensions to automatically delete Gradescope's massive number of bloat columns and use a right merge to combine all of my student grading data into one spreadsheet with only the students who were still enrolled in the class. Once that was done, I still did everything else in Excell as I normally would. 

As I learned some matplotlib and seaborn, I was curious about how to make use of visualizations to see student progress in their exams and other aspects of the course. Then as I made progress in a data science bootcamp, I wanted to use even more of the things I was learning to both understand student performance and also front-load the grade administration process. It was a great way to do many useful things at the same time. 

The file Grading Script 34A Spring 2022 is the restul of this process, and almost all of the code you see was used to create the grade submission file. Some TAs and professors expressed interest in a grading utility, so I wanted to polish and publish it so they could make use of this code. 

## The Grading-Script (Grading Script 34A Spring 2022.ipynb)
Script for compiling multiple csv files with grade data and an updated registrar list in them. The files are merged into a single data frame, the columns are cleaned and sorted, and grades are computed. A detailed spreadsheet is saved as a CSV file, and leaner version is saved as a CSV file to be uploaded to the registrar. 

## gradingfunctions.py
This is a file meant to store all of the functions used in the grading script. The original version had just spaghetti code and friends of mine had no desire to read that. 

## Scatter Plot Visualizations Script.ipynb
This was just me having some fun trying to find visual correlations between various features and the grade outcome. There are a lot more visualizations, some that I made during the quarter and many others. I'll upload them when they are more organized and don't just look like a hodge-podge of visualizations. 
