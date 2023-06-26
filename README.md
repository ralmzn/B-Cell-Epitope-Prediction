# B-Cell_Epitope_Capstone

This project aims to predict B-cell Epitopes. Epitope prediction is an important aspect of vaccine development. 

An epitope is the region of an antigen or peptide that gets recognized by and binds to the immune system, including anitbodies, B-cells or T-cells. For the purposes of this analysis, the term "epitope" will be referring specifically to the B-cell epitopes. These are regions that bind to a B-cell and will trigger physiological events that lead to the production and secretion of antibodies, creating an immune response.

Whether a peptide in a protein sequence is epitopic or non-epitopic will serve as the target variable for this analysis and may be referred to an "immune response" or "antibody activity", these terms imply the same thing. 

In terms of vaccine development, identifying these regions are crucial. Vaccines are designed to introduce epitopes to the immune system that mimic the real disease, training B-cells to recognize and respond to these epitopic sequences without exposure to the actual disease.

By introducing these epitopic peptides that are similar to the actual disease to the immune system, the vaccines allow the immune system to develop a memory response and the immune system will produce antibodies geared towards fighting the specific disease. Epitopes that will induce an immune response serve as a great base point for vaccine development and this project aims to develop a model that will predict B-cell epitopes based on the protein sequences of a particular disease.

### The Jupyter Notebooks are divided into four sections:

1. Data Cleaning and Preprocessing --> DataCleaning_Capstone.ipynb
2. Exploratory Data Analysis       --> EDA.ipynb
3. Machine Learning                --> ML_Models.ipynb
4. Deep Learning                   --> DeepLearning.ipynb

### The Data folder contains the following files that were used in the project:
1. bcell_cleaned.csv --> general bcell data
2. sars_cleaned.csv --> SARS data
3. bcell_sars_cleaned.csv --> the combined data

### Packages used:
1. pandas
2. numpy
3. matplotlib
4. seaborn
5. sklearn
6. pytorch
7. biopython

### Data Sources:
1. https://www.kaggle.com/datasets/futurecorporation/epitope-prediction
2. IEDB.org
3. UniProt.org



