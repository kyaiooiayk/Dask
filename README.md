# Dask
![image](https://user-images.githubusercontent.com/89139139/213912660-4cbe017d-defb-4673-8e2d-1f93c1693c2d.png)

***


## Dask vs. Pandas
- Do we still need Pandas since PySpark sounds super? The answer is “Yes, definitely!” There are at least two advantages of Pandas that PySpark could not overcome:
    - stronger APIs
    - more libraries, i.e. matplotlib for data visualization
- In practice, convert Spark DataFrame to a Pandas DataFrame using method toPandas() with optimization with Apache Arrow ONLY for those a small subset of the data. For example, the subset of the data you would like to apply complicated methods on, or the data you would like to visualize.
***

## Available tutorials
- [Dask and XGBoost]()
***

## References
- [Distributed XGBoost with Dask](https://xgboost.readthedocs.io/en/stable/tutorials/dask.html)
***
