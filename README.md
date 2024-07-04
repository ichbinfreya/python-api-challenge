# API project

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

  
