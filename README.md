# Breast_Cancer_Classification
This repository contains a script for classifying breast cancer as either malignant or benign tumor using logistic regression. We use the Breast Cancer Wisconsin dataset, available in the ```sklearn.datasets``` library.
## Dataset
* Source: ```sklearn.datasets```
* Description: The Breast Cancer Wisconsin dataset consists of 569 samples with 30 features each, characterizing cell nuclei from breast cancer biopsies.
* Target Classes:
  - 0: Benign
  - 1: Malignant
## Project Requirements
  * Python 3
  * Libraries:
      - ```numpy```
      - ```pandas```
      - ```sklearn```
      - ```notebook``` or ```jupyter```
## Usage
### Objective
The main objective is to create a machine learning model that can classify breast tumors into malignant or benign categories using the features provided.
### Steps
  * Data Loading: The dataset is loaded directly from ```sklearn.datasets```.
  * Data Splitting: The data is split into training and test sets using an 80-20 split.
  * Model Training: We use Logistic Regression from ```sklearn.linear_model``` to build a simple classifier.
  * Evaluation: The model is evaluated on the test set using accuracy as the primary metric.
### Project Files
- Breast_Cancer_Classification.ipynb: Jupyter notebook containing the entire workflow, from -data loading to model evaluation.
- README.md: Project documentation.
- data.csv: The dataset file.
### Instructions
* Clone the Repository:
```bash
git clone https://github.com/sejalsahu01/Breast_Cancer_Classification
cd Breast_Cancer_Classification
```
* Install Dependencies: Ensure you have the required libraries installed. You can install them using pip:
```bash
pip install numpy pandas scikit-learn jupyter
```
* Run the Jupyter Notebook: Launch Jupyter Notebook and open the ```Breast_Cancer_Classification.ipynb``` file:
```bash
jupyter notebook Breast_Cancer_Classification.ipynb
```
## Results
Using Logistic Regression on this dataset typically achieves high accuracy, often above 90%, indicating it is effective in distinguishing between malignant and benign tumors.
## License
This project is for educational and research purposes only, and the dataset used is courtesy of ```scikit-learn```.
