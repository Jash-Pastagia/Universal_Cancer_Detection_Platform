# **Universal Cancer Detection Platform**  
**AI-Powered Diagnostic Tool for Early Cancer Detection**  

![GitHub](https://img.shields.io/badge/License-MIT-blue)  
![Python](https://img.shields.io/badge/Python-3.8%2B-green)  
![Deep Learning](https://img.shields.io/badge/DL-PyTorch-yellow)  
![Medical AI](https://img.shields.io/badge/Medical%20AI-ResNet--34-orange)  

---

## **Overview**  
The **Universal Cancer Detection Platform** is an AI-powered diagnostic tool designed for the early detection of **leukemia**, **lung cancer**, and **colon cancer**. Built using **ResNet-34** and leveraging **transfer learning**, this platform provides accurate and efficient cancer detection across multiple datasets. The system is aimed at improving early diagnosis and treatment outcomes.

---

## **Features**  
- **Multi-Cancer Detection**: Detects leukemia, lung cancer, and colon cancer using a single model.  
- **Transfer Learning**: Utilizes pre-trained ResNet-34 to reduce training time and improve accuracy.  
- **Data Augmentation**: Enhances model robustness with techniques like resizing, normalization, and augmentation.  
- **User-Friendly Interface**: Built with Streamlit for easy interaction and visualization.  

---

## **Technology Stack**  
- **Programming Language**: Python  
- **Deep Learning Framework**: PyTorch  
- **Model Architecture**: ResNet-34  
- **Data Processing**: Pandas, Matplotlib  
- **Web Framework**: Streamlit  

---

## **Installation**  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/Jash-Pastagia/Universal_Cancer_Detection_Platform.git  
   cd Universal_Cancer_Detection_Platform
2. Install dependencies:  
   ```bash  
   pip install -r requirements.txt
3. Download the datasets:
   -Ensure you have access to the required datasets.
   -Place the datasets in the data/ directory.  
4. Run the application:  
   ```bash  
   streamlit run app.py

## **Usage**  
1. **Launch the Web App**:  
   - Run the app using the command above.  
   - Open the provided local URL in your browser.  

2. **Upload Medical Images**:  
   - Use the interface to upload medical images.  

3. **View Predictions**:  
   - The system will analyze the images and display the predicted cancer confidence scores.  

---

## **Dataset**  
The platform uses the following datasets:  
- **Leukemia**: Blood smear images for leukemia detection.  
- **Lung Cancer**: CT scan images for lung cancer detection.  
- **Colon Cancer**: Histopathology images for colon cancer detection.  
