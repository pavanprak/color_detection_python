# color_detection_python


This is a basic python project which uses computer vision.

This program is a simple color identifier tool that allows the user to select a specific pixel in an image and determine the corresponding color name and RGB values. 
The user can do this by double clicking on a specific point in the image, and the program will display a rectangle with the identified color, as well as text showing the
color name and RGB values. The program uses the opencv library to read and display the image and to handle mouse events, and it uses the pandas library to read and
process data from a csv file containing a list of colors and their corresponding RGB values. The program compares the RGB values of the selected pixel to the values in 
the csv file and calculates the minimum distance between them to determine the most matching color. The program will keep running until the user hits the 'esc' key, at 
which point it will close all windows and terminate.

About the data set

For this application we use a CSV File as our dataset.

The contents of this CSV File are the name of the color and along whit this the Hexadecimal code of the Color name.

The CSV file also contain the R.G.B values of all the colors in the dataset.

The Dataset obviously cannot have all possible combinations of R.G.B values for each and every permutation for each and every color.

The Dataset is stored in a CSV File and can be read and arranged by python with the help of pandas library.



Modules or librarys used 
1)OpenCV

2)pandas

3) Numpy

4)Argparser


