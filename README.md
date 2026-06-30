# SmartCity Sentiment Intelligence Platform

An AI-powered data intelligence platform designed for municipal corporations to monitor, evaluate, and act on citizen issues in real-time. This project leverages a modern, no-code data warehouse approach using Google Cloud and Generative AI technologies.

## 🚀 Project Overview (Idea Stage)
Our solution centralizes unstructured civic data from public feeds and complaint portals into Google Cloud BigQuery. By utilizing Vertex AI Gemini Remote Models directly via standard SQL, the platform automatically translates, categorizes, and prioritized citizen complaints (e.g., Sanitation, Water supply) and detects urgency levels without requiring complex data pipelines.

## 🛠️ Tech Stack & Architecture
- **Data Warehouse:** Google Cloud BigQuery (Single Source of Truth)
- **AI/ML Engine:** Vertex AI Gemini Remote Models (via `ML.GENERATE_TEXT` in BigQuery SQL)
- **Compute Infrastructure:** Powered by NVIDIA-accelerated compute backend via Google Cloud
- **Visualization:** Live Looker Studio Dashboards for real-time monitoring and administrative action

## 📈 Key Features
- **Code-Free ELT Pipeline:** Seamless ingestion and text processing natively inside BigQuery.
- **Automated Triaging:** Real-time classification of complaints into respective municipal departments.
- **Urgency Detection:** Instant sentiment analysis to highlight critical issues on a Live Hot-Spot Map.

## 📅 Next Phase (Implementation Plan)
1. Set up the Google Cloud environment and configure IAM roles.
2. Establish the BigQuery remote connection with Vertex AI Gemini models.
3. Deploy the structured SQL schema and run test datasets.
4. Connect Looker Studio to visualize live citizen data and performance KPIs.
