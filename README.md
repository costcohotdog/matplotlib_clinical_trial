# Matplotlib Challenge 
Using matplotlib to analyze results from test clinical trial data (`clinicaltrial_data.csv` and `mouse_drug_data.csv` found in `data`).

## Primary Objectives
For the drugs Capomulin, Infubinol, Ketapril, and Placebo:
* Creating a scatter plot that shows how the tumor volume changes over time for each treatment.
* Creating a scatter plot that shows how the number of [metastatic](https://en.wikipedia.org/wiki/Metastasis) (cancer spreading) sites changes over time for each treatment.
* Creating a scatter plot that shows the number of mice still alive through the course of treatment (Survival Rate)
* Creating a bar graph that compares the total % tumor volume change for each drug across the full 45 days.

### Data Format
Using Pandas and a user function, the merged dataframe was converted to the following format to prepare for plotting. This allows quick and easy formatting for the following plots:

![dataframe format](https://github.com/L0per/Matplotlib-Challenge/blob/master/Pymaceuticals/dataframe_format.JPG?raw=true)

### Tumor Response to Treatment
Capomulin was the only drug that demonstrated a decrease in tumor size:

<img src="https://github.com/L0per/Matplotlib-Challenge/blob/master/Pymaceuticals/Tumor_Response_to_Treatment.jpeg?raw=true" width="75%" height="75%">

### Metastatic Spread During Treatment
While Capomulin minimized metastatic spread, it did not hault or reverse it:

<img src="https://github.com/L0per/Matplotlib-Challenge/blob/master/Pymaceuticals/Metastatic_Spread_During_Treatment.jpeg?raw=true" width="100%" height="100%">

### Survival Rate During Treatment
Capomulin had the highest survival rate of the drugs:

<img src="https://github.com/L0per/Matplotlib-Challenge/blob/master/Pymaceuticals/Survival_During_Treatment.jpeg?raw=true" width="100%" height="100%">

### Tumor Volume Change
An alternative visualization of the change in tumor size over the 45 days of treatment (tumor response to treatment):

<img src="https://github.com/L0per/Matplotlib-Challenge/blob/master/Pymaceuticals/Tumor_Change_Over_Time.jpeg?raw=true" width="75%" height="75%">
