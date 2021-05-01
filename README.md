# Noise-effects-on-classifiers
How Noise effects different types of classifiers

<b>Table of Contents:</b>
<b>Libraries Used:</b>
<b>Files Description</b>
<b> Datasets</b>
<b> Results </b>



<b>Libraries Used:</b>
The project was done on Jupyter Notebook and Python 3.0, below are the libraries used:
1. Matplotlib
2. Seaborn
3. Pandas
4. Numpy
5. Sklearn

<b>Dataset:</b>
1. preg: Number of times pregnant
2. plas: Plasma glucose concentration a 2 hours in an oral glucose tolerance test 3. pres: Diastolic blood pressure (mm Hg)
4. skin: Triceps skin fold thickness (mm)
5. insu: 2-Hour serum insulin (mu U/ml)
6. mass: Body mass index (weight in kg/(height in m)^2)
7. pedi: Diabetes pedigree function
8. age: Age (years)
9. class: Class variable (0 or 1)

<b>Domain Background:</b>
The task is to test the diabetes data set, and see how different classifiers get affected when we intentionally add noise to the data set. This should test the robustness of different classifiers. The test is performed on KNN,Decsion Trees (DT) and Neural nets (NN). The noise is added in increments of 2% up to 30%.

<b>Results:</b>
 As seen in the image below, the DT and KNN quickly degraded in prediction power, but NN started low and kept a steady accuracy throughout the increments.
 This should how robust NN are when noise is available in the data set. But then NNs are uninterpretable and require large optimization power


![Heat map](noise/bar_chart.png)



