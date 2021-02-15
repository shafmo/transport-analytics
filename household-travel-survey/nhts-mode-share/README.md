# Determine Mode Share From South African National Household Travel Data

The functions defined in this notebook are used to process the South African National Household Travel Survey. It allows the cleaning and processing of the NHTS person data. The NHTS data is generally clean and meachine readable, however much of the categorical data has been converted to numercal keys which are only defined in the accompanying meta data and can be difficult to analyse effectively. The following tools allow for easy visualisation of the dataset columns and processing of the data in order to determine modal split per transport analysis zone. The modal split summary produced is formatted to be used for further analysis in the PTV line of software but can be reworked for any 4 step transport modelling activity. It includes the walking, cycling, public and private transport main modes with various activity types and 5 income levels.  It should be read in conjuntion with the metadata files for the NHTS with detailed descriptions of each field.

## Examples

Below are a few examples of the exploratory plots. 


| **Description** | **Visualisation**|
| --------- | --------|
|Plot of the age of all respondants within the dataset. This can be further filtered for data from only the corresponding transport analysis zone whihc you are interested in| <img src = "https://i.postimg.cc/zv0S6swB/graph-D-AGE.png" width = "2000"> |
|Example of the resulting modal split for transport analysis zone 9017 of the national household travel survey data. The modal split is for the public transport, private transport, walking and cycling main modes. The respondents are split into 7 classes with 5 different income levels|<img src = "https://i.postimg.cc/zvtK0n5H/mode-share-9017.png" width = "2000">|


## Contact Me

|  |  |
| --- | --- |
| Email | hello@shafeeqm.co.za |
| LinkedIn | https://bit.ly/3jhErJA |
