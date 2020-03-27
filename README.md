<p align="center">
  <img width="412" height="400" src="https://github.com/minh1001/gong_cha_locations/blob/master/boba_tea.png">
</p>

# Gong-Cha Franchise Location Optimization

### Objective: Help Gong-Cha shortlist potential locations for a new franchise. 

For each existing location in NYC, pull all data belonging to census tracts within 1-3 miles. 

Build a model that will successfully predict the locations of the existing locations. If the model performs very well, review the false positive predictions as potential franchise locations. 

The idea here is if the model is good at predicting current locations, we should pay attention to the locations where it thought there was an existing location even though there wasn't. These locations must have possessed qualities that the model was looking for when identifying CURRENT locations.

### Data:
Census ACS Data
  Housing 
  Economic
  Demographic
  Social
