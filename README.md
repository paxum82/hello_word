# My food guide
![alt text](https://github.com/paxum82/hello_word/raw/master/mainUI.PNG "Main UI")

This program allows the user to crate a health balanced diet for a day.It allows the user to select the gender and age range and the program then give the users the options to select a variety of healthy eating patterns.
The program UI can be accessed from [here ](http://roxim.ca/foodguide/)

![alt text](https://github.com/paxum82/hello_word/raw/master/UI2.PNG "Main UI")

## Technologies
The program fetches the data from a REST API

## REST API examples
This section contains different examples of how to use the FOODGUIDE REST API, including how to query and fetch data from the API, etc. 
The REST API can be acccess from [here ](http://roxim.ca/foodguide/api/v1/foods/male/8)

Diet for 8 years old Male :

```
   /api/v1/foods/male/8
```

Diet for 23 years old Female 
```
   /api/v1/foods/female/23
```


Repeating the same query return a new set of foods that still is in agrrement with the healthy daily servings. 
The server response is in Json format.an examole of the response is shown below:

![alt text](https://github.com/paxum82/hello_word/raw/master/json.PNG "Jason Response")
