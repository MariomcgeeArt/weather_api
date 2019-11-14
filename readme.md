Describe the data contained in the API response. What can we discern about the weather in the specified city?

#the data returned looks to be json data dictionaries containg valuse for the citys infrmation reguarding base information about weather, timezone, and a city ID etc.






How would we obtain the temperature in the specified city? Describe using Python dictionary syntax. (HINT: Assume that the JSON response is stored in a variable called json_response.)

temp = json_response['main']['temp']

temp = json_response.get('main').get('temp')




