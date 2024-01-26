# Rain Forecast Detection and Reminder Project

## Overview

This project leverages the OpenWeatherMap API to provide accurate and timely rain forecasts for the next 12 hours. It checks for rain or storm conditions and uses the Twilio API to send SMS reminders to users at 7 AM, ensuring they are well-prepared for the day's weather. Whether it's a quick shower or an impending storm, this project helps users stay informed about weather conditions and remember their umbrellas.

## Features

> OpenWeatherMap Integration: Utilizes the OpenWeatherMap "onecall" API to retrieve detailed weather forecasts for the next 12 hours.
> Rain Detection: Analyzes weather conditions to determine if there will be any rain or storms during the specified period.
> Twilio SMS Reminder: Sends personalized SMS messages via Twilio to user phones at 7 AM, reminding them to prepare for the day's weather.

## How it Works

### Weather Forecast:
Connects to the OpenWeatherMap API to fetch detailed hourly weather forecasts.
Analyzes the forecast data to determine the likelihood of rain or storm conditions.
### Twilio SMS Reminder:
Uses the Twilio API to send SMS reminders to users at 7 AM.
Personalized messages inform users about expected rain, encouraging them to carry an umbrella.

## Getting Started:
1. Clone the Repository
2. Set Up Environment:
   >Obtain API keys for OpenWeatherMap and Twilio.
   >Set environment variables for OWM_API_KEY, AUTH_TOKEN, https_proxy, YOUR ACCOUNT SID, YOUR TWILIO VIRTUAL NUMBER, and YOUR TWILIO VERIFIED REAL NUMBER.
3. Install Dependencies:
   >pip install -r requirements.txt
4. Run the Script:
   >python rain_forecast_reminder.py


## Contributions

Contributions are welcome! Feel free to fork the repository, make improvements, and submit pull requests.

## Acknowledgments

-OpenWeatherMap: Providing accurate and detailed weather data.
-Twilio: Enabling SMS notifications for timely reminders.


For questions or inquiries, please contact Priyanka Negi (negip105@gmail.com).

