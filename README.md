# International Space Station (ISS) Tracker and Notifier

This Python script tracks the International Space Station (ISS) and sends you an email notification when the ISS is overhead during nighttime at your specified location. It uses the Open Notify API to get the current ISS position and the Sunrise-Sunset API to determine if it's nighttime at your coordinates.

# Features

- Tracks the ISS in real-time using the Open Notify API.
- Checks if the ISS is overhead within a ±5 degree latitude and longitude range.
- Determines if it's nighttime at your specified location using the Sunrise-Sunset API.
- Sends an email notification when the ISS is overhead during nighttime.

# Configuration

Before running the script, you need to configure it with your email credentials and geographical coordinates:

- Replace `MY_EMAIL` with your Gmail address.
- Replace `MY_PASSWORD` with your Gmail password (you may want to use an [App Password](https://support.google.com/accounts/answer/185833?hl=en) for security).
- Set `MY_LAT` to your latitude.
- Set `MY_LONG` to your longitude.


Enjoy tracking the International Space Station and receiving notifications when it passes overhead during nighttime! If you encounter any issues or have suggestions for improvements, please don't hesitate to report them.
