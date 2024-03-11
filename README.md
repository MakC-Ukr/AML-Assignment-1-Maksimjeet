# AML A1 Documentation

This documentation outlines the various Jupyter notebooks and Python scripts used in the AML A1 project. The notebooks are categorized based on the type of data they handle (low noise or high noise) and the specific column (era or target_5) they focus on.

## Report

Report is available at `./Report.pdf`.

## Jupyter Notebooks

## Milestone 1. 

### I. MLP Training

#### 1.Low Noise Data

##### a. Focusing on the 'era' Column
- **Notebook:** `Q1P1.ipynb`

##### b. Focusing on the 'target_5' Column
- **Notebook:** `Q1P1_target_5.ipynb`

#### 2.High Noise Data

##### a. Focusing on the 'era' Column
- **Notebook:** `Q1P1_high_noise.ipynb`

##### b. Focusing on the 'target_5' Column
- **Notebook:** `Q1P1_high_noise_target_5.ipynb`

### II. SubTab Implementations

#### Running SubTab Implementation
- **Script Command:** `python train.py`
- Highest accuracyt reached on high noise data = 61.3% (see C=10000.png)

## Milestone 2

### TabPFN

#### 1.Low Noise Data
- **Notebook:** `TabPFN/Q1M2_TabPFN_Low_noise.ipynb`

#### 2.High Noise Data
- **Notebook:** `TabPFN/Q1M2_TabPFN_High_noise.ipynb`

### Sequential

#### 1.Low Noise Data
- **Notebook:** `RNNs/Q1M2_Sequential_LowNoise.ipynb`

#### 2.High Noise Data
- **Notebook:** `RNNs/Q1M2_Sequential_HighNoise.ipynb`
