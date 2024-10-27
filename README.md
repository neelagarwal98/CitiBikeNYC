
# Dynamic Modeling and Analysis of Urban Transportation Networks

This project presents a comprehensive study on predictive modeling of urban transportation dynamics, focusing on the integration and interaction between CitiBike and Yellow Taxi networks in New York City using Graph Neural Networks (GNNs).




## Table of Contents

- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)
- [Acknowledgments](#acknowledgments)
## Project Structure
```
project
│
├── 1. Preprocessing
│   ├── Citibike Graph creation function.ipynb
│   ├── dev_preprocess_citibike.ipynb
│   └── dev_preprocess_taxi.ipynb
│
├── 2. NYC Zones
│   ├── Finding centroids of taxi zones.ipynb
│   ├── NYC Taxi Zones.geojson
│   └── ZoneCentroidGeneration.ipynb
│
├── 3. Data Aggregation for time series
│   ├── Daily aggregation of citibike data.ipynb
│   ├── Weekly aggregation of entire citibike data for TGN training.ipynb
│   ├── Monthly aggregation of entire Yellow Taxi data.ipynb
│   └── Monthly aggregation of entire citibike data.ipynb
│
├── 4. EDA
│   ├── sliding_months_EDA
│   │   ├── Sliding months EDA of Citibike.ipynb
│   │   └── Sliding months EDA of Yellow Taxi.ipynb
│   ├── sliding_weeks_EDA
│   │   ├── Sliding weeks EDA Yellow Taxi.ipynb
│   │   └── Sliding weeks EDA citibike.ipynb
│   └── sliding_years_EDA
│       ├── Sliding years EDA of Citibike.ipynb
│       └── Sliding years EDA of Yellow Taxi.ipynb
│
├── 5. gephiGraphs
│   ├── Screenshot 2024-04-17 at 10.35.41PM.png
│   ├── Screenshot 2024-04-17 at 9.52.22 PM.png
│   ├── betweensess.pdf
│   ├── betweensess.png
│   ├── geoLayout13.svg
│   ├── graph1.svg
│   ├── nyc_map.svg
│   └── successful2013.gephi
│
├── 6. Prediction & Report
│   ├── FinalWeightPrediction_WeeklyAggregated-v2.ipynb
│   ├── FinalWeightPrediction_WeeklyAggregated.ipynb
│   └── Report.pdf
│
├──.DS_Store
├── .gitignore
├── requirements_conda.txt
├── requirements_pip.txt
├── README.md
```
## Getting Started

### Prerequisites

- Python 3.12 or later
- Conda or pip
- Jupyter Notebook or Jupyter Lab

### Installation

Clone the repository:
```bash 
git clone https://github.com/neelagarwal98/graph-neural-networks-for-traffic-prediction
.git
```



```bash
# Using Conda
conda create --name <env> --file requirements_conda.txt
conda activate <env>
```

```bash
# Using pip
pip install -r requirements_pip.txt
```

## Usage

```bash
cd graph-neural-networks-for-traffic-prediction
```

```bash
jupyter notebook
```





## Contributors
- Neel Agarwal (nagarwa9@ur.rochester.edu)
- Shyam Shah (sshah77@ur.rochester.edu)
## Acknowledgements
- Professor Gonzalo Mateos Buckstein for guidance and insights.
- PyTorch Geometric team for essential tools and libraries.
