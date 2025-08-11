# Brain Tumor Detection

## Project Overview
Early detection and classification of brain tumors is a critical research area in medical imaging. Accurate classification helps doctors choose the most effective treatment methods, improving survival rates and patient outcomes.  

This project focuses on detecting and classifying brain MRI scans into four categories:

---

## Tumor Categories

### 1. Glioma
**Definition:**  
A common type of brain tumor originating in the **glial cells**, which support nerve cells in the brain and spinal cord.  

**Characteristics:**  
- Can be benign or malignant  
- Grows within brain tissue  
- Symptoms: headaches, seizures, difficulty thinking, or movement problems  

---

### 2. Meningioma
**Definition:**  
A tumor that originates from the **meninges**, the membranes that cover the brain and spinal cord.  

**Characteristics:**  
- Often benign (non-cancerous)  
- May press on the brain or nerves as it grows  
- Symptoms depend on its location: headaches, vision changes, behavioral changes  

---

### 3. No Tumor
**Definition:**  
MRI scan shows no tumor.  

**Purpose:**  
Serves as a **control/reference** class to help the model learn the difference between healthy and tumorous brain scans.  

---

### 4. Pituitary Tumor
**Definition:**  
A tumor located in the **pituitary gland**, a small gland at the base of the brain that regulates hormones.  

**Characteristics:**  
- Can affect hormone production  
- Symptoms: vision problems, headaches, hormonal imbalances (e.g., weight gain, menstrual issues)  

---

## Project Goals
- Build a deep learning model to classify brain MRI scans into the four categories above  
- Improve medical diagnosis speed and accuracy  
- Support radiologists with AI-based detection tools  

---

## Dataset
The dataset used for this project can be found on Kaggle:  
[Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)

The dataset contains MRI images labeled into **Glioma**, **Meningioma**, **No Tumor**, and **Pituitary Tumor** classes.  
Preprocessing includes normalization, resizing, and augmentation for training robustness.  

---

## Tech Stack
- Python  
- TensorFlow / Keras or PyTorch  
- OpenCV for image preprocessing  
- NumPy, Pandas, Matplotlib for data handling and visualization  

---

## Usage
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/brain-tumor-detection.git
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run training:
    ```bash
    python train.py
    ```
4. Predict on new MRI scans:
    ```bash
    python predict.py --image path_to_image.jpg
    ```

---

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Contact
For questions or collaborations, reach out to:  
**Your Name** – your.email@example.com
