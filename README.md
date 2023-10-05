# bdata-talentanalytics

## Contents

### Exercise 1: Understanding your employees attrition
Delve deep into the patterns and understand the driving factors behind employee attrition. This exercise allows you to explore the dataset, visualize trends, and derive meaningful insights related to employee retention.
  
- **Dataset**: [Link to Dataset](./ex1/dataset/employees_attrition.csv)
- **Notebook**: TBC

### Exercise 2: Employee learnings
Dive into an analysis that showcases the learning patterns of employees across various dimensions. By understanding which courses or trainings have been favored, you could forecast future learning trends.

- **Dataset**: [Link to Dataset](./ex2/dataset/employee_learnings.csv)
- **Notebook**: TBC

## Getting Started

1. Clone this repository to your local machine:
```bash
git clone https://github.com/redurne/bdata-talentanalytics.git
```
2. Navigate to the cloned directory:

```bash
cd bdata-talentanalytics
```
3. Open Anaconda Navigator. You can do that by either from the Windows apps or opening Anaconda Prompt and then running:

```bash
anaconda-navigator
```
4. Launch Jupyter notebook and load data for the corresponding exercise:
   
```python
import numpy as np 
import pandas as pd 
import warnings
import seaborn as sns
import matplotlib.pyplot as plt
%matplotlib inline

# load from github
df = pd.read_csv("https://raw.githubusercontent.com/redurne/bdata-talentanalytics/main/ex1/dataset/employees_attrition.csv")
df.head()

# load from local
df = pd.read_csv("./<relative_local_dataset_path>")
df.head()
```

   
