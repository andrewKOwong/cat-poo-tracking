# The Bowel Troubles of Jackie the Cat

## Project Summary

Jackie the cat is a foster cat that has been having bowel issues, especially constipation. As we switch her between food brands and laxative supplements, we thought we'd better plot our the quality of her poos in response to her food/supplementation.

The input data is a hand-maintained Google Sheet that I export into a csv. It contains dates and poop quality (by the [Bristol stool scale](https://en.wikipedia.org/wiki/Bristol_stool_scale)). Additionally, it also has a column for behavioural conditions (zoomies and yowling, which are a sign of distress, as well as mucus and dribbling in the poop).

A separate csv contains dates for different types of food and supplements.

## Instructions

### Description of Files

- `Jackie_Poop.csv` contains poop data.
- `Jackie_Food_Periods.csv` contains dates for different food and supplements fed to Jackie.
- `output.png` is the final figure.
- `poop_tracking_jackie_the_cat.ipynb` is a Jupyter notebook used to plot the data.

### Libraries Required

`numpy`
`matplotlib`
`pandas`
`seaborn`
`jupyter`

### Running the Notebooks

Execute the Jupyter notebook as usual, or view it directly on Github.

## Results
![](2022-02-23_output.png)
After a few months of tracking, we decided that the best course of action was to feed Jackie only Performatrin (i.e. no First Mate), as well as omitting supplements.


### Further improvements

The main plotting function contains a bunch of hard-coded values, and is worth refactoring if it were to be used for different cats/circumstances.
