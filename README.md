#  Fruit Health and Fruit Recognition System

This is a **major academic project** developed as part of the final year B.E. Computer Science and Engineering curriculum. The project focuses on identifying fruit types and assessing their freshness or rottenness using **deep learning and transfer learning** techniques. A deep learning model based on **MobileNetV2 (with Transfer Learning)** was trained for accurate fruit classification and freshness detection.

## 📌 Overview

The system takes an input image of a fruit and performs:
1. **Fruit Type Classification** – Identifies the fruit (e.g., apple, banana, orange).
2. **Health Detection** – Classifies the fruit as *Fresh* or *Rotten* based on visual cues like discoloration, mold, etc.
3. **Freshness Analysis** – Predicts the **percentage of freshness and rottenness** using a confidence-based model output.

## 🧠 Key Features

- Real-time fruit identification with classification accuracy.
- Predictive analysis of freshness in percentages (e.g., 85% fresh, 15% rotten).
- Pre-trained Convolutional Neural Network (CNN) models.
- User-friendly web interface for image upload and instant results.

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS (using Flask templates)
- **Backend**: Python (Flask)
- **Deep Learning Model**: MobileNetV2 (Transfer Learning)
- **Libraries**: TensorFlow, Keras, OpenCV, NumPy
- **Model File**: `Fresh_Rotten_Fruits_MobileNetV2_Transfer_Learning2(98).h5`


## 📄 Research

- A paper was written based on this project, exploring image preprocessing techniques, CNN architectures, and performance metrics. *(Currently unpublished)* [Paper](https://drive.google.com/file/d/1Pmogqaw1nIvJfHKRgw9-mVN7y7WOZILd/view?usp=sharing)
- A base research paper was referred to during the development for architectural insights and dataset pre-processing. [Base Paper](https://drive.google.com/file/d/1Rd6fsFlRy4RsbAZYMYYAJV-Tp3qcwvFe/view?usp=sharing)

## ✅ Outcomes

- Achieved high accuracy (~92%) on validation datasets.
- Built a working prototype deployable on local servers or cloud platforms.
- Gained practical experience in computer vision, deep learning, and Flask web development.

## Output

### Home page:
![Homepage](static/io/homepage.jpg)
### Freshness Prediction:
![CompleteRotten](static/io/complete_rotten.jpg)
### Rottenness Prediction:
![CompleteFresh](static/io/complete_fresh.jpg)


## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/fruit-health-recognition.git](https://github.com/adithid03/Fruit-Health-and-Fruit-Recognition-System.git)
   cd fruit-health-and-fruit-recognition-system
   ```
2. Install dependencies
  ```bash
    pip install -r requirements.txt
  ```
3. Run the app
   ```bash
  	python ao1.py
   ```
4. Visit `http://127.0.0.1:5000` in your browser.

## 👥 Team Members

- **Durgam Adithi** – adithidurgam22@gmail.com  
- **K.V.L. Praphulla** – kambhampatipraphulla@gmail.com  
- **P. Ashish Reddy** – purumaniashishreddy@gmail.com  
