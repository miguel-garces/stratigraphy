# stratigraphy
For **paleocurrent analysis** there are two notebooks, one built to run on jupyter notebook and the other one to run on google Colab. To run the code in jupyter notebook, installation of pandas, numpy and plotly libraries is required.

The code performs the calculation of the mean and standard deviation of the azimuths, and plots the results in a rose diagram.

Input files must contain paleocurrent azimuths, in the form of an excel file. The first row contains headings (paleocurrent type, such as flutes, grooves,...):

| grooves |  foresets |  flutes|  etc

|azimuth1  |    azimuth1  |  azimuth1|

|azimuth2  |    azimuth2  |  azimuth2|

|...     |    ...   |    ...!
