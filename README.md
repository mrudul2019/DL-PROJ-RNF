# Analysis of paper: Fairness via Representation Neutralization

We implemented the algorithm in the paper for the dataset - Law School Admission Data and perform comparisons with different machine learning and deep learning models combined with different fairness strategies.

# Contents

- `Python_Notebooks` folder contains:
  
  - `DL-Final-Submission.ipynb` contains DL model with RNF.
  
  - `ML-model.ipynb` contains ML model with and without bias mitigation.
  
  - `Without-RNF.ipynb` contains the DL model without RNF.

- `Images` folder contains screenshots of important plots involved in analysis.

- `Final-Project-Submission-Deep-Learning.pdf` contains the final report for the project - **includes Introduction, Analysis, Findings and Contributions which are not included in Python_Notebooks explicitly** . 

# Important Requirements

- Python 3.7.13

- Torch 1.11.0+cu113

- Fairlearn v0.7.0

- Numpy 1.21.6

- Pandas 1.3.5  

- Sklearn 1.0.2

- Matplotlib 3.2.2 

- GPU

# Acknowledgements

- Thanks to Prof. Tirtharaj Dash, Prof. Tanmay Tulsidas Verlekar and teaching assistants of BITS DL course 2022.

- Thanks to Mengnan Du(first author of the paper) for the awesome paper and helping us with the implementation.

- Thanks to Microsoft for their awesome fairness package - Fairlearn.
