# 📌 Overview

The **Ocean Region Vessel Monitoring System (ORVMS)** is a centralized, web-based command and control platform designed to support real-time maritime surveillance, vessel monitoring, threat detection, and operational decision-making across vast maritime domains.

This project simulates the core principles and functional architecture used by modern maritime forces such as the Indian Navy and Indian Coast Guard, where data from multiple sources is fused into a single operational picture to enhance maritime domain awareness (MDA).

The system integrates geospatial intelligence, vessel tracking, automated alert generation, data persistence, and multi-source information ingestion into a unified command interface.

---

# 🎯 Project Objectives

The primary objectives of this **Ocean Region Vessel Monitoring System (ORVMS)** are:

* To provide a real-time operational picture of maritime activities.
* To track, classify, and monitor vessels within and around Indian maritime boundaries.
* To detect suspicious behaviour and generate automated alerts.
* To support decision-making for interception, patrol, and surveillance.
* To demonstrate a centralized command & communication model used in naval and coast guard operations.
* To simulate data fusion from heterogeneous sources (manual input, documents, OCR, logs).

---

# 🧠 Conceptual Background

Modern maritime security operations rely on:

* AIS & non-AIS vessel tracking.
* Coastal radar chains.
* Aerial and surface patrol reports.
* Intelligence & surveillance logs.
* Centralized command centres.

This project models the software backbone of such systems, focusing on:

* Data fusion.
* Geospatial analysis.
* Threat assessment.
* Persistent situational awareness.

---

# 🧩 Key Features

## 🔐 Secure Command Access

* Login-based access simulating restricted command centre entry.
* Role-based operational interface.
* Persistent session-based data storage.

---

## 🗺️ Interactive Maritime Map

* Real-time interactive map using Leaflet.

Visualization of:

* Indian maritime boundaries (East & West).
* Vessel positions.
* Patrol areas.
* Exercise zones.
* Piracy-prone regions.
* Security checkpoints.

Layer-based toggling for operational clarity.

---

## 🚢 Vessel Tracking & Classification

* Manual and automated vessel ingestion.

Vessel attributes:

* Position (Lat/Lon).
* Speed & course.
* Vessel type.
* Flag inference.
* Friendly vs unidentified classification.

Real-time tracking and zoom-to-target functionality.

---

## 📊 Operational Dashboard (Command Overview)

Key Performance Indicators (KPIs):

* Total vessels.
* Friendly vessels.
* Suspicious vessels.
* Active alerts.

Includes:

* Mini-map overview.
* Recent alerts feed.
* Active vessel summary.
* System health indicators.

---

## 🚨 Automated Threat Detection & Alerts

The system automatically generates alerts based on:

* High-speed unidentified vessels.
* Entry into restricted patrol or exercise zones.
* Piracy-zone presence.
* Predicted maritime boundary violation.
* Collision risk detection.
* Trajectory-based future movement prediction.

Each alert includes:

* Priority level (Medium / High).
* Location.
* Timestamp.
* Source.
* Associated vessel(s).

---

## 🧭 Trajectory Prediction & Boundary Analysis

Predicts future vessel movement based on:

* Speed.
* Course.
* Time window.

Detects:

* Boundary crossings.
* Intersections with maritime limits.

Recommends nearest naval or coast guard asset for interception with ETA estimation.

---

## 📁 Multi-Source Data Ingestion

Supports ingestion of operational data from:

* Text & Markdown reports.
* CSV & Excel files.
* DOCX documents.
* PDFs & scanned images (OCR using Tesseract).
* JSON-based operational area definitions.
* Manual vessel input forms.

This simulates real-world intelligence fusion from diverse maritime reporting channels.

---

## 🧠 Text Intelligence Processing

Extracts structured vessel data from unstructured surveillance logs.

Automatically parses:

* Coordinates (DMS formats).
* Vessel identity.
* Speed & heading.
* Operational context.

Converts raw reports into actionable data.

---

## 💾 Persistent Data Storage

Uses IndexedDB for offline-capable persistence.

Data survives browser reloads.

Supports:

* Data export (TXT / CSV).
* Data import.
* Backup & restore.
* System refresh.

---

## 🗂️ Data Management Module

* System-wide statistics.
* Exportable operational datasets.
* Manual data import.
* Full system reset (with confirmation).

---

# 🛠️ Technology Stack

* Frontend: HTML5, CSS3, JavaScript.
* Mapping & GIS: Leaflet.js, OpenStreetMap.
* Data Storage: IndexedDB.
* OCR: Tesseract.js.
* File Parsing: Mammoth.js, SheetJS (XLSX).
* Icons: Font Awesome.

---

# 🧪 Use-Case Scenarios

* Coastal surveillance simulation.
* Naval & coast guard training demonstrations.
* Defence technology academic projects.
* Maritime security research.
* Hackathons & innovation challenges.
* Command-and-control system prototyping.

---

# ⚠️ Disclaimer

This project is a simulation and academic implementation inspired by publicly known principles of maritime surveillance systems.

It does not use classified data, real military feeds or operational intelligence and does not represent any official system currently deployed by defence forces.

---

# 🚀 Future Enhancements

* AIS feed simulation.
* Role-based access control.
* AI-based threat scoring.
* Satellite & UAV integration models.
* Real-time communication overlays.
* Backend API integration.
* Multi-command synchronization.

---

# 👨‍💻 Author

**Sharath Y Kudachi**
Computer Science & Engineering Student 
BMS Institute of Technology & Management 

📜 License

This project is licensed under the **MIT License**.

You are free to use, modify, and distribute with proper attribution.

⭐ Support

If you found this project useful:

⭐ Star the repository  
🍴 Fork and build your own version  
📢 Share with others interested in defence technology and military history

Developed as an advanced **Ocean Region Vessel Monitoring System (ORVMS)** project to demonstrate system design, geospatial intelligence and defence-oriented software architecture.
