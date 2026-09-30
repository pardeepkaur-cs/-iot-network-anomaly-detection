# IoT Network Behaviour Anomaly Detection

A proof-of-concept project exploring unsupervised machine learning for identifying unusual behaviour in a simulated IoT environment.

## Focus
IoT security • behavioural anomaly detection • unsupervised machine learning • security monitoring

## What it does
1. Creates synthetic IoT network activity.
2. Explores behavioural features.
3. Applies Isolation Forest without using attack labels during training.
4. Creates simple rule-based security alerts.
5. Compares ML and rule-based alerts.
6. Evaluates the model against synthetic ground truth.
7. Discusses limitations and future research.

## Technologies
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Google Colab/Jupyter.

## Dataset
Synthetic educational data only. No real device, network, patient, or user information is included.

## Important limitation
An anomaly score does not prove compromise. Real deployment would require validated datasets, device-specific baselines, privacy controls, and investigation of alerts.

## Future work
Public IoT-security datasets, model comparison, device-specific baselines, false-positive analysis, lightweight detection, and privacy-preserving telemetry analysis.

