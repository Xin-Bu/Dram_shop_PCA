# The Dram Shop Principal Component Analysis (PCA)
 ![The-Dram-Shop](https://github.com/Xin-Bu/Dram_shop_PCA/assets/69817896/06deb648-b53c-4017-9599-4ffe1ebe44c5)

[Image source](https://missoulaunderground.com/guide/the-dram-shop/)

### Introduction
This is a project from my Applied Data Analytics course, a core course from my Master of Science in Business Analytics (MSBA) Program at the University of Montana. The purpose of this project is to better understand the Dram Shop customers' purchasing behavior by applying PCA to dimensionality reduction.

The Dram Shop is a local craft brewing company located at Missoula, MT, with its two locations: the Dram Shop Downtown and the Dram Shop Central. It has more than three dozen regional craft beer and wine offerings and is the first of its kind in the state. 

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
