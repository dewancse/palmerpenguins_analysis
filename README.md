# Analysis of penguins measurements

This project aims at understanding the differences between the size of three species of
penguins (Adelie, Chinstrap and Gentoo) observed in the Palmer Archipelago, Antarctica.
The data was collected by Dr Kristen Gorman between 2007 and 2009.

## Key contributors

- Jane Doe: project leader

- Kristen Gorman: data collection

- Dewan Sarwar: data analysis

## Input data

The raw penguins measurements, stored in the `penguins_raw.csv` file, were downloaded from the 
[`palmerpenguins` package](https://allisonhorst.github.io/palmerpenguins/index.html).

Data source: [...]

## Analysis

- Data cleaning: a cleaned version of the dataset was saved as `penguins_cleaned.csv` on
[OneDrive](path/to/OneDrive/folder).

- *To be filled*

## Repository content

- `renv.lock`: list of packages used in the analysis (and their version)
- `analysis/`: collection of `R` scripts containing the analysis code
- `R/`: collection of `R` scripts containing helper functions used for the analysis
- `reports/`: collection of `Quarto` documents used to generate the reports

## How to reproduce the analysis

```{r}
# Install the necessary packages
renv::restore()
```