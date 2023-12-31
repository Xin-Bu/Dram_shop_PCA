# The Dram Shop Principal Component Analysis (PCA)
![Dram Shop](https://github.com/Xin-Bu/Dimensionality_reduction_dram_shop/assets/69817896/7c301277-bfb9-4f36-8069-f83e494106ff)

[Image source](https://dramshopmt.square.site/)

### Introduction
This is a project from my Applied Data Analytics course, a core course from my Master of Science in Business Analytics (MSBA) Program at the University of Montana. The purpose of this project is to better understand the Dram Shop customers' purchasing behavior by applying PCA for dimensionality reduction.

The dram shop is a local craft brewing company located at Missoula, MT, with its two locations: the Dram Shop Downtown and the Dram Shop Central. It has more than three dozon regional craft beer and wine offerings and is the first of its kind in the state. 

### The procedures
* Write a SQL query in Google Big Query (GBQ) that returns the values of `beverage` with the top 1000 gross sales totals.
* Write a SQL query built off the previous one that returns three columns: `customer ID`, `beverage` and `total sales`.
* Use the pandas function `pivot`, pivot the data into a 'wide' format with `customer ID` as the rows and `beverage` as the items.
* Use the `PCA` function from `sklearn.decomposition`, and perform a PCA on this dataset.
* Plot the amount of explained variation in the first 20 components.
* For each of the first 6 components, print the items with the 15 largest loadings in absolute value. 

### Data source
[The Dram Shop](https://www.dramshopmt.com/)

### Reference
[The Missoula Underground](https://missoulaunderground.com/guide/the-dram-shop/) 
