# Quantitative Investment Research (Smart Factor) : Earnings Per Share (EPS) by  Market Value (MV)

## Overview
Entrepreneurs and investors put their time and money into businesses with the idea of making profits, so it should not be surprising that earnings growth drives stock market returns. 

This repository is home to files used in conducting a 5 level Quintile Research where i try to determine the relationships between the Earnings per share growth and Market Value of specific quintiles.Quintiles here is defined by splitting relevant data (first factor) eg. market value, free cash flow per share, earnings per share etc. into a number of portfolios which is used as reference for our second factor.

## How to Replicate the Research
1. Download and Edit the dataset paths as needed
2. Download and Edit the modules path as needed
3. Run the main python file (stated below)

> ......../EPS/templates/Market Value by Earnings per Share.py

Alternatively, you can clone the repository and restructure as necessary. Via 
the command line,

```
> git clone git@github.com:QuizeCapital/EPS 
```
## Layout

The repository is split into five main directories,which may/may not have subdirectories. This structure has been designed to be easily navigable by humans and computers alike, allowing for rapid location of specific files and instructions. Within each directory is a `README.md` file which summarizes the purpose of that directory as well as some examples where necessary. Each section is briefly described below. 

<!--  * **`exploratory`**: A sandbox where you keep a record of your different approaches to transformation, interpretation, cleaning, or generation of data.
 * **`figures`**: Any code used to generate figures for your finished work, presentations, or for any other use. -->

### **`data`** 
This directory houses all small (< 100 MB) data sets that are a result of API downloads from different sources. All datasets are mostly sourced from https://site.financialmodelingprep.com/developer/docs/. 
### **`miscellaneous`** 
Files that may not be code, but are important for reproducibility of this project's findings. This includes pictures, screenshots , research papers, books, important links etc

### **`Results and Comments`** 
Summary of Results and comment resulting for the code. Some research work is just a means to an end so comments might include the feasibility of practical usage of the research or feasibility of future research building on this . An example of an out put file:

<div align="center">
    <img src="/miscellaneous/Results output.png" width="400px"</img> 
</div>

Benchmark for judging good Quantitative Smart Factor strategy:

* **Significant outperformance for the top quintile** : For single-factor strategies, which have large average portfolio sizes (usually over 300 companies), I like to see at least a 2% average excess return for the top quintile versus the Universe. For more focused, two-factor strategies, excess returns of 4% or more are preferable.
* **Significant underperformance of the bottom quintile** : For single-factor strategies, the bottom quintile should underperform the benchmark by 2% or more on average (i.e., excess returns should be (2%—negative 2%—or lower); for two- factor strategies, 4% underperformance or more. If a strategy is to be used for short sales, underperformance of 8% to 10% or more is preferable.
* **Good linearity of excess returns among the quintiles** : This means that the top quintile should outperform the second quintile, which should outperform the third quintile, and so on. The smoother, or more linear, the trend of excess returns, the higher my assurance that the strategy really works (i.e., that it is a general, well-founded strategy that works for many stocks and not a statistical anomaly).12
* **Strong consistency of returns over time** : The top quintile of a strategy should outperform the Universe for 60% or more of the annual periods tested. Strategies that outperform 70% or more are preferable.13 The bottom quintile should underperform the Universe by 60% or more. Again, 70% under- performance or higher is preferable. Along with this, I’d much prefer a strategy that provided consistent but moderate excess returns over the years to

### **`Code`** 
Custom code  written that is executed directly and some code that is called from files in the other directories. 

### Other Files
These are files considered to be mandatory for this project.

1. **`LICENSE`**: A legal protection of your work.

2. **`README.md`**: A descriptive yet succinct description of this research project and information regarding the structure outlined.

# License Information

<p xmlns:dct="http://purl.org/dc/terms/" xmlns:vcard="http://www.w3.org/2001/vcard-rdf/3.0#">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />
  To the extent possible under law,
  <a rel="dct:publisher"
     href="https://github.com/QuizeCapital/EPS">
    <span property="dct:title">Zequi Adams</span></a>
  has waived all copyright and related or neighboring rights to
  <span property="dct:title">Quantitative Investment Research (Smart Factor) : Earnings Per Share (EPS) by Market Value (MV)</span>.
This work is published from:
<span property="vcard:Multiple Countries" datatype="dct:ISO3166"
      content="US" about="https://github.com/QuizeCapital/EPS">
  Multiple Countries</span>.
</p>