Project 'Sस्य-Carbon' (Syasya-Carbon)
A Scalable Digital MRV Framework for India's Smallholder Carbon Economy

(https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
(https://img.shields.io/badge/Status-Functional%20MVP-success.svg)](./)

Table of Contents
(#problem-statement)

(#our-solution-the-hybrid-dmrv-model)

(#prototype-demonstration)

(#technology-stack)

Key Features & Functionality

Compliance & Methodology

Project Architecture

License

Problem Statement
The voluntary carbon market presents a significant opportunity for climate action, but it remains largely inaccessible to the most critical stakeholders in Indian agriculture: the smallholder farmers. Traditional Monitoring, Reporting, and Verification (MRV) systems are prohibitively expensive, complex, and ill-suited for India's fragmented agricultural landscape, where 86.1% of farmers are small and marginal, owning less than two hectares of land. This high cost of entry systematically excludes the very farmers who are essential for scaling nature-based solutions like agroforestry and sustainable rice cultivation.   

Our Solution: The Hybrid dMRV Model
'Sस्य-Carbon' (Syasya-Carbon) is a digital MRV (dMRV) platform designed from the ground up to solve this challenge. Our key innovation is a Hybrid dMRV Model that fuses high-tech automation with human-centric validation.   

High-Tech Automation: We leverage publicly available satellite imagery (e.g., Harmonized Landsat & Sentinel-2) and an AI/ML engine to provide continuous, low-cost monitoring of vast agricultural areas. This provides the scale.   

Human-Centric Validation: A simple, offline-first, vernacular mobile app empowers farmers and local field agents to capture targeted, geo-tagged ground-truth data (e.g., photos of newly planted trees, water levels in rice paddies). This provides the trust and accuracy.

This hybrid approach, inspired by successful last-mile data networks, drastically reduces verification costs by up to 70%, accelerates credit issuance by months, and builds a transparent, auditable data trail that enhances the integrity of the carbon credits generated.   

Crucially, our farmer-facing app is not just a data collection tool. It provides immediate, tangible value through features like hyperlocal weather forecasts and AI-powered pest alerts, driving consistent user engagement and ensuring a steady flow of high-quality data.   

Prototype Demonstration
We have developed a high-fidelity, interactive prototype to demonstrate the end-to-end functionality of our platform.

▶️ Interactive Figma Prototype: Click here to explore the full user journey

This prototype showcases the mobile app flow for a field agent onboarding a farmer and recording an agroforestry activity, and the corresponding web dashboard for a project manager to verify the data and view AI-driven insights.

🎥 Video Walkthrough: ****

This video provides a guided tour of the prototype, explaining the core features and the value proposition of our hybrid dMRV model.

Technology Stack
Our platform is built on a modern, scalable, and robust technology stack designed for the realities of rural India.

Layer	Component	Technology / Source
Data Acquisition	Remote Sensing	
Harmonized Landsat & Sentinel-2 (HLS), ISRO Bhuvan, PlanetScope (Commercial)    

Mobile App	
Flutter (for cross-platform compatibility), Firebase (for real-time DB & offline sync)    

IoT (Future)	
Low-cost soil sensors, smart water meters    

Processing & Analytics	Cloud & GIS	
AWS/Azure, Python, Google Earth Engine API, GDAL, Rasterio    

AI/ML Engine	Scikit-learn, TensorFlow/PyTorch; Models: Random Forest, XGBoost for SOC/Methane estimation
Verification & Ledger	Human-in-the-Loop	Web Dashboard (React/Angular or Streamlit for MVP)
Immutable Ledger	
Hyperledger Fabric (Conceptual for auditability and transparency)    

User Interface	Design	Figma (for interactive prototyping)
Mobile	Flutter
Web	React / Streamlit
Key Features & Functionality
For Farmers & Field Agents (Mobile App):

Offline-First Functionality: Map farms and capture data without an internet connection.

Simple Evidence Capture: Geo-tag and time-stamp photos/videos as verifiable proof of practice.

Value-Added Services: Drive engagement with daily hyperlocal weather forecasts and AI-powered pest alerts.   

For Project Aggregators (Web Dashboard):

Geospatial Monitoring: Visualize all project farms on an interactive map with satellite data overlays.

Data Validation: Review and validate ground-truth data submitted from the field.

Automated Reporting: Generate audit-ready reports compliant with international standards.

For Auditors & Registries:

Digital Audit Trail: Secure, read-only access to a complete and transparent data history for every credit.   

Immutable Records: DLT-based ledger ensures data integrity and prevents double-counting.   

Compliance & Methodology
'Sस्य-Carbon' is designed to be fully compliant with leading international carbon standards, ensuring the generation of high-integrity, high-quality carbon credits.

Agroforestry Projects: Our workflow aligns with Verra's VM0047 (Afforestation, Reforestation, and Revegetation), specifically the "census-based approach" which is ideal for dispersed smallholder plantings like agroforestry.   

Rice Cultivation Projects: Our platform supports Gold Standard's "Methodology for Methane Emission Reduction by Adjusted Water Management Practice in Rice Cultivation," including its simplified approach for small-scale projects.   

Project Architecture
Detailed diagrams illustrating our technical architecture and data flow are available in the /architecture folder of this repository.

technical_architecture.png: A high-level overview of the cloud services, databases, and microservices.

data_flow_diagram.png: A visual representation of the data journey from the farmer's mobile device to the final verified carbon credit.

License
This project is licensed under the MIT License. See the LICENSE file for details.
