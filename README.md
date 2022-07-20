# UFOs Analysis

## Overview

Dana's webpage and dynamic table are working as intended. In order to provide a more in-depth analysis of UFO sightings, we added more table filters allowing users to filter for multiple criteria at the same time.

## Results

### UFO Sightings

![Webpage](/resources/site.PNG)

### Using the table filters:

![Using_filters](/resources/filters.PNG)

## Summary

### Drawback

Users must use specific dates, cities, or shapes when using the filters. The filters require correct lower-case spelling and cannot include spaces at the end. The city that was used, for example, could not be typed as "elcajon", “el cajon_”, or "El Cajon". The only acceptable input would be "el cajon".

### Recommendations

1. Add a trim function to catch spaces at the end of words, as well as allow for upper and lower case spelling.
2. Adding a filter for a date range instead of a singular date. That way users can search if UFO sightings occur frequently in a specific month instead of in a specific day of the month.
