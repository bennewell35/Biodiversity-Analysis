Biodiversity Analysis in National Parks

Overview

This project analyzes data from the National Park Service on endangered species across various national parks. The goal is to explore patterns and themes related to the conservation statuses of these species, understand which species are most at risk, and investigate the distribution of endangered species across different parks.

Project Objectives
Data Analysis: Perform exploratory data analysis (EDA) to understand the distribution of species and their conservation statuses.
Data Visualization: Use visualizations to uncover trends and patterns in the data.
Insights: Pose questions about the data and answer them through analysis, providing meaningful insights into biodiversity and conservation efforts.
Communication: Document and share findings in a clear, organized manner using a Jupyter Notebook.

Data Sources
The data used in this project comes from two primary files:
species_info.csv: Contains information about different species, including their scientific names, common names, species types, and conservation statuses.
observations.csv: Contains data on the number of observations of these species across various national parks.

Key Questions
The analysis in this project seeks to answer the following questions:

What is the distribution of species across different conservation statuses?
Are certain types of species (e.g., mammals, birds, plants) more likely to be endangered?
Which national parks have the highest number of endangered species?
Are there any patterns or themes that can be observed in the data regarding endangered species?
Analysis and Findings

The analysis is conducted in the biodiversity.ipynb Jupyter Notebook and covers the following steps:

Data Loading and Inspection:

Load the data from species_info.csv and observations.csv.
Inspect the structure of the data and clean it if necessary.

Exploratory Data Analysis (EDA):

Analyze the distribution of species by their conservation statuses.
Investigate the types of species that are most at risk.
Examine the number of endangered species observed in different parks.

Data Visualization:

Create visualizations to highlight key findings, such as bar charts showing the distribution of endangered species across parks.
Insights and Conclusions:

Summarize the findings from the analysis, including any patterns or significant observations about endangered species in national parks.
Requirements

To run the analysis, you will need the following Python libraries:

pandas
seaborn
matplotlib
You can install the required packages using pip:

bash

pip install pandas seaborn matplotlib
Usage

Clone the repository to your local machine:
bash

git clone https://github.com/bennewell35/Biodiversity-Analysis.git

Navigate to the project directory:
bash

cd Biodiversity-Analysis
Open the Jupyter Notebook:
bash

jupyter notebook biodiversity.ipynb

Run the cells in the notebook to perform the analysis and view the visualizations.

Conclusion
This project provides valuable insights into the conservation efforts within national parks and highlights the importance of protecting endangered species. By analyzing the data, we can better understand which species are most at risk and where conservation efforts should be focused.

License
This project is licensed under the MIT License - see the LICENSE file for details.
