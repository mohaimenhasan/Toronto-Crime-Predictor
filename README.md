# Toronto Crime Trend Analysis

## Overview
This project analyzes the Major Crime Indicators (MCI) dataset from the Toronto Police Service to identify crime trends and high-risk areas, enhancing public safety through data-driven insights.

## Structure

```plaintext
project_name/
│
├── data/               # Dataset storage
│   └── MCI_data.csv    # MCI dataset file
│
├── notebooks/          # Jupyter notebooks for exploration and analysis
│   └── analysis.ipynb
│
├── scripts/            # Python scripts for preprocessing and modeling
│   └── models.py
│
├── requirements.txt    # Project dependencies
│
└── README.md           # Project documentation
```

## Setup
To get started with this project:

1. Clone the repository:
```bash
 git clone https://github.com/mohaimenhasan/Toronto-Crime-Predictor.git
```
2. Navigate to the project directory:

```bash 
cd Toronto-Crime-Predictor
```

3. Set up a virtual environment:
```bash
python -m venv env
source env/bin/activate  # Use `.\env\Scripts\activate` on Windows
```

4. Install dependencies:
```bash
pip install -r requirements.txt
```

5. Launch Jupyter Notebook to access the notebooks:
```bash
jupyter notebook
```

## Data
The data/ directory contains the crime dataset provided by the Toronto Police Service. To download the dataset vist - https://www.tps.ca/data-maps/open-data/

The CSVs I collected for this project are:
- Major_Crime_Indicators_Open_Data.csv
- Major_Crime_Indicators_Open_Data.geojson
- Major_Crime_Indicators_Open_Data.kml

## Notebooks
The notebooks/ directory includes Jupyter notebooks with detailed data analysis and visualization.

## Scripts
The scripts/ directory contains Python code for data preprocessing and machine learning models.

## Requirements
Dependencies are listed in the requirements.txt file and can be installed using pip.

## License
This project is released under the MIT License.

## Contributing
Contributions to this project are welcome! Please refer to [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## Authors
[Mohaimen Khan](https://www.linkedin.com/in/mohaimenkhan/)

## Acknowledgments
- Toronto Police Service for providing the dataset.
- Contributors who helped with the project.

## Contact
For any inquiries, please reach out to mohaimenhasan@gmail.com.