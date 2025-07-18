# Water Quality Prediction Using Machine Learning

## Project Overview

This project aims to build a robust machine learning classifier that predicts the **safety of water samples** based on the concentration of various chemical and biological contaminants. The classification model helps determine whether the water is safe (`is_safe = 1`) or unsafe (`is_safe = 0`) using features like heavy metals, nitrates, bacteria, viruses, and more.

---

## Technical Highlights

* **Dataset**: Contains 7,999 water samples with 21 attributes including:

  * `aluminium`, `ammonia`, `arsenic`, `lead`, `bacteria`, `viruses`, and a binary target label `is_safe`.

* **Data Cleaning**:

  * Removed invalid entries (e.g., rows with `#NUM!`)
  * Handled non-numeric values using type conversion and dropped NaNs

* **Visualization Techniques**:

  * Histograms, boxplots, pairplots, heatmaps, violin plots, and scatterplots to analyze distribution, relationships, and correlations between contaminants

* **Modeling**:

  * Implemented and compared multiple classifiers: Logistic Regression, Random Forest, and XGBoost
  * Achieved best performance with **XGBoost**, followed by hyperparameter tuning using **RandomizedSearchCV**

* **Performance**:

  * XGBoost model achieved a **cross-validated accuracy of 96.9%**
  * Final evaluation using confusion matrix for visual performance analysis

---

## Purpose and Applications

* Assess real-world **water quality** in environmental monitoring
* Aid **governmental health agencies** and **municipal bodies** in water safety checks
* Used in **IoT-based water sensors** for real-time water safety alerts
* Serves as a **teaching aid** for classification, data cleaning, and model tuning in machine learning

---

## Installation

 **Clone the repository**

   ```bash
   git clone https://github.com/BhaveshBhakta/Water-Quality-Prediction-Using-XGBClassifier.git
   cd Water-Quality-Prediction-Using-XGBClassifier
   ```

---

## Collaboration

Contributions are welcome! If you’d like to improve model performance, add new visualizations, or integrate the project with a web interface.
