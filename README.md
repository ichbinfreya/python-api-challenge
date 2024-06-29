# API project
During my project, I used the GitBash to git clone the repository from GitHub to the local computer.
 
  git clone HTTPS

For README, the command was:

  touch README.md
  
  echo "# API project" > README.md
  
  git add README.md
  
  git commit -m "Add README.md"

I created a folder in the local python-api-challenge folder:
 
  mkdir WeatherPy

And then I created api_keys, WeatherPY and VacationPy:
  touch WeatherPy/api_keys.py
  touch WeatherPy/WeatherPY.ipynb
  touch WeatherPY/VacationPy.ipynb

For the api_keys.py, I don't want it to be accessible to the public. So I created .gitignore:
  echo "WeatherPy/api_keys.py" > .gitignore
  git add .gitignore
  git commit -m "Add .gitignore"

  git push origin main

I would like to copy the edited file from the Starter_code to my challenge folder:
  cp C:/Users/freya/BOOTCAMP/Starter_Code/VacationPy.ipynb C:/Users/freya/BOOTCAMP/python-api-challenge/WeatherPy/
  git add WeatherPy.ipynb
  git push origin main

  
