# 🧠 **Brain Tumor Classification from MRI dataset**

# **What is a brain tumor ?**
A brain tumor is a collection, or mass, of abnormal cells in your brain. Your skull, which encloses your brain, is very rigid. Any growth inside such a restricted space can cause problems. Brain tumors can be cancerous (malignant) or noncancerous (benign). When benign or malignant tumors grow, they can cause the pressure inside your skull to increase. This can cause brain damage, and it can be life-threatening.

# 📂 **Dataset**
This dataset contains 7023 images of human brain MRI images which are classified into 4 classes: glioma - meningioma - no tumor and pituitary.


# 🧠 **Model Overview**
The notebook uses a Convolutional Neural Network (CNN) to detect whether a brain tumor is present in an image.

# **Key steps:**
- Image loading and preprocessing
- Data augmentation
- CNN architecture design
- Training and evaluation
- Accuracy and loss visualization

# 📈 **Results**
The model achieves high accuracy on the validation set and shows good generalization performance.

📌 Metrics such as precision, recall, and F1-score are included in the notebook.


# 🧰 **How to Run**
1. Clone the repository
   
```bash
git clone https://github.com/Yasmixe/Brain_tumor_detection.git
cd Brain_tumor_detection
```
2. Install dependencies
Make sure you have Python ≥ 3.7 installed.

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow keras
```
3. Run the notebook
Open the Jupyter Notebook and run all cells:
```bash
jupyter notebook Brain_tumor_detection.ipynb
```
