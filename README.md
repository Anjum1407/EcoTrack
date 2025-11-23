# EcoTrack
EcoTrack is an intelligent system designed to help users understand, track, and reduce their vehicle-based carbon emissions. By combining vehicle scanning, automatic data extraction, and real-time emission calculation, EcoTrack empowers individuals to make greener travel choices with zero complexity.

**Features:**

1. Vehicle Scanner / Sensor Integration

2. Extracts key vehicle details automatically

3. Removes the need for manual input (fuel type, mileage, emission factor)

**Optional OBD-II Adapter Support**

1. Reads real-time vehicle data

2. Automatically captures distance traveled after every ride

**Mobile App Tracking**

1. Users update their daily travel activity

2. Carbon footprint calculated instantly

3. Personalized suggestions to reduce emissions

**Emission Categorization**

Low: < 90 kg CO₂/month

Moderate: 90–240 kg CO₂/month

High: 240–450 kg CO₂/month

Very High: > 450 kg CO₂/month

**Eco-Suggestions**

1. Carpooling or public transport

2. Maintenance reminders

3. Route optimization

4. Alternative fuel recommendations

**System Architecture**

_EcoTrack consists of the following components:_

1. Mobile App

    Scanner module

    Manual or automatic distance entry

    Daily logging dashboard

2. Data Processing Layer

    Extracts vehicle details

    Computes carbon emissions

    Stores trip history

3. Suggestion Engine

    Evaluates emission patterns

    Generates personalized advice

4. Optional OBD-II Layer

    Real-time distance tracking

    Seamless user experience

**Tech Stack**

**_Frontend (App UI)_**

Flutter / React Native, Flask (Python) or FastAPI (Python)

Camera API (for scanning)

**_Backend_**

Python

Flask / FastAPI

SQLite / Firebase / MongoDB

ML / Image Processing (Future Scope)

OCR (for scanning RC details)

Lightweight CNN models
