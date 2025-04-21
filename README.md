# 📊 UCI Adult Income Dataset – Student ML Project

This project was created as part of the course **"Statistical Methods for Data Mining"** at the University of Piraeus.  
The goal was to explore the classic UCI Adult Income dataset using techniques from machine learning, data preprocessing, clustering and neural networks.

---

## 📌 Project Tasks

The work was divided into 5 parts:

1. **Data Cleaning & Preprocessing**  
   - Handling missing values  
   - Feature transformation  
   - Normalization & encoding  
   - PCA dimensionality reduction  

2. **Feature Selection & Outlier Detection**  
   - Chi-squared ranking  
   - IQR method  
   - Boxplots & winsorization  

3. **Clustering**  
   - K-Means & BIRCH  
   - PCA-based visualization (2D & 3D)  
   - Adjusted Rand Index (ARI) for evaluation  

4. **Classification with Scikit-learn**  
   - Random Forest  
   - K-Nearest Neighbors (KNN)  
   - GridSearchCV parameter tuning  
   - Confusion matrix & classification report  

5. **Classification with Keras (Neural Networks)**  
   - Fully connected MLP  
   - EarlyStopping  
   - Train/Validation/Test split  
   - Accuracy, loss curves

---

## 📂 Files

| File                  | Description                                                 |
|-----------------------|-------------------------------------------------------------|
| `Ergasia1.ipynb`      | Data preprocessing and PCA                                  |
| `Ergasia2.ipynb`      | Feature selection and outlier detection                     |
| `Ergasia3.ipynb`      | Clustering (K-Means, BIRCH)                                 |
| `Ergasia4.ipynb`      | Classification with Scikit-learn (Random Forest, KNN)       |
| `Ergasia5.ipynb`      | Neural Networks with Keras                                  |
| `adult.csv`           | Original UCI dataset                                        |
| `adult-preproc.csv`   | Preprocessed dataset used in model training                 |
| `requirements.txt`    | Python libraries used throughout the project                |

---

## 💻 How to Run

To run this project on your local machine:

1. **Download or clone the repository**
   - Click the green "Code" button on the top right of this page
   - Choose "Download ZIP" and extract it, or run:
     ```bash
     git clone https://github.com/ThrasosM/student-ml-project-adult-income.git
     ```

2. **Install the required Python libraries**
   - Make sure you have Python 3.x installed
   - Then open a terminal in the project folder and run:
     ```bash
     pip install -r requirements.txt
     ```

3. **Open the notebooks**
   - You can open the `.ipynb` files one by one (`Ergasia1.ipynb` to `Ergasia5.ipynb`) using:
     - Jupyter Notebook
     - JupyterLab
     - or Google Colab (just drag and drop the files)

4. **Make sure the data files are available**
   - The files `adult.csv` and `adult-preproc.csv` should be in the same folder as the notebooks.

---

## 📝 Final Report (PDF)

The complete report submitted for academic evaluation is available [here (PDF)](Report_Thrasyvoulos_Mastoras.pdf).

It includes:
- Overview of all 5 project stages
- Descriptions of preprocessing, clustering, and classification methods
- Visualizations and evaluation metrics
- Final conclusions and reflections

> This document provides a structured summary for instructors and evaluators.

---

## 🧑‍🎓 Author

**Thrasyvoulos Mastoras**  
University of Piraeus – MSc in Applied Statistics  
📧 thrasos.mastoras@gmail.com  

---
## 📚 Dataset

This project uses the [UCI Adult Income Dataset](https://archive.ics.uci.edu/ml/datasets/adult).
