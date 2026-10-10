# DSCI 552 - Homework 3

Feature extraction using the AReM dataset and answers to ISLR 3.7.4.

Open [Oliver_Austin_HW3.ipynb](Oliver_Austin_HW3.ipynb) in Jupyter and run the cells from top to bottom. The first code cell installs the packages. Keep the `data/` folder in the same directory as the notebook.

Optional practice is in [Oliver_Austin_HW3_Extra_Practice.ipynb](Oliver_Austin_HW3_Extra_Practice.ipynb).

## Data notes

- A few files use spaces instead of commas or have trailing commas. The notebook handles these when loading the data.
- `sitting/dataset8.csv` has 479 samples instead of 480 because timestamp 13,500 ms is missing. I use the available samples without filling in the missing value.
- There are six pairs of duplicate recordings, and three pairs cross the train/test split. I kept the split required by the assignment.
- The original data files are unchanged.
