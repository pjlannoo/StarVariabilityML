# StarVariabilityML

## Overview



## Buisness Problem
Nasa is planning to observe the stars that the European Space Agency's astrometric satellite, Hipparcos, observered from August 1989 to August 1993. Specificaly they want to determine whether stars that have unkown variablity are variable stars and what type of variable star they are. We are tasked with coming up with a list of stars that are likely to be variable so that Nasa does not waist time and money on observing stars that are not variable. However Nasa would rather observe a few more stars than miss a variable star. So, we will focus on minimizing false negatives.


## Data Understanding
For this project, we used data collect from The European Space Agency's astrometric satellite, Hipparcos. The data contained two portions one were the target(Variablity) is null and another were the target is not null. These two portions were sepperated into two sets of data the UntestableData.csv and UsableData.csv. The UsableData.csv was used to train and test all of our models. The our final model was used on the UntestableData.csv to given nasa a list of stars that are likely variable.

## Methods

### Data Preparation

### Modeling

## Results

## Conclusion

## Future Work

## For More Information

## Repository Structure

```
├── Notebooks                                               <- Rough Working Directory
|   ├── ConnorWorkSpace
|   |   ├── Cleaning.ipynb                                  <- Rough Jupyter Notebook: Cleaning
|   |   └── Models.ipynb                                    <- Rough Jupyter Notebook: Models
|   ├── PhilWorkspace                                       
|   |   └── WorkNotebook.ipynb                              <- Rough Jupyter Notebook
|   ├── ColumnDescriptions.ipynb                            <- Brief Description of all Columns
|   └── DataSeparation.ipynb                                <- Seperating out the Data: Train and Test
├── data                                                    <- Rough Working Directory
|   ├── UntestableData.csv                                  <- Nulls in the Target
|   ├── UsableData.csv                                      <- Non-Nulls in the Target
|   └── hipparcos-voidmain.csv                              <- Unsplit Data
├── .gitignore                                              <- Standard python gitignore file
├── Presentation.pdf                                        <- Final Slides Presentation
├── Final NoteBook.ipynb                                    <- Final Jupyter Notebook
└── README.md                                               <- You Are Here   X
```

