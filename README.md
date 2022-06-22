# **dataxray:** An Interactive Table Interface for Data Summaries
### [useR! 2022: Session 20, Data Visualization](https://user2022.r-project.org/program/talks/#session-20-data-visualization)
### Wednesday, 22 June 2022
### **Stephanie Lussier** + **Agustin Calatroni**

### Abstract

>Every time a dataset is created, either for data management purposes or for statistical analyses, it is imperative that each variable be reviewed to detect potential errors. Not only should the evaluation involve summary statistics and graphical displays, but it should also present the results in a thorough and succinct manner.

> Originally developed a couple of decades ago, the `Hmisc::describe` function has been a useful tool for data exploration prior to analysis. `Hmisc::describe` provides key information about input datasets, including variable attributes and summary statistics, using a concise print method to create a static report (HTML or PDF). It also provides the ability to interface SAS formatted datasets, which remain widely used in the clinical research industry, while the R language continues to grow in popularity.

> For some time now, we have wanted to provide a wrapper for the aforementioned describe function to provide a modern and interactive interface to the `Hmisc::describe` output. Utilizing the power of the reactable package embedded with plotly interactive figures within a `flexdashboard`, concise summaries of every variable in a dataset can be generated with minimal user configuration. In order for other users to readily deploy such a powerful summary table, we wrapped our work into the `dataxray` package.

