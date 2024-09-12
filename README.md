# dengue-gene-expression-analysis

# Overview

This project analyzes gene expression profiles related to Dengue fever and Dengue hemorrhagic fever (DHF) using the GEO dataset GDS5093. By applying techniques such as Principal Component Analysis (PCA), Hierarchical Clustering (HCA), and machine learning models like Support Vector Machines (SVM), the study identifies significant gene expression patterns across different disease stages—Convalescent, Dengue Fever, Dengue Hemorrhagic Fever, and Healthy Controls. These findings can provide insights into the molecular mechanisms underlying Dengue fever, including immune responses and cellular processes triggered by the virus, offering valuable targets for therapeutic research and diagnostic applications.

# Data

The dataset used in this analysis is based on the GEO dataset GDS5093. It includes:

Gene expression data (dengue_data.csv): Contains gene expression levels for each sample.

Metadata (dengue_metadata.csv): Contains information about the disease state (Convalescent, Dengue Fever, Dengue Hemorrhagic Fever, or Healthy Control) for each sample.

# Findings

Identified significant genes like PSMA6, PSMA4, and GRAMD1C, which play roles in immune response and cell signaling, potentially related to the progression of Dengue infection.

Visualized clustering of samples across disease states using PCA and hierarchical clustering.

The SVM model demonstrated limitations in accurately distinguishing between Dengue fever and Dengue hemorrhagic fever, with a mean accuracy of 63%.

# Installation

Clone the repository:

git clone https://github.com/MontzCode/dengue-gene-expression-analysis.git

- Programming language used: Python

- main libraries: pandas, seaborn, matplotlib, numpy, scikit-learn, bootstrapped

# Contributing

Feel free to submit pull requests or report issues to improve the project.

# License

This project is licensed under the MIT License.

# Contact

For queries, please connect with me on LinkedIn: https://www.linkedin.com/in/monty-nkpa-7a4a7623b/
