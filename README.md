# IoT Temperature Monitoring System

## Overview
This project demonstrates an IoT-based temperature and humidity monitoring system built with **Microsoft Azure**.  
It simulates real-time sensor data using the **Raspberry Pi Web Simulator**, processes it via **Azure Stream Analytics**, stores results in **Blob Storage**, and sends alerts using **Azure Monitor** when temperature exceeds safe limits.

## Azure Services Used
- **Azure IoT Hub** – Receives and manages device telemetry from simulated IoT sensors.  
- **Azure Stream Analytics** – Processes incoming data in real time using SQL-like queries.  
- **Azure Blob Storage** – Stores processed data as JSON for long-term analysis.  
- **Azure Monitor + Action Group** – Sends email notifications for threshold breaches.  

## Architecture
**Data Flow:**  
Raspberry Pi Simulator → IoT Hub → Stream Analytics → Blob Storage → Azure Monitor Alerts  

## Files Included
- `app.js` – Main Node.js script used in the IoT simulator.  
- `/screenshots` – Proof of Azure setup (IoT Hub, Stream Analytics, Blob Storage, Alerts).  
- `Cost_Analysis.xlsx` – Estimated monthly Azure cost breakdown.  
- `architecture-diagram.png` – System architecture flow.  

## Cost Analysis
| Azure Service | Pricing Tier | Est. Monthly Cost |
|----------------|--------------|-------------------|
| IoT Hub | Free Tier | $0.00 |
| Stream Analytics | 1 Streaming Unit | $81.30 |
| Blob Storage | Standard (Hot LRS) | $21.84 |
| Azure Monitor | Free | $0.00 |
| **Total** |  | **$103.14 (approx.)** |

## Author
**Name:** Kavya Dhawan  
**Student ID:** 154150239  
**Course:** CSP451 – Week 9 Azure Demo  

## Demo Video
🔗 [Unlisted YouTube Link](https://www.youtube.com/your-demo-link)


