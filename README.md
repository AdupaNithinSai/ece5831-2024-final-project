
---

# ECE5831 - Final Project  

This repository contains an **Interactive Visualization Tool for Convolutional Neural Networks (CNNs)**, developed as part of the **ECE5831: Pattern Recognition and Neural Networks** course. This tool is designed for educators, students, and researchers to intuitively understand the operations of CNNs through real-time, layer-by-layer visualizations.  

## Features  

The **Interactive CNN Visualization Tool** allows users to:  
- **Draw Images**: Create customized input images for the CNN.  
- **Visualize in Real-Time**: Observe feature maps and activation patterns across convolutional, pooling, and dense layers.  
- **Understand CNN Operations**: Gain insights into concepts like edge detection, feature extraction, and classification processes.  

The project leverages:  
- **Streamlit** for the interactive user interface.  
- **TensorFlow** for building the CNN architecture.  
- **OpenCV** for image preprocessing.  

---

**NOTE:**  
1. The provided Jupyter notebook, final-project.ipynb, demonstrates CNN operations using OpenCV (cv2) only, as Streamlit is not supported within Jupyter environments. 
2. To experience the full interactive user interface, please run the project using Streamlit (see instructions below). 

---

## Getting Started  

1. **Install the Dependencies:**  
   Run the following command to install all required libraries:  
   ```bash  
   pip install -r requirements.txt  
   ```  

2. **Run the Application:**  
   Execute the Streamlit application with:  
   ```bash  
   streamlit run app.py  
   ```  

3. **Input an Image:**  
   Use the interactive drawing canvas to provide a custom image as input.  

4. **Explore Visualizations:**  
   View and analyze the CNN layer outputs as your image propagates through the network!  

---

## Resources

- **Dataset:** We haven’t used any specific dataset since our project focuses on visualization rather than training a CNN for one specific dataset.  
- **Project Report:** [View Report](https://drive.google.com/file/d/1ZSVbu-SzPwG6AAwbmZQVQC5BbeE5uFE7/view?usp=drive_link)  
- **Presentation Slides:** [View Slides](https://drive.google.com/file/d/15AHJgBnLUnZc3_UFvz5YuQexnoxSzG9g/view?usp=drive_link)  
- **Presentation:** [Watch Video on YouTube](https://www.youtube.com/watch?v=zHOBiQmFux4)  
- **Demo:** [Watch Demo on Google Drive](https://drive.google.com/file/d/190AmJZ7Ujdnk0YnIvN8IXVZmh7lTCw5q/view?usp=drive_link)

---




