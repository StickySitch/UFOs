## Overview
In order to help Dana refine her UFO sighting website, we have employed the power of ```Javascript```,```HTML```, ```CSS``` and ```Bootstrap```. To refine the site, we have added multiple page filters (Date, City, State, Country, and Shape) to our UFO sighting table. When putting these filters in, our ```Javascript``` file is listening to each input box for the value and automatically updating our table to the preferred filters. With this data UFO enthusiasts can really dive deep!

## Results: How To Use
### How To Make A Search
Alright, so lets take a look at how to make a search! To get started, take a look at the left side of our webpage where we can see the "Filter Search" section:
![Search Image](https://github.com/StickySitch/UFOs/blob/main/RmImages/basicsearch.png)

#### One Filter Search
As you can see, we have a few options to filter by: Date, City, State, Country, and Shape. Let's start with one filters. I'm going to begin by entering a date in the "Enter Date" input box in order to filter the UFO sightings table to that specific date. For example: 
![Date Search](https://github.com/StickySitch/UFOs/blob/main/RmImages/datesearch.png)

Looking above, you can see that when entering the date ```1/10/2010``` our table was filtered to ONLY UFO sightings on that date. Even better, you don't need to click a button to begin the filtering. When clicking anywhere else on the webpage or by hitting enter when the input box is active, the table will be automatically updated to the new filter preference. Let's add another filter!

#### Two Filter Search
To refine our search a little more, I want to filter to see only UFO sightings of spherical shape on the date of 1/10/2021. Take a look below: 
![Two Filter Search](https://github.com/StickySitch/UFOs/blob/main/RmImages/twofiltersearch.png)

Simply by adding "sphere" to the "Enter a Shape" input, out table has filtered to both filters specifics. According to the data we have, there are two spherical UFO sightings on 1/10/2010. 


#### Reset Table and Filters
Want to start fresh? SIMPLE! We made it nice and easy for you! All you need to do is navigate to the top left corner of the webpage where it reads "UFO Sightings".  Simply click "UFO Sightings" and your filters and table will be reset back to default; No filters!

![reset Image](https://github.com/StickySitch/UFOs/blob/main/RmImages/resetimage.png)


## Summary

### Drawbacks
Although our webpage is functional, there are a few drawbacks. These drawbacks can be small but a few small improvements go a long way. 
- **Drawback #1**
The first and the biggest drawback of our current webpage is our data pool; It is too small. In order to let users really dive deep and do research, much more information is needed. When adding one filter, our table a lot of the time is filled with only a handful of results. There have to be more sighting than that! 

- **Drawback #2**
Two words... Case sensitivity. When making a search with any of our filter inputs, the input must be exact! This isn't really ideal. By simply typing "Fresno" instead of "fresno", no results are returned. Even if there were "Fresno" results, the data wouldn't be accurate due to the "fresno" data being missing. 

### Recommendations For Improvement
The drawbacks make it easy to find recommendations for improvements, so lets get into it! 

- **Recommendation #1**
The first recommendation is updating our data pool. Not only is it small, it's static. It doesn't update at all which means there is no new data. Which no new data, this information is a little outdated. To improve this we would simply use ```Python``` to scrape data from the web, store that data in a ```.js``` file and feed it into our table building function.

- **Recommendation #2**
This one **seems** small, but honestly it's quite important. Along with fixing our case sensitivity issue mentioned in the drawbacks above, there are a few other filters that could use a similar treatment. For example, Our "Enter Date" input could be updated to accept other date formats(01/01/2010 or 1-1-2010). In the same realm, the "State" and "Country" input should be updated to accept States or Countries FULL names. For example, "California" should be an acceptable search option for "ca" data points.

- **Recommendation #3**
Simple and easy. Move the reset table/filter button below the search fields. With the button currently at the top left of the screen and not even labeled as a reset button, it's not very user friendly. So by simply moving our reset button to the bottom of the search fields and labeling it "Reset Filters", users will know EXACTLY what it is and used for!
