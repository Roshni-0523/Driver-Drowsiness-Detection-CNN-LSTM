# Driver-Drowsiness-Detection-CNN-LSTM
This project compares a classical computer-vision-based Eye Aspect Ratio (EAR) method with a deep-learning-based CNN–LSTM hybrid model for real-time driver fatigue detection. The CNN–LSTM achieved 96.48% accuracy, outperforming traditional approaches and demonstrating robustness in low-light and occluded conditions.
🛞Features

Real-time drowsiness detection via webcam

EAR-based classical method using OpenCV & Dlib

Deep CNN–LSTM model for spatiotemporal fatigue patterns

Comparison dashboard with performance metrics

👉Flowchart

![dl_flowchart](https://github.com/user-attachments/assets/c62db242-9aed-45af-a46a-a0ac5227694d)

🧰 Tech Stack

Python, TensorFlow, OpenCV, Dlib, NumPy, Matplotlib, Google Colab

📊 Performance
Model	Accuracy	Precision	Recall	F1 Score
EAR-Based	89.12%	86.47%	84.20%	85.32%
CNN–LSTM	96.48%	95.80%	96.20%	96.00%
📂 Repository Structure
├── data/
├── notebooks/
├── src/
├── results/
├── requirements.txt
└── README.md

🚀 How to Run
git clone https://github.com/Roshni-0523/Driver-Drowsiness-Detection-CNN-LSTM.git
cd Driver-Drowsiness-Detection-CNN-LSTM
pip install -r requirements.txt
python src/main.py

📚 Dataset

Kaggle Drowsiness Prediction Dataset

MRL Eye Dataset

📸 Results

![loss_ml](https://github.com/user-attachments/assets/38383fbd-fb1c-43dc-9e24-b169b2094c2f)

![accuracy_ml](https://github.com/user-attachments/assets/c03305b7-60c1-48e3-a60d-f94556ee87ad)

![predicted_ml](https://github.com/user-attachments/assets/59ecb3b1-17dd-457d-86cd-9f5bb2f6ad5b)

<img width="990" height="451" alt="ml_training and validation_loss accuracy" src="https://github.com/user-attachments/assets/fbdfc001-b774-4251-b1d8-c3317d73ed56" />

<img width="513" height="470" alt="ml_predicted label" src="https://github.com/user-attachments/assets/71bda20d-ae63-4229-96f5-ab7a8721c7e3" />

🏁 Future Scope

Model pruning, edge deployment using TensorRT, and real-world testing for ADAS integration.
