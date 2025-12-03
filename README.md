# Digital-Twin-Predictive-Quality-Monitoring-System
🏭 Digital Twin + Predictive Quality Monitoring System AI-Powered Manufacturing Health &amp; Quality Prediction | Real-Time Alerts | Gradio Dashboard

This project simulates a Digital Twin of a manufacturing machine and builds a Predictive Quality Monitoring System using AI/ML.

The system generates realistic time-series sensor data, predicts failure or quality degradation, and provides automated maintenance recommendations. It also includes an interactive Gradio dashboard and email alert system for real-world usability.

⭐ Project Highlights

🔧 Digital Twin simulation of multiple machines with realistic sensor behavior

📊 Predictive model (Random Forest or ML model of your choice) to forecast quality issues

🧠 Rule-based expert system for actionable maintenance recommendations

🖥️ Gradio dashboard to interactively assess machine health in real time

📧 Automated email alerts when machine is at risk (HTML styled for clarity)

🧪 Full ML pipeline: data generation → EDA → modeling → deployment

🧪 Features in Detail
🔹 1. Digital Twin Simulation

Generates data for multiple machines across several days with sensor fields:

Temperature

Vibration

Pressure

Spindle speed

Tool wear progression

Quality OK / Not OK

Failure indicator

The simulation includes drift, anomalies, and wear patterns like real equipment.

🔹 2. Predictive ML Model

A Random Forest Classifier is trained to predict:

quality_risk = 1 → High probability of quality failure

quality_risk = 0 → Machine is healthy

Model Evaluation Includes:

Accuracy

Precision / Recall

Confusion Matrix

ROC-AUC

🔹 3. Recommendation Engine

Uses sensor thresholds + expert rules to generate maintenance actions like:

Reduce temperature: check coolant flow

High vibration: check imbalance & bearing

Pressure abnormal: inspect valves

Excessive tool wear: schedule tool change

These insights mimic what an experienced maintenance engineer would decide.

🔹 4. Gradio Dashboard (Interactive Digital Twin UI)

Users can input live sensor values:

Temperature

Vibration

Pressure

Speed

Tool Wear

The app outputs:

Status: HEALTHY / AT RISK
Risk Probability: (0 to 1)
Recommended Actions: bullet list

🔹 5. Automated HTML Email Alerts

If machine status = AT RISK, the system sends a well-formatted HTML email with:

Color-coded status

Risk probability badge

Actionable recommendations

Timestamp

This simulates a real industrial alerting system.
