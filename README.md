# 🧠 Garbage Classification using Deep Learning

This project is an AI-powered waste classification system that uses a Convolutional Neural Network (EfficientNetV2B2) to automatically identify different categories of garbage from images — such as recyclable, organic, and hazardous waste. It is deployed with a user-friendly Gradio interface and follows a clean, modular folder structure for scalability.

---

## 📁 Project Structure

garbage-classification-ai/
├── data/ # Dataset images or sample inputs
├── models/ # Saved model files (.h5)
├── notebooks/ # Jupyter Notebooks
│ └── Garbage Classification-aicte.ipynb
├── app/ # Gradio or Streamlit app
│ └── app.py
├── requirements.txt # Python dependencies
├── README.md # Project overview and instructions
├── .gitignore # Files to ignore in GitHub


---

## 📦 Technologies Used

- **Python**
- **TensorFlow / Keras**
- **EfficientNetV2B2**
- **Gradio** (for app interface)
- **OpenCV**
- **NumPy, Matplotlib, Seaborn**

---

## 🚀 How to Run This Project

### 📌 Setup

```bash
# Step 1: Clone the repository
git clone https://github.com/your-username/garbage-classification-ai.git
cd garbage-classification-ai

# Step 2: Install dependencies
pip install -r requirements.txt

#Step 3: Run the Notebook
bash
jupyter notebook notebooks/Garbage\ Classification-aicte.ipynb

#Step 4: Run the Gradio App 
bash
python app/app.py

📷 Sample Output
Input Image      	Predicted Class
🥤 Plastic Bottle	Recyclable
🍎 Apple Core	    Organic Waste
🔋 Battery	        Hazardous

🧠 Model Overview

Model: EfficientNetV2B2 (transfer learning)
Layers: Dense → Dropout → Softmax
Training: Augmented images, early stopping, and learning rate reduction
Accuracy: Achieved ~92% on validation set

🔮 Future Enhancements

📸 Real-time prediction with webcam
📱 TensorFlow Lite mobile deployment
🌐 Smart bin integration using IoT
📊 Analytics dashboard using Streamlit/Power BI

