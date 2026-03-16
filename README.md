# San Francisco.
The assignment was done in google collab to preserve the outputs and ease the presentation. 

Datasets are:
https://data.sfgov.org/Transportation/Map-of-Parking-Meters/fqfu-vcqd

and random 5%(dataset was way too big to process in full) with some columns removed from https://data.sfgov.org/Public-Safety/Fire-Department-and-Emergency-Medical-Services-Dis/nuek-vuh3/about_data

Majority of explanations is done via comments in the code.

The goal was to see whether there is some relation rule between number of parking  lots  and speed of emergency dispatchers coming to the place of event. My assumption was that the huge parking space hinders(or otherwise) easy access to area in some manner. 

First, correlation was attempted to be noted by numerical comparisons, but there was no noticeable correlation noticed.
Looking at K-means and tree classifiers also did not help, as variables like address(similarly important for both, a bit different for variables like the time of day, as tree put it first in importance and k-means put it lower) were outweighing parking numbers significantly. 

Last attempt to note correlation was done through searching clusters in scatterplots, as it could’ve indicated some rule if there is a notable number of points gathered around some value. This attempt seemed unfruitful too, but it potentially can be due to the way in which plots were done – points overlay each other, red points always overlay blue ones if they are in the same spot, etc. 

