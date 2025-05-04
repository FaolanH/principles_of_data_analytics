# principles_of_data_analytics

Contributed by Faolán Hamilton

## My submission for the Principles of Data Analytics module 2025

## This project is an analysis on the Iris dataset, investigating different ways the data can be shown and analysed. It also implements different packages and libraries from various sources, showing that even with a relatively simple dataset of 150 rows and 4 columns, it can be displayed in many ways.

## To view this repository in codesspaces, follow the steps below:

1. Sign up for a free GitHub account.
2. Go to the repository page in your browser.
3. Click the green 'Code' button.
4. Click the 'Codespaces' tab
5. Click 'Create New Codespace' on main

## Technologies used

- Python
- Git
- GitHub
- Codespaces
- Jupyter

## Documentation

### Pandas: https://pandas.pydata.org/docs/
#### - pandas, used throughout to create DataFrames, performing analysis
#### - Used in Task 2, 3, 4, 5, 6, 7, 8, 9, 10

### Scikit-learn: https://scikit-learn.org/stable/index.html
#### Machine learning library used to import one format of the dataset, perfomed calculations for certain tasks
#### Used in Task 1, 2, 6, 9

### Numpy: https://numpy.org/doc/
#### - numerical python (numpy) to help with calculations on arrays
#### - Used in Task 3, 6, 8, 9

### Matplotlib: https://matplotlib.org/stable/index.html
#### - matplotlib visualises data through charts
#### - Used in Task 4, 5, 6, 7, 8, 9

### Seaborn: https://seaborn.pydata.org/
#### - seaborn visualises complicated data through charts
#### - Used in Task 10

## Tasks

### 10 tasks were assigned as part of this module. These are broken down into further detail below:

### Task 1: Source the Dataset - using the sklearn.datasets module, the iris  dataset was imported and loaded in

#### Relevant Resources to view for Task 1:
#### iris dataset origins: https://www.geeksforgeeks.org/iris-dataset/
#### Packages: sklearn (see documentation section above for more details)

# 

### Task 2: Explore the Data Structure - the shape of the dataset, first and last five rows, feature names and target classes were investigated in this task

#### Relevant Resources to view for Task 2:
#### Pandas head and tail: https://pandas.pydata.org/docs/user_guide/basics.html#head-and-tail
##### Packages: sklearn, pandas (see documentation section above for more details)

#

### Task 3: Summarise the Data - show the mean, median, standard deviation, minimum and maximum of each feature in the dataset

#### Relevant Resources to view for Task 3:
#### page 47 of the numpy documentation showing the functions: https://numpy.org/doc/2.2/numpy-user.pdf
##### Packages: pandas, numpy (see documentation section above for more details)

# 

### Task 4: Visualise features - using matplotlib, plot histograms adding appropriate labels and headings to the plot.

#### Relevant Resources to view for Task 4:
#### Matplotlib has a relevant histogram to show all the potential additions: https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.hist.html
##### Packages: matplotlib, pandas (see documentation section above for more details)

# 

### Task 5: Investigate Relationships - Create a scatterplot for any two features in the dataset, colour code three different classes

#### Relevant Resources to view for Task 5:
#### If you are interested in learning more about how to plot graphs, consider going through the tasks on DataCamp on the Intermediate Python course: https://campus.datacamp.com/courses/intermediate-python/matplotlib?ex=1
##### Packages: pandas, matplotlib (see documentation section above for more details)

# 

### Task 6: Analyse Relationships - add a regressions line to the scatterplot from task 5

#### Relevant Resources to view for Task 6:
#### see this interesting article on geeksforgeeks to see how numply.polyfit works: https://www.geeksforgeeks.org/numpys-polyfit-function-a-comprehensive-guide/#1-linear-fit
##### Packages: sklearn, pandas, numpy, matplotlib (see documentation section above for more details)

# 

### Task 7: Analyse class distributions - create boxplots for each of the three classes

#### Relevant Resources to view for Task 7:
#### See other examples of boxplots and what additions can be made on the matplotlib boxplot page: https://matplotlib.org/stable/gallery/statistics/boxplot_color.html#sphx-glr-gallery-statistics-boxplot-color-py%20fig,%20ax%20=%20plt.subplots()%20#%20Setting%20the%20labels%20labels%20=%20['setosa',%20'versicolor',%20'virginica']%20#%20For%20this%20one%20specifically,%20I%20did%20not%20need%20to%20assign%20the%20colours%20the%20species%20colours%20=%20['#5A4FCF','#AC37B2',%20'#8B85E0']%20#%20Setting%20an%20appropriate%20title%20(I%20originally%20learned%20this%20method%20on%20DataCamp)%20plt.title%20('Iris%20Species%20by%20Petal%20Length')%20#%20Setting%20the%20x%20axis%20label%20plt.xlabel%20('Iris%20Species')%20#%20Setting%20the%20y%20axis%20label%20plt.ylabel%20('Petal%20Length')%20#%20Setting%20a%20background%20grid%20for%20more%20clarity%20plt.grid(True)%20#%20as%20referenced%20above,%20I%20learned%20the%20below%20method%20for%20assigning%20colours%20on%20the%20matplotlib%20gallery%20bplot%20=%20ax.boxplot%20(petal_length,%20tick_labels%20=%20labels,%20patch_artist=True);%20for%20patch,%20color%20in%20zip(bplot['boxes'],%20colours):%20patch.set_facecolor(color)
##### Packages: pandas, matplotlib (see documentation section above for more details)

# 

### Task 8: Compute correlations - calculate coefficient correlations between features through a heatmap

#### Relevant Resources to view for Task 8:
#### See this article on interesting ways to display heatmaps: https://www.geeksforgeeks.org/matplotlib-colors-colormap-class-in-python/
##### Packages: pandas, numpy, matplotlib (see documentation section above for more details)

# 

### Task 9: Fit a simple linear regression - re-create the plots from task 5 and 6 and calculate the coefficient of R2

#### Relevant Resources to view for Task 9:
#### Understand coefficient of determination of r squared: https://www.statology.org/r-squared-in-r/
##### Packages: sklearn, pandas, numpy, matplotlib (see documentation section above for more details)

# 

### Task 10: Too many features - Create a pairplor using seaborn

#### Relevant Resources to view for Task 10:
#### Understand the pariplot method through this interesting article: https://www.geeksforgeeks.org/python-seaborn-pairplot-method/ 
##### Packages: seaborn, pandas (see documentation section above for more details)


# END 