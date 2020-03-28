<p align="center">
  <img width="412" height="400" src="https://github.com/minh1001/gong_cha_locations/blob/master/boba_tea.png">
</p>

# Gong-Cha Franchise Location Optimization

### Presentation Time Limit: 4 minutes
The time constraints are purposefully kept short to force us to deliver our results in a clear and consise manner that can be digested by an audience of varying technical acumen.

The slide deck is not meant to by any means comprehnsively detail the substantial amount of analysis, coding, and modeling that went into the project.

### Objective: Help Gong-Cha shortlist potential locations for a new franchise. 

For each existing location in NYC, pull all data belonging to census tracts within 1-3 miles. 

Build a model that will successfully predict the locations of the existing locations. If the model performs very well, review the false positive predictions as potential franchise locations. 

The idea here is if the model is good at predicting current locations, we should pay attention to the locations where it thought there was an existing location even though there wasn't. These locations must have possessed qualities that the model was looking for when identifying CURRENT locations.

### Data:
Census American Community Survey (ACS) Data   
Approx. 1900 features in total between Housing, Social, Economic, and Demographic statistics

### Code:
All coding was done in a Jupyter Notebook via Google Colab.
