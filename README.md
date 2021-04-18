# UFO Sighting Data Table

## Background

### Purpose

The "UFO Sightings" webpage gives users access to a dynamic table of UFO sightings, organized by sighting date, city, state, country, observed shape and additional sighting comments. Previous UFO sighting data is made avaialble through the webpage and there are 5 active filters that can be used to sort the data; date, city, state, country and observed shape. The filters can be cleared and used for additional searches. Overall, the webpage offers a streamlined view of the UFO sighting data and ability to quickly sort based on different criteria using the filters. 

## Results

### UFO Sighting Webpage Functionality

###### Webpage Overview
>![webpage_overview](https://user-images.githubusercontent.com/77405273/115153254-cdb18a80-a029-11eb-85d6-226936c986dc.png)

The webpage has an attention grabbing title and image, with added context provided in the "UFO Sightings: Fact or Fancy" section. Below is a dynamic table with UFO sighting data organized by date, city, state, country, shape, duration and comments. To filter the data, the user can use the 5 available filters:
- Date
- City
- State
- Country
- Shape

These filters can be used individually or in any combination to sort the sighting data. Below, we will look at the functionality of each filter.

__Filter by Date__
>![filter_date](https://user-images.githubusercontent.com/77405273/115153248-c5594f80-a029-11eb-89de-77e9fc36e2b6.png)
- Users can enter a date in MM/DD/YYYY format to filter sighting results by a particular date. 

__Filter by City__
>![filter_city](https://user-images.githubusercontent.com/77405273/115153224-afe42580-a029-11eb-83de-28c440c11bfc.png)
- Users can enter a city name to see all sightings for that particular city. If a city in not included in our dataset, no results will be returned. 

__Filter by State__
>![filter_state](https://user-images.githubusercontent.com/77405273/115153232-b377ac80-a029-11eb-9355-2f7ad0e26c0f.png)
- Users can filter by state using the 2 letter abbreviation. All sightings for that state will be returned. 

__Filter by Coutry__
>![filter_country](https://user-images.githubusercontent.com/77405273/115153237-b83c6080-a029-11eb-9af1-3d8ed37cfbfd.png)
- Users can filter by the 2 letter country codes to sort for all sightings within one country.

__Filter by Shape__
>![filter_shape](https://user-images.githubusercontent.com/77405273/115153242-bbcfe780-a029-11eb-80c1-7dd264ae1f1e.png)
- Users can filter the data by the observed shape of the UFO.

Users can use any combination of these filters to sort the date, for example date, state and shape. 

__Sort with Multiple Filters__
>![filter_multiple](https://user-images.githubusercontent.com/77405273/115153245-be324180-a029-11eb-88f1-9a67714bc44d.png)
- Date, state and shape.


## Summary

While the webpage has increased functionailty with the added filters, users need to input values exactly as they appear in the dataset. This may lead to no results being returned, when in fact there are results matching their search criteria. Addtional improvements can be used to accept a wider range of inputs into the filters. 

### Recommendations

1. To continue developing the webpage, it would be helpful to have a map visual to show the distribution of these sightings across the world. This would allow users to see "hotpots" for sightings and look into those areas more closely. Additionally, a map visual may lead to other conclusions about sighting patterns that aren't easily drawn from the table (i.e. a correlation between location and shape). 
2. The webpage currently uses a static dataset, excluding most recent sightings. Continued development could be focused on building out the connection to live data of sightings via an API or other method. 
