Detecting statistically rare events in industrial sensor data to identify potential mechanical failures, fraud, or sensor malfunctions.

# Industrial Sensor Anomaly Detection
This notebook demonstrates how to use machine learning techniques, specifically the Isolation Forest algorithm, to detect anomalies in industrial sensor readings. Anomalies are not considered errors but statistically rare events that may indicate mechanical failures, fraudulent activity, atypical behavior, or defective sensors. The project includes preprocessing steps, feature scaling, model training, and visualization of detected anomalies across multiple sensor variables such as temperature, vibration, pressure, flow rate, and efficiency.

# Technologies Used
- Python 3.12
- Pandas 
- NumPy 
- Scikit-learn 
- Matplotlib

# Included Files
- industrial_sensors.csv → dataset containing sensor readings (Timestamp, Temperature, Vibration, Pressure, Flow Rate, Efficiency)
- ml_industrial_sensors_anomaly_detection.ipynb → Jupyter Notebook implementing the anomaly detection pipeline
- industrial_sensors_anomalies_processed.csv → set of processed and treated data
