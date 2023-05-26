 # R Data Analysis Library

## Description
This repository is a collection of R scripts for analysis and prediction of diabetes in women of Pima Indian descent over the age of 21. The data used for the study is collected by the National Institute of Diabetes and Digestive and Kidney Diseases. 

The aim of this analysis is to determine if a woman has diabetes based on predictors such as blood glucose levels, blood pressure, number of pregnancies, insulin levels, BMI, age, skin thickness, and genetics (called diabetes pedigree function).

## Getting Started

### Dependencies

- This project uses the `tidyverse` and `tidymodels` libraries, which are essential collections of R packages used for data science. They can be installed with `install.packages("tidyverse")` and `install.packages("tidymodels")` respectively.
- The `repr` package is also required and can be installed with `install.packages("repr")`.

Please note that all used packages need to be installed and loaded in your R environment to successfully run the code in this repository.

### Files

The following scripts are included in the repository:

- `tests.R`: This script contains unit tests for the functions used in the data analysis process. Currently, the file is not available in the repository.
- `cleanup.R`: This script performs cleanup tasks on the data.

### How to Use

1. Clone this repository to your local machine.
2. Open the R scripts in your preferred IDE (RStudio is recommended).
3. Make sure to set your working directory to the location of the cloned repository.
4. Run the scripts. 

## Results

Results of the exploratory data analysis include various statistical summaries of the data, such as mean, max and min of the different predictors and outcome. 

## Errors and Warnings

During the script execution, you may encounter some warning messages related to package versions and conflicts between functions. They are mostly harmless but can lead to unexpected behaviour in some cases.

There's also a message indicating that the `tests.R` file could not be found. This file is meant to contain the tests that ensure the scripts are running as expected, so please make sure this file is present in the same directory where you run the scripts from.

## Future Work

Future updates of the repository will include:
- Adding unit tests for the functions.
- Resolving the conflicts between the loaded packages.
- Updating the scripts to use the latest version of the packages.
- Including scripts for data modeling and prediction.

## Contact

For questions and suggestions, please open an issue on this repository. Contributions to the project are welcomed.

## References

1. Tidyverse: https://www.tidyverse.org/
2. Tidymodels: https://www.tidymodels.org/
3. Data source: National Institute of Diabetes and Digestive and Kidney Diseases.
