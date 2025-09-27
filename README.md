

# 🧠 BrainWave: Real-Time EEG-Based Brain State Monitoring  

[https://drive.google.com/file/d/1G2FTFFGpHaR-zDla8mhnGMW3AWqODbQg/view?usp=sharing ](https://docs.google.com/presentation/d/1s-eXcMaaWMMeqvpQ0b6uMbRDhYYfAJdp/edit?usp=sharing&ouid=101927311431373482807&rtpof=true&sd=true)

> 🚀 A low-cost Brain-Computer Interface (BCI) system that enables **thought-driven wheelchair navigation** using EEG signals and deep learning.  

---

## ✨ Highlights  
- 🎯 **Problem Solved:** Lack of affordable and reliable control systems for individuals with severe motor impairments.  
- 🧩 **Approach:** Real-time classification of EEG signals using a **CNN-LSTM hybrid model**.  
- ⚡ **Outcome:** Navigation commands (Forward, Backward, Left, Right, Stop) generated directly from **thoughts**.  
- 💡 **Impact:** Affordable, scalable assistive tech for wheelchairs and beyond (robotic arms, drones, smart homes).  

---

## 📌 Problem Statement  
Traditional wheelchair control methods (joysticks, voice, eye-tracking) are often unsuitable for people with **severe disabilities**.  
👉 Solution: A **non-invasive EEG-based BCI system** that captures brain signals, classifies motor imagery, and maps them into navigation commands.  

---

## 🎯 Objectives  
1. Design a prototype EEG-based wheelchair navigation system.  
2. Preprocess EEG signals to reduce noise and extract features.  
3. Train a **CNN-LSTM** model for spatio-temporal EEG pattern recognition.  
4. Achieve **real-time thought-driven control**.  
5. Ensure affordability and scalability for future assistive devices.  

---

## 🛠️ Tech Stack  

### **Hardware**  
- 🧩 **EXG BioAmp Pill** – EEG acquisition  
- 🧠 EEG Electrodes + Conductive gel  
- ⚡ Arduino Uno / Nano – motor control & signal digitization  
- 🔌 Jumper wires & prototyping board  

### **Software & Libraries**  
- Python: `NumPy`, `SciPy`, `Pandas`  
- Deep Learning: `TensorFlow`, `Keras`  
- ML: `Scikit-learn`  
- MATLAB – EEG visualization  
- Arduino IDE – Microcontroller programming  

---

## ⚙️ System Workflow  

### 1. EEG Signal Acquisition  
![EEG Signal Flow]()

### 2. Preprocessing & Noise Reduction  
- Normalization  
- Windowing  
- Feature extraction  

### 3. Deep Learning Model  
![CNN-LSTM Model] 
- CNN extracts **spatial features**  
- LSTM captures **temporal dynamics**  

### 4. Real-Time Control  
- Model outputs → Arduino → Wheelchair motor control  

---

## 📂 Project Structure  
BrainWave-EEG-BCI/
│── data/ # EEG datasets

│── notebooks/ # Jupyter experiments

│── models/ # Trained CNN-LSTM models

│── src/ # Core source code

│ ├── preprocessing.py

│ ├── train_model.py

│ ├── real_time_classification.py

│── arduino/ # Arduino motor control sketches

│── docs/ # Reports, diagrams, images

│── requirements.txt # Dependencies

│── README.md # Project documentation


