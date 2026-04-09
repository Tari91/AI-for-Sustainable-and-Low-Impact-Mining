## 🌱 AI for Sustainable and Low-Impact Mining
A machine learning project that improves mining efficiency while reducing environmental impact through ore grade prediction and environmental risk detection.
## 📌 Overview
This project simulates a mining site and applies AI to:
🎯 Target high-grade mineral zones
🚨 Detect potential environmental hazards early
It combines predictive modeling and anomaly detection to support safe, efficient, and sustainable mining operations.
## 🧠 Features
Ore Grade Optimization
Model: Random Forest Regressor
Predicts mineral concentration using spatial data
Environmental Risk Detection
Model: Isolation Forest
Detects abnormal vibration and water pressure patterns
Synthetic Data Simulation
Generates realistic mining and sensor data
Includes injected anomalies (~3%)
Visualization
Resource map (mineral concentration)
Risk map (hazard detection)
⚙️ Tech Stack
Python
NumPy
Pandas
Matplotlib
Scikit-learn
## ▶️ How to Run
Install dependencies:
pip install numpy pandas matplotlib scikit-learn

## Run the script:
python mining_ai.py

## 📊 Output
Mean Squared Error (MSE) for ore prediction
Number of detected environmental hazards
Visualization of:
High-grade zones
Risk areas
🌍 Impact
Reduces unnecessary excavation
Improves environmental safety
Supports sustainable mining practices
🚀 Future Improvements
Real-world dataset integration
GIS/geospatial analysis
Time-series risk monitoring
Web dashboard (Streamlit)
📄 License

👤 Author
William Tarinabo williamtarinabo@gmail.com
