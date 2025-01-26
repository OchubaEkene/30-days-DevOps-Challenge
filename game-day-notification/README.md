# 🏟️ Game Day Notification Solution  

A real-time notification system for sports enthusiasts, built using **AWS Lambda**, **SNS**, **EventBridge**, and the **Sportsdata.io API**. This project fetches live sports data and delivers notifications about game events to users, ensuring they stay updated without missing a moment.  

---

## 🚀 Features  

- **Real-Time Updates**: Get instant notifications for game events.  
- **Event-Driven Architecture**: Uses AWS services to manage events efficiently.  
- **Scalable and Cost-Effective**: Built using serverless technologies.  
- **Reliable Data Source**: Powered by the Sportsdata.io API for accurate, live sports data.  

---

## 🛠️ Tech Stack  

- **AWS Lambda**: For processing Sportsdata.io API data and executing event-driven tasks.  
- **Amazon SNS (Simple Notification Service)**: To send notifications directly to users.  
- **Amazon EventBridge**: To schedule and route events seamlessly.  
- **Sportsdata.io API**: For fetching real-time sports data.

---

## ⚙️ Architecture  

The project follows a serverless architecture:  

1. **EventBridge** triggers a scheduled Lambda function to fetch game data from the Sportsdata.io API.  
2. The Lambda function processes the data and identifies key game events.  
3. **SNS** sends notifications to subscribed users based on these events.  

---

## 🧰 Prerequisites  

Before running this project, ensure you have the following:  

- **AWS Account** with access to Lambda, SNS, and EventBridge.  
- **Sportsdata.io API Key** (sign up [here](https://sportsdata.io/)).  
- **Node.js** or **Python** installed locally for function development.  

---

Read article on https://medium.com/@alexanderochuba7/building-a-game-day-notification-solution-with-aws-lambda-sns-eventbridge-and-sportsdata-io-325dcbfbb7f7

## 🛠️ Setup  

1. Clone this repository:  
   ```bash
   git clone https://github.com/OchubaEkene/30-days-DevOps-Challenge/tree/main/game-day-notification
   cd game-day-notification
