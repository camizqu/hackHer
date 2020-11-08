# hackHer
App development for Covid Care, an app that tracks long term health effects of those who have contracted COVID-19. The user logs their daily health and can monitor their symptoms on a daily, weekly, or monthly basis.


## Baseline Profile
When getting started with the app, there will be a baseline profile set up by taking user input. This includes data such as name, weight, height, gender, and race.

## Analytics Page
This shows the weekly analytics for the user. 

Measurable content such as heartrate, weight, blood oxygen levels, and temperature are shown through a line graph.

Summaries for relative content such as severity of headaches, coughing, fatigue, and joint pain are given through statements

## Logging Page
Allows user to give health symptom input. A GUI (preferably Tkinter) would be used to actualize this.

Measurable content is available for direct input (inputting value).

Relative content is inputted on scale buttons such as "No coughing", "Slight Coughing", "Extreme Coughing"

## Calendar Page
Shows a monthly calendar to the user.

Depending on the health symptom input on the given day, the calendar day will be changed to a colour to indicate the health level of the user.

For example, if the user's health is is excellent that day, on the calendar it will show green. Alternatively, if the user's health is bad, it will show red.
There are four tier colours from great to bad: green, yellow, orange, red.

## Resources Page
News portion that relays headlines related to COVID-19 at the time it is run. Created using NewsCast API.

Nearby hospitals that uses Google Places API to return all hospitals within a 100km radius of the inputted latitude and longitude.
(Currently produces an error because the API uses paid content)
