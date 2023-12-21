# Analise-de-Temperaturas
Temperature analysis
This project was used as an assessment in the subject of Programming Logic

Phase 2 Project
Python 3.10.11

The Project was divided into the following steps
#1- Reading the file
In addition to reading, data was checked and data converted

#2- Data visualization
In visualization, a function was created to visualize the data frame according to some requirements
NOTE: I did not read the dictionary or list because it was very difficult to try to apply validation and filter within the same

#3- Calculating least rainy month
In this part of the code I created 2 functions, the first of which collects the smallest precipitation. The function receives the df (dataframe) as an argument.
The second function performs the same collection but with a filter that the precipitation must be greater than 1.
As I didn't know which one to use and didn't have time to ask the tutors, I left them both.
NOTE: Again, everything was done in pandas dataframe as it was impossible to do it in list/tuple/dict

#4- Calculating the average minimum temperature of a given month.
In a single function, it filters and displays the average for the chosen month between 2006 and 2016.
The user input was made outside the function so that it could be reused in the next function.
After receiving the user's input, a quick validation is carried out in order to guide the user so as not to leave the input without validation.
NOTE: the function receives the dataframe and the chosen month variable as a parameter.

#5- Viewing the bar chart
In a single function, which receives the dataframe and the previously chosen variable, the grouped and filtered bar graph is "plotted": "month chosen by year"




In this project, 4 libraries and a sublibrary were used:
  -pandas: for reading, viewing, and processing data;
  -matplotlib: to import the matplotlib.pyplot sublibrary, which in turn was used only to plot the graph;
  -calendar: used to filter the data frame when applying functions.
  -datetime: used to convert the dataframe's "date" data and display certain filtered date


Final considerations:

Due to lack of time, I couldn't finish all the classes and do the work at the same time.
A lot of time was spent trying to carry out all the activities in a dictionary or list/tuple and even then I couldn't move forward with the work, it ended up that pandas did almost the entire project.
Some validations could be more functional without having to execute the line of code again, but it was getting really ugly and there was no time, I decided to just validate the entries in a guided way.
The project functions were made to perform in the proposed file, another file used in the same project will present errors.
