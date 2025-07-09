# ML-Integrated-IoT-Smart-City-Inventory-Management-System


An IoT and Machine Learning-based smart inventory management platform designed to automate stock tracking, demand forecasting, and environmental monitoring for small and medium retailers, warehouses, and smart city supply chains. The system uses ESP32 microcontrollers, a network of sensors, and predictive models to minimize operational expenses, reduce waste, and improve supply chain efficiency.

---

## 🚀 Features

✅ **Real-Time Inventory Tracking**  
Monitor stock levels, temperature, and security conditions continuously using IoT sensors.

✅ **Automated Demand Forecasting**  
Predict inventory requirements with ARIMA and LSTM models to optimize restocking.

✅ **Security and Environmental Alerts**  
Trigger real-time notifications for motion detection and temperature anomalies.

✅ **User-Friendly Dashboard**  
Visualize inventory status and trends via a responsive web dashboard.

✅ **Scalability & Cost-Effectiveness**  
Designed to be affordable for SMEs while supporting future expansion to larger facilities.

---

## 🏗️ System Architecture

- **IoT Layer:**  
  - *ESP32 microcontroller* collects sensor data.
  - Load cells measure weight (stock levels).
  - PIR sensors detect unauthorized access.
  - DHT11 sensors monitor temperature.

- **Communication Layer:**  
  - ESP32 sends data via Wi-Fi.
  - PHP-based REST APIs handle incoming data.

- **Data Storage:**  
  - MySQL database stores real-time and historical records.

- **Processing & Forecasting:**  
  - ARIMA and LSTM models analyze consumption trends.
  - Automated ordering logic triggers restocking recommendations.

- **Visualization & Alerts:**  
  - Web dashboard (HTML/CSS/JavaScript) displays data.
  - Email/SMS notifications for critical events.

---

## 🎯 Objectives

1. **Real-Time Inventory Tracking**
   - Develop an IoT sensor network with load cells, PIR, and DHT11 sensors.
   - Use ESP32 microcontrollers to wirelessly transmit data.

2. **Automated Demand Forecasting**
   - Implement ARIMA & LSTM models to predict demand.
   - Automate restocking recommendations.

3. **Security & Environmental Monitoring**
   - Detect unauthorized access and temperature drift in real time.

4. **User-Friendly Dashboard**
   - Provide real-time visualization and alerts.

5. **Scalability & Cost-Effectiveness**
   - Keep the system affordable and modular.

6. **Data-Driven Decision Making**
   - Enable long-term analytics and reporting.

---

## 🛠️ Technologies Used

- **Hardware:** ESP32, Load Cells, DHT11 Sensors, PIR Motion Sensors
- **Backend:** PHP, MySQL
- **Frontend:** HTML, CSS, JavaScript
- **Machine Learning:** Python (ARIMA, LSTM)
- **Notifications:** Email Integration(PHPMailer)



