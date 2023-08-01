# Project README

## Introduction

This project aims to analyze a dataset containing information about heart disease, smoking habits, and biking activities. The primary objective is to explore the relationship between smoking, biking, and the occurrence of heart disease. The insights gained from this analysis can have significant implications for public health and well-being, providing evidence-based conclusions to support decision-making processes.

## Dataset

The dataset used in this project is stored in a CSV file named `heart.data.csv`. It contains the following columns:

- `smoking`: Numerical variable representing smoking habits.
- `biking`: Numerical variable representing biking activities.
- `heart_disease`: Binary variable (0 or 1) indicating the occurrence of heart disease.

## Getting Started

To run the code, you will need Python and the following libraries installed:

- NumPy
- Matplotlib
- Seaborn
- Pandas
- Statsmodels

Clone this repository to your local machine using the following command:

```
git clone https://github.com/valarythairu/practice-project
```

Once cloned, navigate to the project directory:

```
cd project-repository
```

Install the required libraries (if not already installed):

```
pip install numpy matplotlib seaborn pandas statsmodels
```

## Data Understanding

The first step of the analysis involves understanding the dataset. The code will load the data, display its dimensions, and provide summary statistics to gain insights into the data structure. Additionally, data types of the columns will be displayed to identify any potential data quality issues.

## Data Preparation

Data preparation is crucial for a clean and reliable analysis. This step involves:

1. Renaming the column `heart.disease` to `heart_disease` for consistency.
2. Rounding off the values in the dataset to the nearest integer to remove decimal points.

## Exploratory Data Analysis (EDA)

EDA will be performed to visualize the distribution of variables in the dataset. Histograms will display the distribution of each variable, allowing us to identify patterns and trends.

Additionally, bivariate analysis will examine the relationship between smoking/biking and heart disease. Scatter plots will provide insights into the correlation between these variables.

## Modeling

The project will build a linear regression model to quantify the impact of smoking and biking on heart disease occurrence. The model will be fitted using the Statsmodels library, and its results will be displayed.

## Conclusion

The insights gained from this analysis will be summarized in the conclusion section, highlighting the relationship between smoking, biking, and heart disease. The conclusions can have implications for healthcare professionals, policymakers, and individuals in promoting healthier lifestyle choices to reduce the burden of heart disease.

For more detailed information about the code implementation, please refer to the Jupyter Notebook or Python script provided in the repository.



## Team Members

The following individuals have contributed to this project:

- Valary Thairu (valary.thairu@student.moringaschool.com)
- James Mungai (james.mungai@student.moringaschool.com)
- Maurice Njogu  (maurice.njogu@student.moringaschool.com)
- Caren Chepkoech (caren.chepkoech@student.moringaschool.com)
- Julie Chepngeno(julie.chepngeno@student.moringaschool.com)
- Lynn Ndero(lynn.ndero@student.moringaschool.com)
-

Special thanks to all our contributors for their valuable contributions!

