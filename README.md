MarsVisionAI 🚀🔍
MarsVisionAI is an AI-powered system designed for automated analysis of Martian surface imagery collected by the Curiosity rover. This project utilizes Convolutional Neural Networks (CNNs) for image classification and an autoencoder for image reconstruction, enabling terrain analysis, object recognition, and anomaly detection.

Project Overview
Image Classification: Classifies Mars surface images into different categories (e.g., ground, horizon, rover parts).
Image Reconstruction: Uses an autoencoder to reconstruct input images, potentially aiding in anomaly detection.
Features
✅ Custom CNN Architecture for object detection in Mars images.
✅ Autoencoder Integration for feature extraction and noise reduction.
✅ Multi-class Classification of terrain and rover components.
✅ Image Preprocessing & Data Augmentation for better model generalization.
✅ Efficient Training with Adam optimizer and EarlyStopping.
✅ Evaluation Metrics including accuracy, confusion matrix, and visualization of predictions.

Folder Structure
bash
Copy
Edit
📂 MarsVisionAI  
│── 📂 data                # CSV files and datasets  
│── 📂 images              # Image folder (to be downloaded separately)  
│── 📂 models              # Trained model files  
│── 📂 notebooks           # Jupyter notebooks for training and testing  
│── 📜 requirements.txt    # Dependencies  
│── 📜 README.md           # Project Documentation  

Installation & Setup
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/dhanalakshmi-ai/MarsVisionAI.git
cd MarsVisionAI
2. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
### **3. Download Image Dataset**  
- The dataset is hosted on **Kaggle** due to its large size.  
- Download the dataset from [Mars Surface and Curiosity Image Set (NASA)](https://www.kaggle.com/datasets/brsdincer/mars-surface-and-curiosity-image-set-nasa).  
- After downloading, extract the images and place them inside the `images/` folder in the repository.  

4. Run Jupyter Notebook
bash
Copy
Edit
jupyter notebook
Open MarsVisionAI.ipynb and execute the cells to train and evaluate the model.
Usage

Train the Model: Run the notebook to train the CNN and autoencoder.
Predict on New Images: Use the trained model to classify and reconstruct images.
Visualize Results: The notebook contains visualization functions for model predictions.
Contributing
Feel free to contribute! Fork the repository, make changes, and submit a pull request.

License
This project is licensed under the MIT License.
