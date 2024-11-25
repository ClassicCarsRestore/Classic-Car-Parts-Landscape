# Classic-Car-Parts-Landscape
Classic car spare parts for restoration: International supply chain and environmental impact

## Overview
This project contains datasets, analysis, and visualizations derived from web scraping manufacturers, suppliers, and bodywork parts data from their respective websites. 

## Directory Structure

- **datasets/**: 
  - raw/:
    - **manufacturers**: Raw data from manufacturers.
    - **suppliers**: Raw data from suppliers.
    - **bodywork_parts**: Raw data from bodywork parts.
      
    Note: The raw files have been collected through web scraping.

  - processed/:
    - **manufacturers**: Processed data from manufacturers.
    - **suppliers**: Processed data from suppliers.
    - **bodywork_parts**: Processed data from bodywork parts.
      
    Note: Contains datasets after preprocessing.These files have undergone data cleaning and transformation for further analysis.

- **notebooks/**: 
  - Includes Jupyter notebooks for various analyses in Python language:
    - **(2) Data Preprocessing**: Preprocessing code for the datasets.
    - **(3) Descriptive Analysis**: Code for performing descriptive analysis on the datasets.
    - **(4) Clustering Modeling**: Code for clustering.

- **plots/**: 
  - Contains visualizations generated during the analysis in both PNG and EPS formats.

## Instructions

1. **Download the raw datasets** from the `datasets/` directory.
2. Run the notebook for data preprocessing (2) on the downloaded dataset.
3. After preprocessing, run the notebook for descriptive analysis (3).
4. Finally, run the clustering modeling notebook (4) to generate clustering results.
   
Note: If you only want to view the generated plots, you can directly access the `plots/` directory.

### Requirements

Each notebook includes the necessary packages for execution. If you do not have any of the required packages installed on your computer, you can install them using the following command:

```bash
pip install <package_name>


