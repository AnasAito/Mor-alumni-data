# Mor-alumni-data
data archive for the [Moroccan Alumni Report](https://moroccan-alumni.vercel.app/)

## Data schema :
![image](https://user-images.githubusercontent.com/56308112/163890419-134ab912-de2a-46f6-8d3c-9bfd18db82a0.png)

## About the data :
- Schools_data.pkl

```python
# load data using pickle 
import pickle
with open('../data/schools_data.pkl', 'rb') as f:
    data = pickle.load(f)
```
- Emsi skills dataset

```python

# load skill data
import pandas as pd
skill_data = pd.read_csv('../data/all_skills_df.csv')
```


