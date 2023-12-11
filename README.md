## AIThyroid: Diagnostic Predictive Modeling for Thyroid Disease 

### Repository Overview

This repository contains different types of data related to the diagnosis of thyroid disease. Attributes range from patient hormone levels to patient opinions about their current health. 
The goal is to use machine learning models to accurately diagnose different types of thyroid conditions, including euthyroid (healthy), hypothyroid and hyperthyroid states.

---

### Datasets

There are multiple databases in this repository that provide data related to thyroid disease. 
The primary datasets used for the analysis include:

- `allbp.data`
- `allhyper.data`
- `allhypo.data`
- `allrep.data`
- `ann-train.data`
- `ann-test.data`
- `dis.data`
- `sick.data`
- `sick-euthyroid.data`
- `thyroid0387.data`

For a more comprehensive analysis and exploratory data investigation, we combined these files into a single dataframe and used this dataframe throughout our analysis. 

---

### Repository Structure

```
thyroid+disease/
│
├── costs                           # Directory containing data related to costs
│
├── AIThyroid_Final_Output.ipynb    # Main analysis Jupyter notebook
│
├── EDA_thyroid.ipynb               # Initial analysis Jupyter notebook
│
├── HELLO                           # General description of databases
│
├── Index                           # File providing index information
│
├── Updated_EDA.ipynb               # Additional exploratory analysis Jupyter notebook
│
├── allbp.data                      # Binding protein database
│
├── allbp.names                     # Binding protein database names
│
├── allbp.test                      # Binding protein database test set
│
├── allhyper.data                   # Hyperthyroid database
│
├── allhyper.names                  # Hyperthyroid database names
│
├── allhyper.test                   # Hyperthyroid database test set 
│
├── allhypo.data                    # Hypothyroid database
│
├── allhypo.names                   # Hypothyroid database names 
│
├── allhypo.test                    # Hypothyroid database test set 
│
├── allrep.data                     # Replacement therapy database 
│
├── allrep.names                    # Replacement therapy database names 
│
└── allrep.test                     # Replacement therapy database test set 
│
├── ann-Readme                      # Description for 'ann-test.data' and 'ann-train.data'
│
├── ann-test.data                   # Thryoid domain database test set 
│
├── ann-thyroid.names               # Thryoid domain database names 
│
├── ann-train.data                  # Thryoid domain database train set 
│
├── dis.data                        # Discordance database 
│
├── dis.names                       # Discordance database names
│
├── dis.test                        # Discordance database test set 
│
├── hypothyroid.data                # Hypothyroid database (edited addition)
│
└── hypothyroid.names               # Hypothyroid database names (edited addition)
│
├── new-thyroid.data                # Recent data additions from Stefan Aberhard
│
├── new-thyroid.names               # Recent data addition names
│
├── sick-euthyroid.data             # Similar database with possible Corruption
│
├── sick-euthyroid.names            # Similar database with possible Corruption
│
├── sick.data                       # Sick database 
│
├── sick.names                      # Sick database names 
│
├── sick.test                       # Sick database test set 
│
├── thyroid.theory                  # Domain theory 
│
├── thyroid0387.data                # Latest archive of thyroid diagnosis from Garvan Institute
│
├── thyroid0387.names               # Latest archive of thyroid diagnosis names
│
```

---

### Project Summary 

In this project, various machine learning algorithms were used to develop a model that effectively predicts thyroid disease. The Random Forest model, particularly when trained and tested on a binary target classifier, emerged as the most effective. This model enabled the visualization of decision trees and feature importance, thereby enhancing our subsequent analyses and leading to the proposal of a practical clinical model.

---

### Contributing

For any questions, comments, issues or contributions, please feel free to open an issue on the Github repository. 

---

### Authors

- **Halladay Kinsey**
- **Stephanie Tabares**

---

### Clone the Repository

To clone this repository, open your terminal or command prompt and run the following command:

```bash
git clone https://github.com/halliekinsey/AAI501_Final.git
```
---

### Acknowledgments

We would like to express our gratitude to the UCI Machine Learning Repository for providing the dataset, and to our professors and mentors for their guidance throughout the project.

---

**Repository Link**: [Thyroid Disease Predictive Modeling GitHub Repository](https://github.com/halliekinsey/AAI501_Final)
