# API project
In this project, we introduced API. The WeatherPy used the OpenWeatherMap API to retrieve weather data from the cities list. I created linear regression graph to compare various factors that can be affected by the lattiude bewtten Northern Hemisphere and Southern Hemisphere, while VacationPy used the geoViews Python library and the Geoapify API to create map visualisations.

## Set up for Git Clone and Create a folder & files
''' bash
git clone HTTPS
  touch README.md
  echo "# API project" > README.md
  git add README.md
  git commit -m "Add README.md"
  mkdir WeatherPy

## Create api_keys, WeatherPY and VacationPy
  touch WeatherPy/api_keys.py
  touch WeatherPy/WeatherPY.ipynb
  touch WeatherPY/VacationPy.ipynb

## Make api_keys unaccessible to the Public
  echo "WeatherPy/api_keys.py" > .gitignore
  git add .gitignore
  git commit -m "Add .gitignore"
  git push origin main

## Copy the Sarter_Code .ipynb to New Place
  cp C:/Users/freya/BOOTCAMP/Starter_Code/VacationPy.ipynb C:/Users/freya/BOOTCAMP/python-api-challenge/WeatherPy/
  git add WeatherPy.ipynb
  git push origin main

  
