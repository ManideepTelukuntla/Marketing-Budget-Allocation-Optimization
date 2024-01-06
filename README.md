# Marketing Budget Allocation Optimization

<div align="center">
  <img src="https://github.com/ManideepTelukuntla/Marketing-Budget-Allocation-Optimization/blob/main/Images/Marketing-Budget-Allocation-Banner.svg" width="800" height="600" alt="Stock Portfolio Optimization">
  <br>
  <p>Image by Freepik</p>
</div>

## Table of Contents
1. [Introduction/Overview](#1-introductionoverview)
2. [Objective](#2-objective)
3. [Methodology/Approach](#3-methodologyapproach)
   - [Key Features](#key-features)
4. [Installation/Requirements](#4-installationrequirements)
5. [File Descriptions](#5-file-descriptions)
6. [Data Collection and Sources](#6-data-collection-and-sources)
7. [Usage/How to Run](#7-usagehow-to-run)
8. [Results/Conclusion](#8-resultsconclusion)
9. [Contributors/Team](#9-contributorsteam)
10. [License](#10-license)

## 1. Introduction/Overview
This project utilizes Linear Programming to optimize marketing budget allocation across various channels, aiming to maximize Return on Investment (ROI) within organizational constraints.

## 2. Objective
Enhancing ROI across diverse platforms including Print, TV, SEO, AdWords, Facebook, LinkedIn, Instagram, Snapchat, Twitter, and Email.

## 3. Methodology/Approach
- **Linear Programming Model**: Implementing Gurobi optimizer for maximizing ROI.
- **Constraints**: Following investment limits across different platforms.
- **Comparative Analysis**: Comparing strategies with different ROI data sets.

### Key Features
- **Optimal Investment Strategy**: Created from in-depth analysis of ROI data.
- **Sensitivity Analysis**: Assessing changes in ROI estimates.
- **Reinvestment Analysis**: Exploring implications of reinvesting returns.
- **Stability Analysis**: Ensuring consistent and predictable marketing strategies.

## 4. Installation/Requirements
- [Python](https://www.python.org/downloads/)
- [Jupyter Notebook](https://jupyter.org/install)
- [Gurobi Optimizer](https://www.gurobi.com/downloads/) - Requires Gurobi license

## 5. File Descriptions
- **`Marketing-Budget-Allocation-Report.ipynb`**: This Jupyter Notebook contains Python code for finding optimal strategies for allocating marketing budget.
- **`Marketing-Budget-Allocation-Report.pdf`**: A comprehensive report explaining the methodologies, analytical processes, and valuable insights pertaining to marketing budget allocation.
- **`Data`**: Folder containing datasets used in this project.
- **`Images`**: Folder with images pertaining to this project.

## 6. Data Collection and Sources

**Datasets Overview:**  
This project uses three CSV files located in the Data folder. These files contain ROI data for various marketing channels:

- `ROI_data.csv`
- `roi_mat.csv`
- `index_data.csv`

#### File Structure:
**ROI_data.csv**
- This file contains ROI estimates for various marketing channels from two different firms.
- Columns 2-11 represents the ROI estimate values of marketing channels.

**roi_mat.csv**
- This file contains ROI estimates for various marketing channels from January to December.
- Column 1 represents the month.
- Columns 2-11 represents the ROI estimate values of marketing channels.

## 7. Usage/How to Run
- Repository contains comprehensive code and instructions.
- The model can be tailored to different ROI data and constraints.
- Utilize the `Marketing-Budget-Allocation-Report.ipynb` to assess and optimize your own marketing budget allocation.

## 8. Results/Conclusion
The project underscores the value of linear programming in marketing budget allocation, revealing key insights into the most effective investment platforms and the impact of varying ROI scenarios. The findings highlight the necessity for a dynamic allocation approach, adaptable to ROI changes, and emphasize the importance of incorporating constraints for a balanced and risk-averse strategy, contributing to enhanced marketing efficiency and long-term stability.

## 9. Contributors/Team
- Manideep Telukuntla
- Krittika Deshwal
- David Gong
- Teja Sirigina

## 10. License
Licensed under [MIT License](https://github.com/ManideepTelukuntla/InvestigateTMDBMovieData/blob/master/LICENSE)
