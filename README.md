# biodiversity-in-national-parks
In this project, I will explore the the biodiveristy observed in a variety of national parks. I will analyze the data from two datasets (```observations.csv``` and ```species_info.csv```) to answer the questions I have about the data.

**Questions**
* Identify which parks have the most observations
* Identify the most and least spotted species
* Identify why some species are endangered
* Identify which species are the most and least isolated (how many national parks are they in?)
* Visualize the conservation status of each species in the dataset

## Repository Structure
```
README.md

├─ data/
│  ├─ raw/                     (original, untouched files)
│  ├─ processed/   

├─ src/
│  ├─ __init__.py               ---->               empty
│  ├─ data_prep.py              ---->               cleaning logic
│  ├─ plotting.py               ---->               charts
│  └─ utils.py                  ---->               calculations

├─ notebooks/
│  ├─ 00_setup.ipynb            ---->               imports and setups
│  ├─ 01_eda.ipynb              ---->               exploration & comments
│  ├─ 02_clean.ipynb            ---->               calls functions
│  ├─ 03_analysis.ipynb         ---->               tells the story
│  └─ 04_results.ipynb          ---->        
```