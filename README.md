# Forest Fire Prediction

[![Python](https://img.shields.io/badge/Language-Jupyter%20Notebook-orange)](https://jupyter.org/)

## Description

This repository includes the necessary code and dataset to develop and train a predictive model (Uses Regression Models) for detecting potential forest fires.

## Dataset Description

Source : <a href="https://archive-beta.ics.uci.edu/dataset/547/algerian+forest+fires+dataset"> UCI - Algerian Forest Dataset </a>

The dataset includes 244 instances that regroup a data of two regions of Algeria,namely the Bejaia region located in the northeast of Algeria and the Sidi Bel-abbes region located in the northwest of Algeria.
- 122 instances for each region.
- The period from June 2012 to September 2012.
- The dataset includes 11 attribues and 1 output attribue (class)
- The 244 instances have been classified into fire (138 classes) and not fire (106 classes) classes.

## Key Features and Highlights

- Utilizes regression Models to predict Fire Weather Index using inputs given by user for Algeria region.
- Input Features are-
    - Temperature
    - Relative Humidity (RH)
    - Wind Speed (Ws)
    - Rain
    - Fine Fuel Moisture Code (FFMC)
    - Duff Moisture Code (DMC)
    - Initial Spread Index (ISI)
    - Region
- Displays the Predicted FWI value and  Risk level classification (based on predefined FWI thresholds).


## Installation

To run the project, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/your-username/Forest-fire-Prediction.git
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Run application:

```bash
python application.py
```

4. Open your web browser and navigate to http://localhost:5000/


## Dependencies

The project has the following dependencies:

- NumPy
- Pandas
- Scikit-learn
- Matplotlib

## Thesis and PPT

<a href="https://drive.google.com/file/d/1A63Yje8k_bBIF28yk-TtsetzkNFyxdta/view?usp=drive_link" > Thesis </a>
<br>
<a href="https://docs.google.com/presentation/d/1wDwyLZozPP-dD6Z_RNYv10c-h-C7X0MS/edit?usp=drive_link&ouid=110757473140388247684&rtpof=true&sd=true" > PPT </a> 

##
