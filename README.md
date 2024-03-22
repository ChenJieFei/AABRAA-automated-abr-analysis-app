# Auditory Brainstem Response (ABR) Data Analysis App

## Overview
AABRAA (Automated ABR Analysis App) is designed to assist researchers in the analysis of auditory brainstem response (ABR) data recorded from Tucker Davis Technology's BioSigRZ software. It provides a suite of tools for uploading, visualizing, and analyzing ABR waves.

## Features

### Wave Visualization
The app allows researchers to plot and visualize ABR waves. 

### Automatic Hearing Threshold Detection
Included in the repository is a Jupyter notebook that trains an XGBoost gradient boosting machine to identify the decibel (dB) level at which an ABR corresponds to hearing (hearing threshold), given ABRs across different dB levels. This automatic threshold detection machine learning algorithm is integrated into the app, providing a valuable tool for researchers.

### Peak and Trough Detection
These waves typically have a 5 peak structure, and the app has the capability to automatically identify the coordinates of these peaks and troughs. Furthermore, the app utilizes these peak and trough coordinates to calculate useful metrics such as peak-to-peak ratios. Users also have the option to export all this data for further analysis.

## Getting Started

You have two options to get started with the ABR Analysis App:

1. **Use the Web App:** You can access the web application directly at https://abr-analysis.streamlit.app/.

2. **Run Locally:**
    - Clone the repository
    - Install the required dependencies
    - Run the application
