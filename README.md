# Liquor Rating Forecasting

The work of a one-month internship. Goal was to detect the human with only the distance (in mm f.e) as input.

---
## Table of contents
* [General info](#general-info)
* [Methods](#methods)
* [Summary](#summary)
* [Interactive Heroku App](#interactive-heroku-app)

---

## General info
25 schnapps were exhibited at a schnapps fair and rated by a jury with points in four different categories. The most important chemicals for the end result should be collected in order to be able to give the distillers a guideline as to how good schnapps from previous years were chemically structured. Basically, it should be possible to draw conclusions about the jury evaluation with as few parameters as possible. This was done using several techniques from data science. Ultimately, the four different categories could be predicted with an accuracy of 96%, 84%, 92% and 96%, respectively. This result was achieved with the help of only 2, 3, 3, or 2 transformed features.

---
## Methods
Different methods were considered in order to get to a solution. Mainly the following methods were chosen:

- Autoencoder
- PCA
- PLS
- UMAP
- XGBoost
- Basic Neural Network

---
## Summary
A summary can be seen when downloading the files folder and opening [Results.html](files/Results.html)

---
## Interactive Heroku App
An interactive app can be see at https://schnaps.herokuapp.com/
