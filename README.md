# mapmanager

MAPMANAGER

IMPORTANT: mapmanager has been designed to analyze data from the website seamap.env.duke.edu. Data sets from this website are in .csv format, and need to be transformed to .txt before mapmanager analysis.

Rpackages required:
	-marmap

HOW TO USE_

1.Before starting mapmanager, change the name of the file you want to analyze to "data_all.txt" and go on the command line to the directory where the file is.

2.Start mapmanager by typing "mapmanager.sh" in the command line. 

3.Mapmanager will ask you if you want to print the code of each specie. Mapmanager works with codes assigned to each specie. If you don't know the code of the specie you want to analyze type "yes" and three lists with the code for each specie will be printed. First list compiles the codes for species fully identified; second list only to a genus level and third list the codes for unidentified species.
Otherwise type "no".

4.Enter the code of the specie you want to analyze.

5.Enter the year in which you want to center your analisys.

6.Enter the month in which you want to split your analysis.

7.Mapmanager will create a folder where you will find three files: 1_period_data_all.txt (text file with the data before the month of your choice), 2_period_data_all.txt (text file with the data after the month of your choice) and 3_all_data_all.txt (including all data for the chosen year). You will also find two pdfs (one from the first period and the other one from the second) with the coordinates plotted and two graphs, one for number of sightings and the other one with the counts of individuals per month.


8.If any bug is detected, please contact
				javialegria92@gmail.com
				luciairaz93@gmail.com
winter.R and summer.R are identical R scripts with different outputs. comments can only be found in summer.R

