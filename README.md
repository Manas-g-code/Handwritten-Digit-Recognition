# 🧠 Handwritten Digit Recognition with MNIST

A simple yet powerful deep learning project that classifies handwritten digits (0–9) using the MNIST dataset. This project demonstrates how machine learning and computer vision can be used for pattern recognition and image classification.

---

## MNIST Dataset

![image](https://github.com/user-attachments/assets/86339841-05b9-41d1-a035-8480866cacdd)


## 🔍 Project Overview

This project uses a Convolutional Neural Network (CNN) built with Python and TensorFlow/Keras to recognize handwritten digits from the MNIST dataset with high accuracy.

- 📚 Dataset: [MNIST](http://yann.lecun.com/exdb/mnist/)
- 🧠 Model: CNN with multiple convolution and pooling layers
- 📊 Accuracy: ~98%
- 🖼️ Input: 28x28 grayscale images
- ⚙️ Output: Digit label (0 to 9)

---

## Training Model

![image](https://github.com/user-attachments/assets/9845f1a4-0054-4578-815f-6582775b7440)
![image](https://github.com/user-attachments/assets/d72f22dc-19d1-47a8-b8bb-e17b03504e5f)

---

## 🚀 Tech Stack

- Python 🐍
- TensorFlow / Keras
- NumPy
- Matplotlib (for visualizations)
- Jupyter Notebook

---

## 📁 Project Structure

📦handwritten-digit-recognition
┣ 📂images # Sample predictions & visualization
┣ 📜digit_recognizer.ipynb # Jupyter notebook with code
┣ 📜README.md # Project documentation
┗ 📜requirements.txt # Dependencies


---

## 🔧 How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/handwritten-digit-recognition.git
   cd handwritten-digit-recognition
Create a Virtual Environment (optional but recommended)

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install Dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the Notebook

bash
Copy
Edit
jupyter notebook digit_recognizer.ipynb
📷 Sample Output
![image](https://github.com/user-attachments/assets/d42ea6fc-c122-4a6e-9780-5b73e1124a2e)
![image](https://github.com/user-attachments/assets/4e375f25-92a2-4866-b45d-af6f81c20d31)
![image](https://github.com/user-attachments/assets/7f3f2569-c0df-486b-b23a-13da3eabcec1)

---
📈 Accuracy
Achieved over 98% validation accuracy using a basic CNN architecture. Further tuning and data augmentation can improve results.

💡 Future Improvements
Add data augmentation for better generalization

Convert to a web app using Flask/Streamlit

Try different architectures like ResNet or LeNet-5

Deploy as an Android app

🤝 Contributing
Feel free to fork the repo, submit issues, or create pull requests! Contributions are always welcome.

📜 License
This project is licensed under the MIT License.

✨ Acknowledgments
MNIST Dataset by Yann LeCun
