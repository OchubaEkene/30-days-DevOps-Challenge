🌦️ 30 Days DevOps Challenge 

🌟 Weather Dashboard
  
Day 1: Building a Weather Data Collection System using AWS S3 and OpenWeather API 🌍☁️


The Weather Data Collection System is designed to:

Fetch real-time weather data for multiple cities 🌆

Store the weather data securely in AWS S3 🌐

Track historical weather data using timestamps 🕒

Integrate with the OpenWeather API 🌥️

Follow DevOps principles such as Infrastructure as Code and Environment Management 🛠️

By building this system, I’m applying key DevOps concepts and automation in the cloud.

🛠️ Features
Here are some cool features of the system:

Real-time Weather Fetching: Automatically collects weather data (temperature, humidity, and conditions) from multiple cities 🏙️🌡️

AWS S3 Integration: Stores weather data in AWS S3 for long-term storage and easy access 💾

Timestamps: Each data point is timestamped for historical tracking 🕰️

Supports Multiple Cities: Track weather for various cities 🌍

🖥️ Technical Architecture

Language: Python 3.x 🐍

Cloud Provider: AWS (S3) 🌩️

External API: OpenWeather API 🌤️

Dependencies: boto3 (AWS SDK) 📦
python-dotenv 🔐
requests 🌐

🗂️ Project Structure
The project is organized as follows:

📜 Setup Instructions
Ready to get started? Here’s how to set up the project on your machine:

Clone the repository:
- bash
- Copy
- Edit
- git clone (https://github.com/OchubaEkene/30-days-DevOps-Challenge)

Install dependencies:
- bash
- Copy
- Edit
- pip install -r requirements.txt

Configure environment variables (.env): 
Add the following environment variables in your .env file:
- env
- Copy
- Edit
- OPENWEATHER_API_KEY=your_api_key
- AWS_BUCKET_NAME=your_bucket_name

Configure AWS credentials: Run aws configure to enter your AWS access key and secret access key.

Run the application:

- bash
- Copy
- Edit
- python src/weather_dashboard.py
