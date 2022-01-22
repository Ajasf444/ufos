# ufos

## Overview
The purpose of this analysis is to create a website that displays a variety of UFO sightings.
Multiple filters are available that can help to isolate sightings that are of particular interest.
## Results

### Blank Filters
![blank filters](/Resources/no_data_filters.png)

The filters update the displayed sightings in real time.
The data can be filtered by date, city, state, country, and shape of the UFO.

### Example Filter
![example filter](/Resources/example_data_filter.png)

Above is an example filter being used to filter by the city of San Diego.
One has to either click off the text box when finished entering data, or the user can click their Enter button.

### Example Filtered Results
![example filtered results](/Resources/example_filtered_results.png)

The results for the above filter can be seen above.
## Summary

- One drawback of this new design is that on the back end each time the filters are changed the program searches through all the data again.
  - This could be remedied by returning the previous filtered data as a variable, and only displaying the entirety of the data when there are no filters.
    Ultimately, this isn't too big of an issue given the size of the data set.
- Another recommendation would be to make the filters case insensitive for easier searching, especially on phones which may automatically capitalize the first character.
  - This was implemented in the backend by capitalizing all the strings during the comparison.

