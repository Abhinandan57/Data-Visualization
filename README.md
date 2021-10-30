# Data-Visualization

# Using Seaborn
__1. Numerical Data Ploting__
- relplot()
- scatterplot()
- lineplot()  

__2. Categorical Data Ploting__
- catplot()
- boxplot()
- stripplot()
- swarmplot()  

__3. Visualizing Distribution of the Data__
- distplot()
- kdeplot()
- jointplot()
- rugplot()  

__4. Linear Regression and Relationship__
- regplot()
- implot()  

__5. Controlling Ploted Figure Aesthetics__
- figure styling
- axes styling
- color palettes

# Univariate Analysis
- Univariate analysis is the simplest form of analysis where we explore a single variable.
- We perform Univariate analysis of Numerical and categorical variables differently because plotting uses different plots.

## Categorical Data:
__1. CountPlot__  
- Countplot is basically a count of frequency plot in form of a bar graph.
- It plots the count of each category in a separate bar.
- When we use the pandas’ value counts function on any column, it is the same visual form of the value counts function.

__2. Pie Chart__  
- The pie chart is also the same as the countplot, only gives you additional information about the percentage presence of each category in data means which category is getting how much weightage in data.

## Numerical Data
__1. Histogram__  
- A histogram is a value distribution plot of numerical columns.
- It basically creates bins in various ranges in values and plots it where we can visualize how values are distributed.
- We can have a look where more values lie like in positive, negative, or at the center(mean).

__2. Distplot__  
- Distplot is also known as the second Histogram because it is a slight improvement version of the Histogram.
- Distplot gives us a KDE(Kernel Density Estimation) over histogram which explains PDF(Probability Density Function) which means what is the probability of each value occurring in this column.

__3. Boxplot__  
- A box plot (or box-and-whisker plot) shows the distribution of quantitative data in a way that facilitates comparisons between variables or across levels of a categorical variable.
- The box shows the quartiles of the dataset while the whiskers extend to show the rest of the distribution, except for points that are determined to be “outliers” using a method that is a function of the inter-quartile range.

# Bivariate/ Multivariate Analysis
- Bivariate Analysis is used when we have to explore the relationship between 2 different variables and we have to do this because, in the end, our main task is to explore the relationship between variables to build a powerful model.
- When we analyze more than 2 variables together then it is known as Multivariate Analysis.

## Numerical and Numerical
__1. Scatter Plot__  
- To plot the relationship between two numerical variables scatter plot is a simple plot to do.

## Numerical and Categorical
__1. Bar Plot__  
- Bar plot is a simple plot which we can use to plot categorical variable on the x-axis and numerical variable on y-axis and explore the relationship between both variables.
- The blacktip on top of each bar shows the confidence Interval.

__2. Boxplot__  
- We can draw a separate boxplot for both the variable.

__3. Distplot__  
- Distplot explains the PDF function using kernel density estimation.

## Categorical and Categorical
__1. Heatmap__  
- It basically shows that how much presence of one category concerning another category present in the dataset.

__2. Cluster map__  
- We can also use a cluster map to understand the relationship between two categorical variables.
- A cluster map basically plots a dendrogram that shows the categories of similar behavior together.


# Using Plotly
Plotly is a library that allows you to create interactive plots that you can use in dashboards or websites.
