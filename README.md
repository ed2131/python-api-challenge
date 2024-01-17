## Weather and Vacation Analysis

## Overview

This project consists of two primary components: WeatherPy and VacationPy. The goal is to conduct a comprehensive analysis of weather data from cities around the globe and leverage this information to identify optimal vacation destinations.

### Part 1: WeatherPy

#### Description

In the WeatherPy section, we analyze the weather patterns of 598 randomly selected cities situated at various distances from the equator. This analysis is facilitated through Python, utilizing the citipy library and the OpenWeatherMap API. The focus is to develop a comprehensive understanding of the weather variations across these cities.

#### Requirements Fulfilled

- **Requirement 1**: Generation of scatter plots that illustrate the relationships between various weather variables and latitude.
  
- **Requirement 2**: Execution of linear regressions for each identified relationship, categorizing the plots based on the Northern and Southern Hemispheres.

#### Findings

A detailed explanation follows each set of plots, interpreting the implications of the linear regressions, identifying key relationships, and highlighting significant observations.

### Part 2: VacationPy

#### Description

In the VacationPy segment, we utilize Python, the geoViews library, and the Geoapify API to pinpoint and visualize ideal vacation spots based on predefined weather conditions.

#### Requirements Fulfilled

- Created an interactive map showing points for each city in the `city_data_df` DataFrame, with point sizes indicative of humidity levels.
  
- Applied filters to the DataFrame to isolate cities with ideal weather conditions.
  
- Established a new DataFrame, `hotel_df`, incorporating city names, countries, coordinates, and humidity data.
  
- Integrated the Geoapify API to locate the nearest hotel within a 10,000-meter radius of each city's coordinates.
  
- Enhanced map interactivity by including hotel names and country information in the hover tooltip for each city.

This comprehensive analysis and interactive visualization provide valuable insights for planning vacations in cities with favorable weather conditions.
