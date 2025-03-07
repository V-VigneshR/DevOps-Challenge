# Weather Dashboard Project – DevOps Challenge (Week 1)

## Project Overview

As part of a hands-on DevOps challenge, I developed a weather dashboard utilizing the OpenWeather API and AWS S3 for data storage. This project focused on setting up an environment, collecting real-time weather data, transforming and structuring it, and then securely storing the data in AWS S3 as JSON files.

## Key Components

### 1. **OpenWeather API**
   - Integrated weather data collection using the free OpenWeather API.
   - Ensured the system retrieves accurate, real-time weather information for various locations.
   
### 2. **AWS S3**
   - Leveraged **AWS Simple Storage Service (S3)** for secure and scalable storage of collected weather data.
   - Stored data in **JSON format** to ensure structured and easily retrievable information.

### 3. **Python & DevOps Practices**
   - Wrote Python scripts to manage the API requests, data transformation, and storage processes.
   - Followed best practices for:
     - **Version control** using **Git**.
     - **Environment setup** for secure handling of AWS and API credentials.
     - Structured the project for scalability and easy maintenance.

## Project Workflow

1. **Weather Data Collection**: The system makes API requests to OpenWeather to gather real-time weather information based on user input or pre-configured cities.
2. **Data Transformation**: The data received from the API is then transformed and structured into a standardized JSON format.
3. **Data Storage in AWS S3**: The structured weather data is uploaded to an **AWS S3 bucket** for secure and scalable storage, where it can be accessed for future use or analysis.



