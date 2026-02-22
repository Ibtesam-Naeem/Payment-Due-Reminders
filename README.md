# SMS Payment Reminder

A simple Python script that sends SMS reminders for upcoming payments using Twilio.

This project was built to automate bill reminders while practicing working with JSON files, environment variables, and third-party APIs.

---

## Overview

The script:

- Loads payment data from a `payments.json` file  
- Checks for payments due within 3 days  
- Sends an SMS reminder using Twilio  
- Automatically updates recurring monthly payments  

---

## Features

- SMS reminders via Twilio  
- Upcoming payment detection (3-day window)  
- Monthly recurring payment support  
- Environment variable configuration using `.env`  

---

## Requirements

- Python 3.8+  
- Twilio account  

Install dependencies:

pip install twilio python-dotenv python-dateutil

---


