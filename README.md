# Analysis to Predict Close Stock Prices for Company AT&T

## Authors:
- Victor Yung [Github](https://github.com/vyung96)
- Benson Ou-yang [Github](https://github.com/bensonouyang)
- Ivan Cao [Github](https://github.com/ivancao98)

## Table of Contents
* [Introduction](#introduction)
* [Technologies](#technologies)
* [Setup](#setup)
* [Usage](#usage)
* [Features](#features)
* [Source](#source)

## Introduction
Multiple linear regression analysis using R to predict the market close stock price with volume, capital surplus, gross margin and liabilities of company AT&T. Report with an abstract, introduction, data description, methods, results, conclusion and appendix made in R Markdown using Latex.

## Technologies
Project is created with:
* R/R Markdown
* Latex

## Setup
To run this project:
* Download the files [here](https://github.com/bensonouyang/NYStocks.git) in cmd
```sh
git clone https://github.com/bensonouyang/NYStocks.git
```

Required Libraries in R:
* Install the necessary packages

  - lubridate
  ```sh
  install.packages("lubridate")
  ```
  - tidyverse
  ```sh
  install.packages("tidyverse")
  ```
  - faraway
  ```sh
  install.packages("faraway")
  ```
  - caret
  ```sh
  install.packages("caret")
  ```
  - reshape2
  ```sh
  install.packages("reshape2")
  ```
  - car
  ```sh
  install.packages("car")
  ```
  - knitr
  ```sh
  install.packages("knitr")
  ```
  - bookdown
  ```sh
  install.packages("bookdown")
  ```

## Usage
To run the code and see results:
* Open [rawcode.Rmd](https://github.com/bensonouyang/NYStocks/blob/main/rawcode.Rmd) in R Studio

To see the report:
* Open [atntReport.pdf](https://github.com/bensonouyang/NYStocks/blob/main/atntReport.pdf) for PDF version
* Open [atntReport.Rmd](https://github.com/bensonouyang/NYStocks/blob/main/atntReport.Rmd) to see code with the report
 
## Features

<p align="center">
  <a href="https://raw.githubusercontent.com/bensonouyang/NYStocks/main/Figs/c-plot-1.png">
    <img src="Figs/c-plot-1.png">
  </a>
</p>

<p align="center">
  <a href="https://raw.githubusercontent.com/bensonouyang/NYStocks/main/Figs/pred-plot.png">
    <img src="Figs/pred-plot.png">
  </a>
</p>

## Source
[New York Stock Exchange Kaggle Competition](https://www.kaggle.com/dgawlik/nyse)
