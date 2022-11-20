# IRIS-Visualisation-and-insights
The Iris flower data set is one of the most famous multivariate data. The Iris Dataset contains four features (length and width of sepals and petals) of 150 samples of three classes of Iris (Iris setosa, Iris virginica and Iris versicolor), where each class refers to a type of iris plant. These measures were used to create a linear discriminant model to classify the species.
depending on the lenghts and widths the iris flower has 3 types.
This dataset is a balanced dataset.

![image](https://user-images.githubusercontent.com/93968996/202888103-41bdfae6-6702-42a7-ae1b-fa4d6cde7f05.png)


OBJECTIVE OF THIS PROJECT:

1) This problem statement comes under multiclass classification – as we need to identify the type of Species based on petal length and width,sepal length and width.


DATA-PREPROCESSING AND ANALYSIS:

1) Import the required libraries. 
2) Importing the dataset.
3) Read the data frame and try to understand the attributes and datatypes, and we have to check for 
any missing values.
4) No Null values in dataset
5) Four columns are numerical type - independent features
6) Only Single column categorical type - dependent feature


VISUALIZATION PLOTS:

1) countplot

2) Joint plot : Jointplot is seaborn library specific and can be used to quickly visualize and analyze the relationship between two variables and describe their individual distributions on the same plot.

3) FacetGrid Plot

4) boxplot : gives the information of descriptive statistics of  each numerical features.

5) Strip plot

6) Combining Box and Strip Plots

7) Violin Plot : It is used to visualize the distribution of data and its probability distribution.This chart is a combination of a Box Plot and a Density Plot that is rotated and placed on each side, to show the distribution shape of the data. The thick black bar in the centre represents the interquartile range, the thin black line extended from it represents the 95% confidence intervals, and the white dot is the median.Box Plots are limited in their display of the data, as their visual simplicity tends to hide significant details about how values in the data are distributed

8) Pair Plot : A “pairs plot” is also known as a scatterplot, in which one variable in the same data row is matched with another variable's value, like this: Pairs plots are just elaborations on this, showing all variables paired with all the other variables.

9) Heat map : Heat map is used to find out the correlation between different features in the dataset. High positive or negative value shows that the features have high correlation.This helps us to select the parmeters for machine learning.

10) Distribution plot :The distribution plot is suitable for comparing range and distribution for groups of numerical data. Data is plotted as value points along an axis. You can choose to display only the value points to see the distribution of values, a bounding box to see the range of values, or a combination of both as shown here.The distribution plot is not relevant for detailed analysis of the data as it deals with a summary of the data distribution.

11) Plotting the Histogram & Probability Density Function (PDF)

12) Swarm plot : It looks a bit like a friendly swarm of bees buzzing about their hive. More importantly, each data point is clearly visible and no data are obscured by overplotting.A beeswarm plot improves upon the random jittering approach to move data points the minimum distance away from one another to avoid overlays. The result is a plot where you can see each distinct data point, like shown in below plot

13) LM PLot

14) Factor Plot :  the points represent the average point of SepalLengthCm for a species

15) Stacked Histogram

16) Area Plot : Area Plot gives us a visual representation of Various dimensions of Iris flower and their range in dataset.

17) Distplot : It helps us to look at the distribution of a single variable.Kde shows the density of the distribution


INSIGHTS OF THE DATASET:

![image](https://user-images.githubusercontent.com/93968996/202889642-bdba785a-e913-491f-9125-a48d7bac2468.png)


     The pdf curve of Iris Setosa ends roughly at 2.1.

     If petal length < 2.1, then species is Iris Setosa.

     The point of intersection between pdf curves of Versicolor and Virginica is roughly at 4.8.

     If petal length > 2.1 and petal length < 4.8 then species is Iris Versicolor.

     If petal length > 4.8 then species is Iris Virginica.


