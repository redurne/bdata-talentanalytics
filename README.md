# bdata-talentanalytics

## Contents

### Exercise 1: Understanding your employees attrition
Delve deep into the patterns and understand the driving factors behind employee attrition. This exercise allows you to explore the dataset, visualize trends, and derive meaningful insights related to employee retention.
  
- **Dataset**: [Link to Dataset](./ex1/dataset/employees_attrition.csv)
- **Notebook**: [Link to Notebook](./ex1/notebook/)

## Getting Started

1. Clone this repository to your local machine:
```bash
git clone https://github.com/redurne/bdata-talentanalytics.git
```
2. Navigate to the cloned directory:

```bash
cd bdata-talentanalytics
```
3. Open Anaconda Navigator. You can do that either from the Windows apps or by opening the Anaconda Prompt and then running:

```bash
anaconda-navigator
```
4. Launch Jupyter Notebook, load libraries and load data for the corresponding exercise:
   
```python
# load libraries
import numpy as np 
import pandas as pd 
import warnings
import seaborn as sns
import matplotlib.pyplot as plt
%matplotlib inline

# load data from github
df = pd.read_csv("https://raw.githubusercontent.com/redurne/bdata-talentanalytics/main/ex1/dataset/employees_attrition.csv")
df.head()

# load data from local
df = pd.read_csv("./<relative_local_dataset_path>")
df.head()
```
5. Once data is loaded, jump to [Exercise 1](./ex1/README.md)
