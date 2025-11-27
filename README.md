# ⚡ Dutch National Energy Peak Prediction (2025)

##  Project Goal

To model and predict national energy demand peaks in the Netherlands for the period of July 2025 to December 2025.

Our analysis identified the primary drivers of peak demand variance as collective behavioral patterns (the Dutch "Dinner Hour") and atmospheric temperature fluctuations.

##  Key Findings

* **The Dinner Hour Peak:** A consistent, sharp rise in demand starts around 16:00 hrs.
* **Temperature Correlation:** Energy consumption shows a clear, increasing correlation with warmer seasons.

##  Project Structure & Technology

This repository is primarily focused on the deployment and visualization of the model's results.

### app.py
The main Python script using Streamlit to build the interactive dashboard and deploy the LightGBM model for predictions.

### Model File (.joblib)
Contains the serialized LightGBM model (not tracked in Git due to size).

### Data File (.csv)
Contains the prepared historical electricity demand and weather data (not tracked in Git due to size).

### Dashboard
Visualizes the model's output and key relationships (Demand vs. Temperature vs. Time).

## 📦 Handling Large Files (Data and Model)

LightGBM_demand_model & The_cleaned_energy_weather_dataset is too large for standard GitHub tracking. These files are typically excluded from the repository using a .gitignore file to keep the repository fast and manageable.

### How to Access the Files

If someone needs the full dataset or model to reproduce the results, they would typically need to:

1. **Re-run the training notebook:** I can provide a separate Colab/Jupyter notebook that performs the training process, which generates the .joblib model file from scratch.
2. **Request Access:** Share the files via external cloud storage (e.g., Google Drive, Amazon S3) upon request, as they are too large for direct download from this GitHub repository's file browser.

## 💻 Live Demo

Explore the model's predictions and interactive visualizations here:

**Access the Live Dashboard (Streamlit):**
[dutchenergypredictiondashboard-112358.streamlit.app](https://dutchenergypredictiondashboard-yeabsira.streamlit.app/)

## 👥 Contributors

* Yeabsira Belete
* Eidmon Tesfaye
* Meron Rata
* Shaban Al Dhshan
