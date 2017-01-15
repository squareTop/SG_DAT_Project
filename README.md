_This is my GA project_

# RF Transmission Locator

This project aims to predict the location of an RF transmitter. In a wireless network, RF transmitters are able to share GPS coordinates with each other. This allows tracking of transmitters that are on the move. In the event whereby a transmitter loses its GPS reception, its coordinates can be predicted by:

Predicting in distance between the transmitter and other transmitters based on RF reception levels.
Using the predicted distance, use trilaration to find the new location of the transmitter.

## Getting Started

Deployment Notes: 
Able to collect frequency and amplitude data from RTL-SDR

### Pre-requisites

Clone repo
Set up Jupyter Notebook
pip install Python Packages gmplot, sklearn, matplotlib, pandas and numpy

### Scripts to run:

Mapping.ipynb will plot the data provided into the mymap.html file (Google Map).
If you are preparing your own data, use Train Model 2.ipynb to train the prediction model and Evaluate Model.ipynb to determine if you are satisfied with the model.
Run Calculate Coordinates.ipynb to calculate the coordinates of the predicted transmitter location. These should be used for Mapping the data onto Mapping.ipynb for your own project.

#### Additional Notes
Do contact me at andrewloone@hotmail.com if you have any queries.

#### Acknowledgements
General Assembly Singapore's SG_DAT2 Team: Misrab, Shahram and Guo Jun.

*By*
*Andrew Loone*
**14 Jan 2017**
