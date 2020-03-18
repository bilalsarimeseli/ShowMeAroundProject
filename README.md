# Showmearound
Show Me Around App Will Provide Preliminary Tour Guidance and Information About Places Being Visited
 
# Contributors: 
    codifyme, bilalsarimeseli, nanotelegram, nazim806;

# Summary
    This project provides a simple user interface application enabling users to search their favorite places, e.g. cities, using a search engine (or google map). The search engine will render relevant pictures to the searched topic and help a user get a gernal idea about the cities their are visiting. Also a user gets the current weather infomation. 
    
# Live Link
[Click here!](https://bilalsarimeseli.github.io/ShowMeAroundProject/)

# Screenshots from Berkeley

![weather](https://github.com/bilalsarimeseli/ShowMeAroundProject/blob/master/Screen%20Shot%202020-03-17%20at%2010.32.22%20PM.png?raw=true)
----------------------
![Berkeley](https://github.com/bilalsarimeseli/ShowMeAroundProject/blob/master/Screen%20Shot%202020-03-17%20at%2010.32.56%20PM.png?raw=true)

# API Documentations & Sources 
    1. Unsplash.com        => https://unsplash.com/developers
    2. Pixabay.com         => https://pixabay.com/api/docs/
    3. Openweathermap.com  => https://openweathermap.org/api
    4. Google Map          => https://developers.google.com/maps/documentation/
    
# Pseudo Code Summary 
    1. Connect to: 
        a. Google Map API 
        b. Unsplash API 
        c. AccuWeather
    2. Build a search engine
        User searches the name of the city 
            a. app will display the location on the Google Map 
            b. app will render all relevant pictures relevant to the city name 
            c. app will diplsay current weather on the city 
        (note: if possible, locate users by their geolocation or IP and display pictures and weather). Use "LocateMe" button for this feature. 

# Pseudo Code For API responses and Table Content 
    1. Display Pictures 
    2. Assign object responses to Icons 
