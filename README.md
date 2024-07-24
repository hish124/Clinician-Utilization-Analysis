# Clinician Utilization Data Analysis

## Project Overview
This project dives into the clinician utilization data to explore how the volume of procedures impacts clinician performance and rankings. The ultimate goal is to make healthcare decisions more transparent and help patients choose their healthcare providers with better information at hand. The analysis and modeling provide key insights to support this goal.

## Table of Contents
1. Project Overview
2. Dataset
3. Installation
4. Usage
5. Project Structure
6. Results
7. Proof of Concept
8. Contributing
9. License

## Dataset
We've worked with a dataset that includes detailed records of various procedures performed by clinicians. Here's a glimpse of what's inside:
- Procedure Category
- Count of Procedures
- Percentile Rankings
- Clinician Identifiers

## Installation
First things first, you’ll need Python installed on your machine. To get everything up and running, you can install the required packages using pip:


```bash
pip install -r requirements.txt
```

## Usage
Ready to dive in? Here’s how you can replicate the analysis and generate the results:

1. Clone the Repository:
```bash
git clone https://github.com/yourusername/clinician-utilization-analysis.git
cd clinician-utilization-analysis
```
2. Run the Jupyter Notebook:
Open the Final_Analysis_Code.ipynb notebook in Jupyter and execute the cells to perform the analysis.

3. Run the Scripts Directly:
Alternatively, you can run the Python scripts directly:

```
python analysis.py
```

## Project Structure
Here's a quick look at how everything in this repository:

- cleaned_utilization.csv
- utilization.csv
- Correlation_Analysis_Procedural_Volume_vs_Clinician_Ranking.png
- Distribution_of_Procedural_Counts.png
- Distribution_of_Procedure_Categories.png
- K-Means_Clustering_of_Procedural_Volumes.png
- Predictive_Modeling_Results.png
- Flowchart_of_the_Data_Processing_Pipeline.png
- Final_Analysis_Code.ipynb
- README.md
- requirements.txt

.csv Contains the dataset files.

.png Holds the generated images and visualizations.

Final_Analysis_Code.ipynb: Jupyter notebook with the complete analysis.

README.md: This file.

requirements.txt: List of Python packages needed for the analysis.

## Results

The analysis uncovered some interesting insights:

- Identified the most commonly performed procedures.
- Analyzed the distribution patterns of procedural volumes among clinicians.
- Examined the correlation between procedural volumes and clinician rankings.
- Conducted clustering analysis of clinicians based on procedural volumes.

## Figures

Here are some of the key visualizations from the analysis:

1. Correlation Analysis: Procedural Volume vs Clinician Ranking
2. Distribution of Procedural Counts
3. Distribution of Procedure Categories
4. K-Means Clustering of Procedural Volumes
5. Predictive Modeling Results
6. Flowchart of the Data Processing Pipeline

## Proof of Concept

To demonstrate the potential of the analysis, I followed these steps:

1. Data Cleaning:
   I handled missing values, removed duplicates, and corrected any inconsistencies in the dataset.
3. Feature Selection:
   Focused on key attributes such as procedural counts and clinician rankings for the analysis.
3. Descriptive Statistics:
   Calculated basic statistical measures to understand the data distribution.
4. Correlation Analysis:
   Analyzed the relationship between procedural volumes and clinician rankings.
5. Clustering Analysis:
   Used K-means clustering to categorize clinicians based on their procedural volumes.
6. Predictive Modeling:
   Developed a model to predict the likelihood of clinician profiles being visible based on various factors.
7. Results Interpretation:
   Interpreted the results to provide insights and recommendations for enhancing transparency in healthcare.



