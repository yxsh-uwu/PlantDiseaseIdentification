# Plant Disease Classification using CNN

## 📌 Overview
This project utilizes **Convolutional Neural Networks (CNNs)** to classify plant diseases from images. The model is trained on a dataset of plant leaves to detect and categorize different plant diseases, helping farmers and researchers in early disease identification.

## 📂 Project Structure
```
├── dataset/                # Contains training and validation images
├── models/                 # Saved trained models
├── notebooks/              # Jupyter notebooks for data preprocessing & training
├── scripts/                # Python scripts for model training & testing
├── requirements.txt        # Dependencies
├── plant_disease_classification_using_cnn.ipynb  # Main Jupyter notebook
└── README.md               # Project documentation
```

## ⚙️ Features
- **Deep Learning-Based Classification:** Uses **CNNs** built with TensorFlow and Keras.
- **High Accuracy:** Achieves **90%+ training accuracy** and **91% validation accuracy**.
- **Data Augmentation:** Enhances dataset generalization using techniques like rotation, flipping, and zooming.
- **User-Friendly Visualization:** Includes confusion matrix, accuracy plots, and sample predictions.

## 🚀 Installation & Usage
### Prerequisites
Make sure you have Python installed along with the required libraries:
```bash
pip install -r requirements.txt
```

### Run the Model
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/plant-disease-classification.git
   cd plant-disease-classification
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook plant_disease_classification_using_cnn.ipynb
   ```
3. Follow the steps in the notebook to train and test the model.

## 📊 Model Performance
- **Training Accuracy:** 90%
- **Validation Accuracy:** 91%
- **Test Accuracy:** Varies based on dataset split

## 📷 Sample Predictions
Below are some sample predictions made by the model:
| Input Image | Predicted Label |
|------------|----------------|
| 🍃 Healthy Leaf | Healthy |
| 🍂 Diseased Leaf | Powdery Mildew |

## 🛠 Technologies Used
- Python
- TensorFlow & Keras
- NumPy & Pandas
- OpenCV (for image preprocessing)
- Matplotlib & Seaborn (for visualization)

## 📌 Future Improvements
- Implementing Transfer Learning (e.g., ResNet, EfficientNet)
- Deploying as a **Web App** using Flask/Streamlit
- Adding support for **more plant species**

## 🤝 Contributing
Feel free to fork this repo, open issues, or submit pull requests. Contributions are always welcome! 🚀

## 📜 License
This project is licensed under the MIT License.

---
🔗 **Connect with me:** [LinkedIn](https://www.linkedin.com/in/yxsh-agarwal/) | [GitHub](https://github.com/yxsh-uwu)

