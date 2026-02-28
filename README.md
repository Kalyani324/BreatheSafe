<img width="1751" height="604" alt="image" src="https://github.com/user-attachments/assets/a3adb600-0c78-410a-96bf-fd5635ba790c" /><p align="center">
  <img src="./img.png" alt="Project Banner" width="100%">
</p>

##BreatheSafe 🎯

## Basic Details

### Team Name: Kalyani

### Team Members
- Member 1: Kalyani B - Mar Athanasius College of Engineering, Kothamangalam

### Hosted Project Link
[mention your project hosted link here]

### Project Description
Low-cost indoor air quality monitoring system using PPD42 Dust sensor(SHINYEI) and ESP32S which detects the PM2.5 levels real time, displays air quality trends, and automatically alerts families via Whatsapp when air becomes hazardous.

### The Problem statement
Air condition can be considered as a silent pandemic of our generation. India records over 1.7 million pr3emature deaths annuallydue to air pollution. Yet the convos are limited to outdoor pollution and government monitoring stations. But, the air inside our homes, schools and workspaces can be far more toxic than the air outside and nobody knows it's significance. Studies reveal that indoor PM2.5 levels during cooking can go upto 13 times higher than outdoor levels , with a single frying session inscreasing particle concentrations to over 500 µg/m³, against the WHO safe limit of just 15 µg/m³. Over 100 million Indian households using gas stoves and solid fuels are unknowingly exposing themselves to this invisible danger twice a day, every day. 
The most vulnerable categories are the children, pregnant women and elderly people. 
India has only 308 government air quality monitoring stations across 115 cities — measuring city-wide averages that tells nothing about the air in one's home. Existing personal air quality monitors cost ₹5,000–₹50,000, require smartphones, and are designed for Western markets — completely out of reach for the average Indian family.
There is currently no affordable, real-time, hyperlocal solution for monitoring the air that Indian families actually breathe.

### The Solution
BreatheSafe is a low-cost, real-time indoor air quality monitoring system built for homes using Shinyei PPD42 particulate matter sensor and an ESP32S microcontroller. The system continuously measures PM2.5 particle concentration every 30 seconds and transmits the data wirelessly to a live web dashboard hosted locally on a laptop via Flask ( This display on laptop is just for the prototying, instead it can be built as an app to see the logs and other details). The dashboard displays real-time PM2.5 levels, air quality status from Good to Hazardous,  WHO safe limit comparison, live trend analysis showing whether air quality is rising or falling, and a predictive forecast estimating how long before air quality reaches a dangerous threshold. When PM2.5 levels cross 55 µg/m³, an LED alert triggers automatically and the relay module activates — designed to control an exhaust fan or ventilation system in real deployment. When levels cross 150 µg/m³, an automated WhatsApp notification is instantly sent to the family member's phone via Twilio, even without internet on the sensor node. Every reading is timestamped and logged to a CSV file for long-term health record keeping. Unlike government monitoring stations that measure city-wide averages, BreatheSafe monitors the exact air a family breathes ie. in their kitchen, bedroom, or classroom at a hardware cost under ₹800.

---



### Technologies/Components Used


**For Hardware:**
- Main components:ESP32S, Dust Sensor PPD42
- Tools required: Arduino IDE, ESP 32 Board Package, Flask, Json library

---

## Features

List the key features of your project:
- Feature 1:1. Real-Time Air Quality Monitoring
Continuously measures indoor PM2.5 particle concentration every 30 seconds using the Shinyei PPD42NS sensor and displays live data on a web dashboard accessible from any device on the local network.
- Feature 2: Predictive Air Quality Forecasting: Analyzes the rate of change across recent readings to predict where air quality is heading — alerting families before air becomes dangerous rather than after, with estimated time to the next danger threshold.
- Feature 3: Automated Family Alert via WhatsApp
Instantly sends a WhatsApp notification to the family member's phone when PM2.5 crosses hazardous levels — no manual checking required, no app needed, works on any basic smartphone.


---

## Implementation

### For Hardware:

#### Components Required
ESP32S, PPD42 Dust Sensor


#### Screenshots (Add at least 3)

![![<img width="1869" height="838" alt="Screenshot 2026-02-28 094500" src="https://github.com/user-attachments/assets/ee44a8ba-5601-4dc9-a0e0-71335348783f" />
]()
]
*This is the website hosted*

![<img width="1751" height="604" alt="Screenshot 2026-02-28 094511" src="https://github.com/user-attachments/assets/d9e19ac1-aa91-47d2-af3a-c6109295b13a" />
]
*Shows the trends of air quality monitored*


### For Hardware Projects:


**Total Estimated Cost:** ₹[800]



#### Demo Output


## Project Demo

### Video
[]

*Explain what the video demonstrates - key features, user flow, technical highlights*



## Team Contributions

- [Kalyani B]: [Full hardware and software]

---

---

Made with ❤️ at TinkerHub
