# 📊 AI-Driven Data Storytelling Dashboard

## 🎯 Project Overview
A lightweight, client-side web application designed to ingest flat files (`.csv`) and generate dynamic, infographic-heavy dashboards. The tool integrates with the Google Gemini API to analyze data samples and generate executive "What, Why, How" narratives alongside interactive data visualizations.

## 🏗️ Architecture & Tech Stack
- **Frontend:** Single-file architecture (HTML/CSS/Vanilla JS).
- **Styling:** Custom CSS with glassmorphism UI elements; mobile-first responsive design.
- **Data Parsing:** [PapaParse](https://www.papaparse.com/) for immediate, browser-side CSV processing.
- **Visualization:** [Chart.js](https://www.chartjs.org/) for rendering interactive `<canvas>` elements.
- **AI Integration:** [Google Gemini API](https://ai.google.dev/) (via native JavaScript `fetch()`) for contextual analysis and narrative generation.

## 🚀 Key Features
- **Zero-Server Processing:** Data is parsed directly in the browser via PapaParse, ensuring zero server costs and high data privacy.
- **Interactive Q&A Routing:** Gemini analyzes file headers and sample rows to prompt the user with 3-5 clarifying questions before rendering.
- **Automated Storytelling:** Outputs a structured "What, Why, How" narrative to frame the data contextually.
- **Executive Visuals:** Renders high-fidelity, interactive charts based on AI-generated configuration parameters.

## 💻 Local Development Setup
1. Clone the repository: `git clone https://github.com/[YOUR-USERNAME]/data_dashboard.git`
2. Navigate to the directory: `cd data_dashboard`
3. Serve locally using Python: `python3 -m http.server 8000`
4. Open your browser and navigate to: `http://localhost:8000`
