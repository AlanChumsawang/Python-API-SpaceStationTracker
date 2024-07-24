ISS Overhead Notification System


This Python script notifies you via email when the International Space Station (ISS) is overhead and it is dark outside at your location. This is achieved by periodically checking the ISS's current position and the local sunrise/sunset times.



Techniques

API Integration: Demonstrated by fetching data from the Open Notify API and Sunrise-Sunset API to determine the ISS's position and local sunrise/sunset times.

Automated Email Sending: Implemented using the smtplib library to send email notifications when specific conditions are met.

Conditional Logic and Looping: Used to periodically check conditions and execute actions based on real-time data.
