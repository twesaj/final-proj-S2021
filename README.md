# TWESA MWAISEMBA 
# FINAL PROJECT

# SCRIPT 1
This script extracts the 5-day weather forecast using the user’s choice of place by using the  latitude and longitude  from the National Weather Service website using the BeautifulSoup Library. The script provides the user with the input option for the latitude and longitude of a particular location, using the input() function.

First, The script used the latitude and longitude values for Worcester, Massachusetts. The code converted the latitude and longitude values for Worcester, Ma to strings to generate the URL for that area. The script returns an output of a five-day weather forecast for Worcester, Massachusetts. 

Second, I decided to make the weather data presentable by string manipulation. I used spaces and commas in the list. I also used the replace () function to separate words such as “SunnyHigh” to “Sunny High. To capitalise the letters in the data, I used the .upper() function. The outputs include the URL of the desired weather forecast and the 5-day forecast. 

This script was very easy to do, as it was very similar to a lab I have completed in week 4.

# SCRIPT 2

This script creates a chatbot that calculates the BMI based on the user’s height and weight input. The script allows the user to  know their BMI according to the resulting calculations, and furthermore whether they are underweight, healthy,overweightand obese. 

For this script, I created a simple chatbot based on decision trees that look for specific keywords using both input() function to capture input from the user and if, elif, else statements to respond to the user by taking the input numbers and returning them into string values after calculation.

The first part of the script uses the input() function to communicate with the user and get inputs for the BMI calculation.

First, As this is a chatbot, I included an introductory and greeting component to script. The chatbot asks the user for their name and responds with a greeting and letting the user know they are about to check their BMI.

Second, the chatbot provides input boxes that lets the user respond with their height, followed by weight that they want to calculate for the BMI. 

Third, I included a function in the script that calculates the BMI based on the user’s measurement input while also rounding up the result > BMI = round(weight / (height/100)**2)

Fourth, a print statement that tells the user their BMI. It bases this on the result of the calculation entered by the user in the above three steps.

Last, The second part of the script comes to play using the if,elif and else statements to return a statement based on the BMI results. I added four BMI categories to underweight, healthy, overweight and obese. The if statement checks to see whether the variable value for BMI meets the condition set and if they do the return statements according to the categories.

The output result is the numeric result of the calculation in the output unit selected by the user and the health category statement. However, if the input entered by the user does not fit the category; for example, if the user inputs a word or letter which is impossible to calculate the BMI, the program will report missing data, try again.

The script ran as I expected, though I would have liked to have tried including more health indicators for a more complex chatbot and possibly have the age component relate to the BMI return result itself. I had difficulties in using the operators. I wanted to include a range function for my BMI values and the boolean operators but encountered errors regarding ‘int’ and ‘string’ system errors while this would be easy to resolve, I found I can just use the boolean operators for a cleaner look on the code.
