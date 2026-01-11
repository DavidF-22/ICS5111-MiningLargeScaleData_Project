# ICS5111-Mining Large-Scale Data (Group Project)

**Business and Finance**

Develop a RAG system that retrieves and summarises financial or market information to support
high-level analysis (e.g. explaining market movements, summarising company news, or describing
macroeconomic indicators). Unstructured data may include financial news articles, analyst
commentary or company reports; structured indicators (such as country-level economic measures
or simple company-level metrics) can be used as additional context where appropriate.

## Setup

### Requirements
- **Python 3.11.9** 
- **pip** (Python package manager)

> [!NOTE]
> (Python 3.11.9 was used during development and is recommended for compatibility.)

### Installation
### 1. Clone the repository

```bash
git clone https://github.com/DavidF-22/ICS5111-MiningLargeScaleData_Project.git
cd ICS5111-MiningLargeScaleData_Project
```

### 2. Create a Python environment

```bash
# for windows
python -m venv .venv
source .venv/Scripts/activate
pip install -r requirements.txt

# for linux based systems
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

### 3. Run the notebooks
After installing the dependencies, you can run the data preprocessing and notebook `RagAssignment.ipynb`.

## Datasets Utilised
- [Kaggle Financial Sentiment Analysis Dataset](https://www.kaggle.com/datasets/sbhatti/financial-sentiment-analysis)
- [World Bank Open Data](https://data.worldbank.org/)

## Acknowledgments
This project was developed as part of the `ICS5111` course at the [`University of Malta`](https://www.um.edu.mt/).

## Contact
For any inquiries or feedback, please contact [Gianluca Amato](mailto:gianluca.amato.24@um.edu.mt) & [David Farrugia](mailto:david.farrugia.22@um.edu.mt).
