
Consider a CSV file of the Breast Cancer Wisconsin dataset with the following columns:
~~~csv
id,diagnosis,radius_mean,texture_mean,perimeter_mean,area_mean,smoothness_mean,compactness_mean,concavity_mean,concave points_mean,symmetry_mean,fractal_dimension_mean,radius_se,texture_se,perimeter_se,area_se,smoothness_se,compactness_se,concavity_se,concave points_se,symmetry_se,fractal_dimension_se,radius_worst,texture_worst,perimeter_worst,area_worst,smoothness_worst,compactness_worst,concavity_worst,concave points_worst,symmetry_worst,fractal_dimension_worst
~~~

Write the simplest Python + Pandas program over Jupyter to do the following:

1. read this CSV file named breast-cancer-wisconsin.csv
2. find two clusters in the data using K-means, considering all table columns except `id` and `diagnosis`
3. draw a scatter plot with the following characteristics:
  3.a. axis X and Y are radius_mean and fractal_dimension_mean
  3.b. points in the scatter plot are colored according to the `diagnosis` column, with has two values: B and M
  3.c.the shape of the points in the scatter plot varies according to the K-means cluster



Consider a CSV file of the Breast Cancer Wisconsin dataset with the following columns:
~~~csv
id,diagnosis,radius_mean,texture_mean,perimeter_mean,area_mean,smoothness_mean,compactness_mean,concavity_mean,concave points_mean,symmetry_mean,fractal_dimension_mean,radius_se,texture_se,perimeter_se,area_se,smoothness_se,compactness_se,concavity_se,concave points_se,symmetry_se,fractal_dimension_se,radius_worst,texture_worst,perimeter_worst,area_worst,smoothness_worst,compactness_worst,concavity_worst,concave points_worst,symmetry_worst,fractal_dimension_worst
~~~

*Interaction:*

Write the simplest Python + Pandas program over Jupyter to do the following:
1. read a CVS file named `breast-cancer-wisconsin.csv`
2. draw a scatter plot of the columns: `radius_mean` vs `fractal_dimension_mean`

Change the color of the bullets according to the value of `diagnosis`, which can be `B` or `M`?

*Result:*