
# Data Analysis and Critical Indicators: Hospital Pharmacy Delivery

## Context
This project aims to improve the indicators and critical analysis of urgent medication delivery times in a hospital setting, aligning with a data-driven approach to enhance operational efficiency and improve patient experience. Initial analysis revealed significant limitations in the current method, which relies on median delivery times, resulting in superficial and less detailed evaluations.

To address this, we implemented a model combining LightGBM with third quartile analysis and EWMA. This approach identifies critical variables that impact the delivery process, including order generation/delivery times, prescription departments, and delivery personnel.

## Objectives
- Automate data processing for daily indicator analysis.
- Enhance the accuracy and depth of operational performance evaluations.
- Establish a foundation for proactive process improvement discussions.

## Project Phases
1. Automating daily data visualization and sharing with team members.
2. Incorporating advanced statistical analysis (e.g., KDEs, histograms, and normality tests).
3. Testing machine learning models (e.g., LightGBM) to determine key variable importance.
4. Officially implementing the refined model as a critical performance indicator.

## Structure
- `notebooks/`: Contains the analysis and model development process.
- `scripts/`: Python scripts for automation.
- `data/`: Placeholder for data files.

## Requirements
- Python 3.9+
- Libraries: pandas, numpy, matplotlib, LightGBM.

## Usage
1. Clone the repository and install dependencies:
    ```bash
    git clone <repository_url>
    cd project_directory
    pip install -r requirements.txt
    ```
2. Run the notebook to explore the analysis.

### **Contato**
- Nome: Davi
- Email: davirjr@gmail.com
- LinkedIn: https://www.linkedin.com/in/davi-rodrigues-junior-b1b822b4/
