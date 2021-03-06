# Overview
This project began back in February when I was learning Pandas for the first time. There were two particular parts of my grade administration that were tedious, and I thought that a good way to improve my use of pandas would be to use list comprehensions to automatically delete Gradescope's massive number of bloat columns and use a right merge to combine all of my student grading data into one spreadsheet with only the students who were still enrolled in the class. Once that was done, I still did everything else in Excel as I normally would. 

As I learned some matplotlib and seaborn, I was curious about how to make use of visualizations to see student progress in their exams and other aspects of the course. Then as I made progress in a data science bootcamp, I wanted to use even more of the things I was learning to both understand student performance and also front-load the grade administration process. It was a great way to do many useful things at the same time. 

The script named "Grading Script 34A Spring 2022" is the result of this process, and almost all of the code you see was used to create the grade submission file. Some TAs and professors expressed interest in a grading utility, so I wanted to polish and publish it so they could make use of this code. 

## The Grading Script "Grading Script 34A Spring 2022.ipynb"
Script for compiling multiple csv files with grade data and an updated registrar list in them. The files are merged into a single data frame, the columns are cleaned and sorted, and grades are computed (this part is over 75% of the lines of code!). A detailed spreadsheet is saved as a CSV file, and leaner version is saved as a CSV file to be uploaded to the registrar. 

## Straight to Spreadsheet Grading Script
This is a template with step-by-step instructions for someone to run the non-grading parts of the grading script. Run this if you want to combine your CSV files and get started with grading in Excel. 

## gradingfunctions.py
This is a file meant to store all of the functions used in the grading script. The original version of the grading script had just spaghetti code and friends of mine had no desire to read that. This should hopefully make things look a lot cleaner. 

## Scatter Plot Visualizations Script.ipynb
This was just me having some fun trying to find visual correlations between various features and student grades. There are a lot more visualizations, some that I made during the quarter and many others that look cool but aren't at all organized. I'll upload them when I have a set I'm happy with and they don't just look like a hodge-podge of visualizations. 

## Pie Chart of Grade Weights for the Syllabus
I had this idea as I was reading about pie charts and how to make them in matplotlib. The colors list is not used in the version you see because I was happy with the color arrangement, but feel free to play around with that part if you're not happy with the collor scheme of your chart. Here's a great resource for color names: https://matplotlib.org/stable/gallery/color/named_colors.html. Many of my students did not realize that before a midterm and the final were taken, more than half their grade had still yet to be determined. I thought that making a pie chart might help with this. This chart's counterpart is already on the syllabus for my next course right next to the grading breakdown. :)
