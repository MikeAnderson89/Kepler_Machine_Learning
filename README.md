# MACHINE LEARNING FOR KEPLER OBJECTS
Kepler Objects of Interest (KOIs) are stars observed by the Kepler space telescope that are suspected of hosting one or more transiting planets.  The stars are then classified into candidates, confirmed, or false positives.  I built a few machine learning models to predict whether a KOI will fall into one of the above categories based on the KOI's data.

### Models Used
#### K-Nearest Neighbors
#### Random Forest
#### Support Vector Model

### Analysis
The best variables to use were determined by running a correlation analysis on the dataset and testing the models based on varied parameters.

The overall accuracy of the models was ~80%, up from 65% if all of the variables in the dataset were used.  The reason for the disparity is due to over-fitting of the model to the training set, making it inapplicable to unknown data.
