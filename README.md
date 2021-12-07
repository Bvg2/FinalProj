# Final Project

## Team Members:
* Ben Gradeck: bvg2@pitt.edu
* Jackie Colmenares: jgc45@pitt.edu
* Giovanna Niccolai: grn21@pitt.edu

## Our Datasets
### Park Area
https://data.wprdc.org/dataset/parks

This dataset shows where and how big the parks in Pittsburgh are. It includes the area of the parks in acres, their locations with longitude and latitude, and the neighborhoods they are in.

### Water Features
https://data.wprdc.org/dataset/city-water-features

This dataset shows where there are water features in the City of Pittsburgh. It includes the type of feature (drinking fountain, spray fountain, or decorative fountain), the neighborhood it is in, a link to a picture of the fountain, and the longitude and latitude. 

### 311 Data
https://data.wprdc.org/dataset/311-data

This dataset shows the complaints and requests made to the non-emergency police line in Pittsburgh (which is 311). It includes barking dog complaints, which is what we were most interested in. The dataset includes the type of request, the neighborhood of the request, and the longitude and latitude of where the incident/request occurred (either exact or approximate).

## Abstract
  Our project was centered around finding the best neighborhood for a dog to live in. To determine this, we used three separate metrics and then combined them to find the winner. Those three metrics were the neighborhood with the most park area, the neighborhood with the most water fountains, and the neighborhood with the most dog barking complaints.
 
  The first metric is the neighborhood with the most park area. Dogs need space to run around and play, so a neighborhood with a large amount of greenspace is necessary. This was determined by using a dataset that gives the parks in Pittsburgh, how many acres they are, and where they are. By manipulating this dataset and displaying it, we found that the neighborhood with the most acres of park area was Squirrel Hill South.
  
  The second metric is the neighborhood with the most water fountains. When dogs are out on a walk, it is important that they have access to water, so it is important that they live in a neighborhood with many water fountains. This was determined by using a dataset that gives the coordinates and neighborhood for every water feature in Pittsburgh. By filtering the dataset to only drinking fountains, manipulating it, and then displaying it, we found that the neighborhood with the most water fountains was also Squirrel Hill South.
  
  The third metric is the neighborhood with the most complaints of dogs barking. Above all, dogs are social animals who love to make friends. Therefore, it is important that they live in a neighborhood with many other dogs. We decided that a good way to measure this was to find neighborhoods with many dog barking complaints because where there are lots of dog barks, there are lots of dogs. We used the 311 dataset, a dataset that records complaints and requests from all around the city, to find this data. It includes where the complaints were made as well. After cutting the data down to just dog bark complaints, manipulating it, and displaying it, we found that the neighborhood with the most complaints of dog barks was Brookline.
  
  For our overall metric, we weighted each of the individual metrics to make them equal and stacked them in a bar graph. This created a visualization of which neighborhoods had a good amount of all three components. After doing this, we found that the overall best neighborhood for a dog was Squirrel Hill South. 
