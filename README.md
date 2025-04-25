### Project Title
Capstone Project Initial Report - Exploratory Data Analysis for Exoplanet Detection using Transit Method
**Author**
Prem Isaac
#### Executive summary
The light received from a star decreases in brightness whenever an object passes through the line of sight between the observer(telescope) and the star. If such changes in brightness have a constant frequency, they can serve as evidence by which to infer the present of an exoplanet that orbits the star in a predictable manner. Thus, a predictive model can be built to use dataset consisting of  features extracted from the lightcurve data to infer the presence of exoplanets.

#### Rationale
Why should anyone care about this question?
Theoretical:  Detection exoplanets is central to the search for habitable worlds and understanding planetary formation. Automating transit detection through ML accelerates the discovery process, enabling astronomers to analyze large datasets from missions like JWST and TESS more efficiently and uncover planets that may otherwise go unnoticed.

Practical Dividend: The methodology used here can be refined and applied for motion detection near any fluctuating light source , artifical or natural, to infer the presence of airborne objects which cause light to dip. Additionally, since predictive success depends not only on the specific Machine Learning algorithm used but the quality of the data itself, this exercise can be used to assess and refine the quality of the measuring instrument, which is the telescope , and this can lead to more dividends (improvements to the telescope).

#### Research Question
What are you trying to answer?
Answer: Can the presence of exoplanets orbiting a star be predicted by observing changes in the star's brightness over time?
#### Data Sources
What data will you use to answer you question?
Lightcurve data (timeseries of flux(brightness)) from KEPLER or TESS
#### Methodology
What methods are you using to answer the question?
Answer: Time Series Analysis Methods, including identifying Periodicity, performing De-Trending, and Random Forest Classifier
#### Results
The Light Curve Data contains information that can be mined successfully by Timeseries methods to correctly identify the presence of exoplanets. 

#### Next steps
Perform analysis of a sufficiently large number of datasets in order to create a dataset set of features with known target value that is balanced.
Attempt to build a model to predict the presence of an exoplanet.
What suggestions do you have for next steps?
Try 2 approaches to model building: In the first case, use algorithms such as random forest, gradient boosting, and decision trees. In the second approace, use varieties of Neural Networks.
#### Outline of project

- [Link to notebook 1]()
- [Link to notebook 2]()
- [Link to notebook 3]()


##### Contact and Further Information
