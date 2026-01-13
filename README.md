# Smart-Energy-Saving-system-using-AI-models

# README
📄 Project Summary: Smart Energy Control System

Overview This project focuses on predicting building energy consumption using a deep learning approach and automating the decision-making process for HVAC (Heating, Ventilation, and Air Conditioning) systems. By leveraging historical usage data, the system identifies patterns and anomalies to optimize energy efficiency.

Technical Stack Data Analysis: Pandas, NumPy

Visualization: Matplotlib, Seaborn (used for EDA and model evaluation)

Modeling: TensorFlow/Keras (Sequential API, Dense, Dropout)

Key Workflow Exploratory Data Analysis (EDA): Used Seaborn's histplot and boxplot to identify distribution patterns and outliers in the CSV data.
Neural Network Architecture: Designed a 4-layer deep learning model with Dropout (0.2) to prevent overfitting and ensure robust predictions.

Model Evaluation: Visualized the relationship between actual and predicted values. The alignment with the "Perfect Prediction" line indicates high model reliability.

Prescriptive Logic: Implemented a rule-based function to provide real-time HVAC adjustment commands (Decrease/Increase/Maintain) based on the model's output.

![Results](./result.png)

Final Conclusion The system successfully bridges the gap between predictive modeling and real-world application, providing a scalable solution for smart building energy management.
