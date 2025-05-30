
# Anomaly & Survivorship Bias Detection App

## What This App Does

This app is an interactive anomaly detection tool built with **Streamlit** that allows users to:

1. Upload a dataset (CSV)  
2. Select features for clustering  
3. Visualize clusters and anomalies  
4. Understand survivorship bias using statistical overlays  

## Why This Matters

In data analysis, we often focus only on the "visible" or "surviving" data — similar to how WWII engineers only examined returning planes, missing where they were truly vulnerable.

This leads to **survivorship bias**, a trap where decisions are made based only on what’s observed, not on what’s missing.

## What Makes This App Different

- Uses **K-Means clustering** to identify outliers as potential anomalies  
- Visualizes anomalies in red to highlight outliers  
- Prevents clerical mistakes by offering a second look at excluded data  
- Adds a survivorship bias plot to help uncover whether certain data points were unfairly overlooked  

## In One Line

This app helps avoid clerical mistakes by ensuring data decisions aren't misled by what’s simply visible — it gives you a more honest picture.
