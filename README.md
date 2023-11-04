# bdata-talentanalytics

## Contents

### Exercise 1: Understanding your employees attrition
Delve deep into the patterns and understand the driving factors behind employee attrition. This exercise allows you to explore the dataset, visualize trends, and derive meaningful insights related to employee retention.
  
- **Dataset**: [Link to Dataset](./ex1/dataset/employees_attrition.csv)
- **Notebook**: [Link to Notebook](./ex1/notebook/)

### Exercise 2: Employee learnings
Dive into an analysis that showcases the learning patterns of employees across various dimensions. By understanding which courses or trainings have been favored, you could forecast future learning trends.

- **Dataset**: [Link to Dataset](./ex2/dataset/employee_learnings.csv)
- **Notebook**: [Link to Notebook](./ex2/notebook/)

### Exercise 3: Employee engagement
Explore an analysis of employee engagement across different aspects. By identifying what employees value most, you can anticipate future engagement trends.

- **Engagement survey example**: please complete [this survey](https://docs.google.com/forms/d/e/1FAIpQLScRFsNFz4dCu1sqI9LpRh5MX9irxmlXuEYZOrW837EAN-C16A/viewform?usp=sf_link) (anonymous)


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
5. Once data is loaded, jump to [Exercise 1](./ex1/README.md) or [Exercise 2](./ex2/README.md)
