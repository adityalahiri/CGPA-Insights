# CGPA-Insights
The project aims to visualize, explore and draw inferences from the official CGPA data of around 2500 students of BITS Pilani, Goa, using python.

Libraries used are Pandas, Plotly and Cufflinks.

1. ComputerScienceCgpa
The first visualisation has all Computer Science single degree students of BITS Goa from 2013-2016.
Features- 
X axis- Roll number(Last 3 digits) of every student
Y Axis-CGPA

The scatter plot is color coded on basis of which year the student joined the institution and hence gives information regarding which year he/she is in. For a particular roll number, the Cgpa of students of all years is displayed. On hovering, the name of the student is also displayed.

On clicking the legend on the right that has years, one can hide plots of those year's students and get lesser data.

There are 2 plots.
One has students that have roll number ranging from 001-140 which gives a more clutter free graph.
The other one has all ranges of roll numbers. However, there are only a few students beyond 140 roll number. One infers that these are slided up students. This scatter is more cluttered because of the width of roll numbers that has to be covered.
