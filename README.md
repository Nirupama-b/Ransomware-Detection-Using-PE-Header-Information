# Ransomware-Detection-Using-PE-Header-Information
This project focuses on detecting ransomware by analyzing the Portable Executable (PE) header information of Windows executable files. Using extracted header attributes, multiple machine learning and deep learning models were implemented, evaluated, and compared for their effectiveness in malware classification.

Features

Extracts PE header attributes from executable files and converts them into an .arff dataset format.
Implements and compares multiple models:
Random Forest Classifier → 96% accuracyRecurrent Neural Network (RNN) → 95% accuracy
Convolutional Neural Network (CNN) → 95% accuracy
Ensemble Model (LSTM + Random Forest) → 96% accuracy
Evaluates models using accuracy, precision, recall, F1-score, and confusion matrices.
Achieves high detection performance, making it suitable for ransomware detection systems.

📊 Results Overview

Model	               Accuracy	 Precision	 Recall 	F1-score
Random Forest	       96.06%	   94.88%	     97.14%	  96.00%
RNN	                 94.90%	   93.92%	     95.71%	  94.81%
CNN	                 95.14%  	 96.55%	     93.33%	  94.91%
Ensemble (LSTM+RF)	 95.83% 	 94.44%	     97.14%	  95.77%

🛠️ Tech Stack

Language: Python
ML/DL Frameworks: TensorFlow, scikit-learn
Data Processing: NumPy, Pandas
Evaluation: Confusion Matrix, Precision, Recall, F1-score

📌 Use Case

By leveraging PE header metadata for ransomware detection, this system enables faster and more lightweight malware classification without requiring full file scanning, making it ideal for real-time cybersecurity solutions.
