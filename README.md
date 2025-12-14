

# EcoTrack

EcoTrack is an intelligent system designed to help users **understand, track, and reduce vehicle-based carbon emissions** with minimal manual effort.
By combining **vehicle scanning, sensor-based distance tracking, emission analytics, and personalized insights**, EcoTrack empowers individuals to make **greener travel choices effortlessly**.

This repository contains a **working prototype** developed to demonstrate the concept, architecture, and feasibility of the solution. Advanced features are part of the extended design and future scope.

 

## Problem Statement 

Most individuals are unaware of how much carbon their daily travel produces. Existing solutions either require **manual data entry**, lack personalization, or fail to translate emissions into **actionable insights**.
EcoTrack bridges this gap by **automating data capture** and converting emissions into **clear feedback and suggestions**.

 

## Key Features 

### Vehicle Scanner / Sensor Integration 

* Scans vehicle details using the mobile camera or sensors
* Automatically extracts:

  * Fuel type
  * Mileage
  * Emission factor
* Eliminates repetitive manual input

 

###  Optional OBD-II Adapter Support 

* Reads real-time vehicle data directly from the car
* Automatically captures:

  * Distance traveled
  * Ride-level activity
* Enables near **zero-interaction tracking**

 

### Mobile App Tracking 

* Simple daily travel logging
* Automatic carbon footprint calculation
* User-friendly dashboard for:

  * Daily
  * Weekly
  * Monthly emissions

 

### Emission Analytics & Categorization 

Monthly CO₂ emission levels are classified as:

* **Low:** < 90 kg CO₂
* **Moderate:** 90 – 240 kg CO₂
* **High:** 240 – 450 kg CO₂
* **Very High:** > 450 kg CO₂

Visual insights help users understand trends over time.

 

###  Personalized Eco-Suggestions 

Based on user behavior, EcoTrack suggests:

* Carpooling or public transport
* Vehicle maintenance reminders
* Route optimization
* Alternative fuel or EV recommendations

 

### Graphical Insights (Planned Extension) 

* Weekly and monthly emission graphs
* Comparative trend analysis
* Inspired by global carbon monitoring dashboards

 

### AI-Based Emission Prediction (Future Scope) 

* Predicts future CO₂ emissions based on past usage
* Uses regression / ML models
* Helps users proactively reduce emissions

 

## System Architecture 

EcoTrack consists of the following components:

###  Mobile Application 

* Scanner module (camera / sensors)
* Manual or automatic distance input
* Daily activity dashboard

### Data Processing Layer 

* Vehicle data extraction
* Carbon emission computation
* Trip history storage

### Suggestion Engine 

* Analyzes emission patterns
* Generates personalized eco-advice

### Optional OBD-II Layer 

* Real-time distance tracking
* Seamless background data collection
 

##Tech Stack 

### **Frontend (UI / Dashboard)**

* Flutter / React Native *(planned)*
* Streamlit *(for MVP dashboard)*

### **Backend**

* Python
* Flask / FastAPI

### **Database**

* SQLite / Firebase / MongoDB

### **ML & Image Processing (Future Scope)**

* OCR for vehicle document scanning
* Lightweight CNN models for recognition
* Emission prediction models

 

## Project Status 

* Core logic implemented (prototype) 
* Architecture and workflows finalized 
* UI/UX enhancements in progress 
* GPS, odometer, and AI features under development 

 

## License 

This project is open-source and intended for educational and research purposes.


