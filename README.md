# predicting-walking-ability-of-amputees
To predict the K-Level (a measure of mobility for amputees) based on patient details like age, gender, muscle strength, balance, and medical history. This helps healthcare professionals understand the patient's rehabilitation potential and decide the right treatment or prosthesis.
 Here’s a professional and well-structured **README.md** content for your GitHub repository:

---

# 🦿 K-Level Prediction for Amputees using Machine Learning

A machine learning-based tool for predicting the **K-Level** (mobility classification) of lower-limb amputees using clinical and demographic data. The project includes a Decision Tree model and an interactive user interface built with `ipywidgets` for clinicians to input patient details and receive visual predictions.

---

## 📌 Project Overview

**K-Level** refers to a classification system used in prosthetic prescription to describe a patient's mobility potential.
This project:

* Uses a **Decision Tree Classifier** to predict K-Level (1, 2, or 3),
* Accepts patient input through a **widget-based form**,
* Provides **prediction confidence** and **data visualizations** for interpretation.

---

##  Key Features

*  Predicts K-Level based on medical and lifestyle parameters
*  Visualization of:

  * Prediction probabilities
  * User input vs. dataset distribution
  * Patient’s Age vs. BMI against the population
  *  Interactive user interface for real-time input and feedback
  *  Simple, interpretable model with medical relevance

---

##  Technologies Used

* Python
* Pandas, NumPy – Data Handling
* scikit-learn – Model Building
* Matplotlib, Seaborn – Visualization
* ipywidgets – Interactive UI in Jupyter
* Jupyter Notebook

---

##  Dataset

* A simulated dataset (`simulated_lll_dataset.csv`) with the following features:

  * **Demographics**: Age, Gender, Education Years
  * **Clinical**: BMI, Balance Level, Muscle Strength (Hip, PF)
  * **Psychosocial**: BDI Score, MSPSS Score
  * **Health History**: Smoking Status, Diabetes, Amputation Level
  * **Target**: K\_Level (1, 2, 3)

---

##  How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/k-level-prediction.git
   cd k-level-prediction
   ```

2. Install required packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook and run the notebook:

   ```bash
   jupyter notebook
   ```

4. Fill out the form with patient details and click **Predict K-Level**.


##  Model Evaluation

* **Algorithm**: Decision Tree Classifier
* **Accuracy**: *\[e.g., 85%]* on test data
* **Evaluation Metrics**: Confusion Matrix, Classification Report

---

##  Contributions

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

##  License

This project is open-source and available under the [MIT License](LICENSE).

---

##  Acknowledgments

* Inspired by real-world clinical decision support tools
* Thanks to open-source contributors and the machine learning community

---


