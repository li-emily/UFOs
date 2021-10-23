# UFOs

## Overview of Project: 
### Purpose
> Dana’s webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, you’ll add table filters for the city, state, country, and shape.

### Goals
- Build familiarity with Javascript, especially in regards to creating and deploying Javascript functions.
- Convert regular Javascript functions to arrow functions.
- Search and manipulate data using D3.js, then creating and implementing filters on dataset.
- Create and rebuild filtered tables of data, with visualization using HTML/CSS.

### Resources
- Languages: Python 3.7.10, Javascript, HTML, CSS (Bootstrap)
- Interface: Visual Studio Code
- Packages and Software: D3.js
    
## Results
The new UFO sightings website has filters for date, city, state, country, and shape. One to all filters can be used at once to sort through this. Input is through typing, which is then searched for automatically after leaving the search box.
Scroll past the opening blurb to get to the filters and data below.

![website](https://github.com/li-emily/UFOs/blob/main/static/images/webpage.png)

![filters](https://github.com/li-emily/UFOs/blob/main/static/images/nofilter.png)

When a parameter is entered, the data will automatically filter the data based on what is entered. This can be entered without worry of capitalization. See as both NJ and nj are able to be searched properly.

![filtered](https://github.com/li-emily/UFOs/blob/main/static/images/filter.png)
![filter_uppercase](https://github.com/li-emily/UFOs/blob/main/static/images/filter_uppercase.png)

## Summary
A large drawback that this new design has is the inability to sort by duration or comments. If duration data was edited to all be stored in the same format, then it could be sorted through and filtered. Since comments are long, could potentially search for a key word and then the function could use the search() function to find data that correlates with that. Date search could be split into year/month/day so the users can search for individual months or years to see patterns. 

Additional issues include the specificity required for the date search parameters, as well as difficulty to enter parameters cold. A date range function could also be helpful, and would benefit greatly from potentially 2 dropdown boxes with prefilled dates. Additional elements that would enhance user experience while searching would include an autocomplete function or as mentioned before, a dropdown box that could be used instead of typing in the input box. 
