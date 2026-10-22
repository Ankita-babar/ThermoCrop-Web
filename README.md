ThermaCrop 🌱❄️

ThermaCrop is a smart cold storage monitoring platform built for farmers. It tracks storage conditions like temperature and humidity and shows the quality of stored crops (tomato and apple) on a live dashboard. It also connects farmers directly with retailers, so they can sell produce without middlemen.

Problem

Farmers lose a large share of their produce to spoilage because they can’t monitor storage conditions or know the quality of their stored crops. They also depend on intermediaries to find buyers.

Solution

ThermaCrop combines sensor-based monitoring, ML-based quality grading, and a marketplace in one web platform.

Key Features
Live dashboard with temperature, humidity, and gas readings, shown as graphs
ML crop quality grading for tomato and apple (e.g. Grade A/B/C)
Separate farmer and retailer logins, with input validation
Farmer registration with a unique storage machine number (format TC-1080), one machine per farmer, plus location
Marketplace where retailers browse available crops
Controlled access: retailers can’t see farmer data directly and must send a contact request
Farmer inputs such as crop weight, with grade and storage status as output
Profile section with location details
Tech Stack
Frontend: HTML, CSS, JavaScript, Bootstrap, jQuery
ML: Python model trained on temperature, humidity, and gas data
Hardware (planned): ESP32 with temperature, humidity, and gas sensors
Backend and database: planned or in progress, depending on your current build
Project Status

This is a frontend prototype with dummy data. Real sensor integration, backend, and live ML predictions are planned as the next phase.

Future Scope
Real-time data from ESP32 sensors
Support for more crops
SMS/email alerts when storage conditions go out of range
OTP-based verification for contact requests
Price prediction and demand insights
