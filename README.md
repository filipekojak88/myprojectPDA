# myprojectPDA      

This repository contains a project completed for the module of Principles of Data Analytics in ATU with the lecturer Ian McLoughlin.    
Througout this project there were several Python scripts that were used in Jupyter notebook to highlight the different skills acquired during the course.   
This README has been written with [Github's documentation on READMEs](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes) in mind [[1]](#1).     
MarkDown was used in this README file and was based on [in GitHub's Documentation](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) [[2]](#2).       

## About This Project

In this project an analysis has been completed using the data from Palmer Penguins dataset.

The Palmer Penguins dataset is like a treasure trove of information about penguins living near Antarctica. It helps scientists understand how male and female penguins differ in what they eat and how they hunt for food, especially when there's less sea ice around. By studying their diets and body sizes, researchers can figure out why males and females might prefer different hunting spots [[3]](#3) [[4]](#4).      

This dataset is super handy because it's not just for scientists—it's also great for teaching and learning about data analysis. It's like replacing an old, not-so-interesting dataset with something way cooler and more relevant. Plus, it's been downloaded tons of times, showing how popular and useful it is for anyone wanting to explore the world of data science [[5]](#5).     

This data was collected near the Palmer Station in Antarctica from penguins:        
- on three different islands: Dream, Torgersen and Biscoe.           

![Antarctica](images/p_station.png)     
*Palmer Station in Antarctica* [[6]](#6)     

- from three difference species: Chinstrap, Gentoo and Adélie.    

![Penguins](images/penguins.png)    
*Penguins species: Chinstrap (Pygoscelis antarctica), Gentoo (Pygoscelis papua), and Adélie (Pygoscelis adeliae)*  [[7]](#7) [[8]](#8) [[9]](#9)       

- 4 measurements were taken from each penguin: body mass (g), bill length (mm), bill depth (mm), and flipper length (mm).          

![Measurements](images/measurement.png)     
*Penguins measurements: bill length, bill depth, flipper length* [[10]](#10)    

The Jupyter notebook [penguins.ipynb](penguins.ipynb) displays the data analysis completed using the Palmer Penguins dataset.         
The [penguin csv file](https://raw.githubusercontent.com/mwaskom/seaborn-data/master/penguins.csv) used for this analysis was from the [Seaborn](https://github.com/mwaskom/seaborn)'s repository as recommended on the Assessment Instructions for the module of Principles of Data Analytics [[11]](#11) [[12]](#12) [[13]](#13).     

## Use of this project

This project is useful for other users as a source of examples of data analysis that can be completed using Python, and direct them on some conclusions that can be drawn from the data.
Perhaps, the perspective adopted in this project can be also adapted by other students to investigate different datasets.
Nonetheless, this project reflects the author's understanding and knowledge from the Python programming skills learned so far in this course. Therefore, any contribution or ideas to improve this project will be always welcomed.     

## Get Started 

To get started with this project click on this link '[penguins.ipynb](penguins.ipynb)' and navigate through the different sections of this Jupyter from the beginning to the end. But, if you prefer to go to a specific section, then here you can get a quick overview of what is covered:     
- <ins>Loading the Database</ins>: This section displays the different imported Python modules used in the analysis of the penguins dataset and the script used to load the data set from the Seaborn repository in GitHub.        
- <ins>Exploring the Dataset</ins>: A quick look into the datase to understand the columns and some of the first and last rows of the dataset.
- <ins>Types of Variables to Model the Data Set</ins>: Here the author checks the types of variables used in the dataset and what type can be used to model it.
- <ins>Categorical Data and Bar Chart</ins>: An analysis is provided into one of the categorical variables and the different categories available within that variable, using a bar chart to ilustrate that.
- <ins>Continuous Numerical Data and Histogram</ins>: A summary statistic is perfomed to all continuous numerical variables of the dataset and a deep dive is completed into one of the variables, ending with a histrogram and more details of this analysis.
- <ins>Correlation between Penguins' bill length and flipper length</ins>: In this section, the author explores how two continuous variables of the dataset correlates to each other. A scatterplot is used and concepts as best fit line and correlation coeficient are applied to support this analysis.
- <ins>Conclusion</ins>: A summary and results of the author's analysis and investigation carried out on the Palmer Penguins dataset. 
- <ins>Opportunities for further investigation</ins>: Here, the author suggests other areas that users can approach to further analyse the dataset.
- <ins>References</ins>: Full list of references, so you can refer to for more info.

## Get Help

If questions are raised while checking this project, you can contact me via github, and I will be happy to provide more information.
I have also provided the list of references used in this project at the end of both, this README.md file and the Jupyter notebook penguins.ipynb, which can provide further insights into the structure and fundamentals used to build this project.        

## Contribute

I sed [openincolab.com](https://openincolab.com) to generate the following clickable link.      
It opens the 'fib.ipynb' notebook in [Google Colab](https://colab.research.google.com)

<a target="_blank" href="https://colab.research.google.com/github/filipekojak88/demo-repo/blob/main/fib.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

## Author

I am currently a Quality Engieer with a Production Engineering & Management background. Though I have had around 12 years of experience swinging between the medical device and car assembly industry, I am currently chasing a change in my career throught this course of Data Analytics in ATU. My long term goal is to move into Artificial Intelligence. 
If you want to know more about me, please add me on LinkedIn: [Filipe Carvalho](https://www.linkedin.com/in/filipe-carvalho-8146232a/)      

## References:      

<a id="1">[1]</a> About readmes (no date) GitHub Docs. Available at: https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes (Accessed: 29 April 2024).   

<a id="2">[2]</a> Basic writing and formatting syntax (no date) GitHub Docs. Available at: https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax (Accessed: 29 April 2024).       

<a id="3">[3]</a> Horst, et al. (2022) "Palmer Archipelago Penguins Data in the palmerpenguins R Package - An Alternative to Anderson's Irises", The R Journal. Available at: https://journal.r-project.org/articles/RJ-2022-020        

<a id="4">[4]</a> Gorman, et al. (2014) Ecological Sexual Dimorphism and Environmental Variability within a Community of Antarctic Penguins (Genus Pygoscelis). PLOS ONE 9(3): e90081. https://doi.org/10.1371/journal.pone.0090081

<a id="5">[A]</a> Palmer Penguins (2021) UCI Machine Learning Repository. Available at: https://archive.ics.uci.edu/dataset/690/palmer+penguins-3

<a id="6">[6]</a> Google Maps (2024) Palmer Station, Antarctica, Type of Map: Terrain, Scale: 500km. Available at: https://www.google.com/maps/place/Palmer+Station,+Antarctica/@-60.0342296,-67.7558616,3.36z/data=!4m6!3m5!1s0xbc7f6b08d86317c9:0xe343fed7cb6c11e3!8m2!3d-64.7744286!4d-64.053186!16s%2Fg%2F11l2p50kmk?entry=ttu. 

<a id="7">[7]</a> Shiva, A. (2016) Chinstrap penguin (Pygoscelis antarctica), Wikipedia. Available at: https://en.wikipedia.org/wiki/File:South_Shetland-2016-Deception_Island–Chinstrap_penguin_(Pygoscelis_antarctica)_04.jpg. 

<a id="8">[8]</a> Shiva, A. (2016) Gentoo penguin (Pygoscelis papua), Wikipedia. Available at: https://en.wikipedia.org/wiki/File:Brown_Bluff-2016-Tabarin_Peninsula–Gentoo_penguin_(Pygoscelis_papua)_03.jpg. 

<a id="9">[9]</a> Shiva, A. (2016) Adélie penguin (Pygoscelis adeliae), Wikipedia. Available at: https://en.wikipedia.org/wiki/File:Hope_Bay-2016-Trinity_Peninsula–Adélie_penguin_(Pygoscelis_adeliae)_04.jpg. 

<a id="10">[10]</a> Kakati, M. (2020) Know About The Palmer Penguins!, Tableau. Available at: https://public.tableau.com/views/PalmerPenguin_makeovermonday/Dashboard1?%3Aembed=y&%3AshowVizHome=n&%3Adisplay_count=y&%3Adisplay_static_image=y&%3AbootstrapWhenNotified=true&%3Alanguage=en&%3Amobile=true&%3AapiID=host0. 

<a id="11">[11]</a> Waskom, M. (2020) penguins.csv, GitHub. Available at: https://raw.githubusercontent.com/mwaskom/seaborn-data/master/penguins.csv

<a id="12">[12]</a> Waskom, M. (no date) Seaborn Data, GitHub. Available at: https://github.com/mwaskom/seaborn/blob/master/README.md (Accessed: 29 April 2024). 

<a id="13">[13]</a> McLoughlin, I. (2024) Principle of Data Analytics - Assessment, GitHub. Available at: https://ianmcloughlin.github.io/2324_principles_of_data_analytics/.

<a id="14">[14]</a> Horst, A. (no date) The Palmer Archipelago penguins. Available at: https://allisonhorst.github.io/palmerpenguins/reference/figures/lter_penguins.png (Accessed: 29 April 2024)

<a id="15">[15]</a> Pandas (2024) NVIDIA Data Science Glossary. Available at: https://www.nvidia.com/en-us/glossary/pandas-python/#:~:text=Benefits%20of%20Pandas&text=Easy%20handling%20of%20missing%20data,DataFrames%20and%20higher%2Ddimensional%20objects (Accessed: 29 April 2024). 

<a id="16">[16]</a> Parker, K. (2020) Data Analysis in python: Getting started with pandas, Medium. Available at: https://towardsdatascience.com/data-analysis-in-python-getting-started-with-pandas-8cbcc1500c83 

<a id="17">[17]</a> Hunter, J. (2007) "Matplotlib: A 2D Graphics Environment", Computing in Science & Engineering, vol. 9, no. 3, pp. 90-95. Available at: https://matplotlib.org/stable/users/explain/quick_start.html

<a id="18">[18]</a> Numpy quickstart# (2008-2022) NumPy quickstart - NumPy v1.26 Manual. Available at: https://numpy.org/doc/stable/user/quickstart.html (Accessed: 29 April 2024). 

<a id="19">[19]</a> Pierian Training (2023) Working with scipy stats norm: A guide, Pierian Training. Available at: https://pieriantraining.com/working-with-scipy-stats-norm-a-guide/#:~:text=In%20Python%2C%20we%20can%20use,scale%20is%20the%20standard%20deviation 

<a id="20">[20]</a> Abhi (2023) Exploring Seaborn: Part 1: Creating visualizations with scatter plots and line plots, Medium. Available at: https://codeabhi.medium.com/a-complete-guide-to-data-visualization-in-python-with-seaborn-part-11-58fefd99fed3#:~:text=To%20make%20a%20scatter%20plot,the%20plot%20will%20be%20blue

<a id="21">[21]</a> PANDAS.READ_CSV# (2024) pandas.read_csv - pandas 2.2.2 documentation. Available at: https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.read_csv.html (Accessed: 29 April 2024). 

<a id="22">[22]</a> Sullivan, J. (2018) Data cleaning with python and pandas: Detecting missing values, Medium. Available at: https://towardsdatascience.com/data-cleaning-with-python-and-pandas-detecting-missing-values-3e9c6ebcf78b (Accessed: 29 April 2024). 

<a id="23">[23]</a> Pandas.dataframe.sample# (2024) pandas.DataFrame.sample - pandas 2.2.2 documentation. Available at: https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.sample.html (Accessed: 29 April 2024). 

<a id="24">[24]</a> Bhandari, P. (2023) Population vs. sample: Definitions, Differences & Examples, Scribbr. Available at: https://www.scribbr.com/methodology/population-vs-sample/#:~:text=Why%20are%20samples%20used%20in,effective%2C%20convenient%2C%20and%20manageable.

<a id="25">[25]</a> Horvath, R. (2023) Using pandas and python to explore your dataset, Real Python. Available at: https://realpython.com/pandas-python-explore-dataset/

<a id="26">[26]</a> Kaliyadan F, Kulkarni V. (2019) Types of Variables, Descriptive Statistics, and Sample Size. Indian Dermatol Online J. Available at: https://doi.org/10.4103%2Fidoj.IDOJ_468_18 

<a id="27">[27]</a> Rana, A. (2023) Bar charts vs Histograms: A complete guide, Venngage. Available at: https://venngage.com/blog/bar-charts-vs-histograms/

<a id="28">[28]</a> Pandey, P. (2020) Five ways to use value_counts(), Kaggle. Available at: https://www.kaggle.com/code/parulpandey/five-ways-to-use-value-counts

<a id="29">[29]</a> Board Infinity (2023) Groupby python function & how to use it!, Board Infinity. Available at: https://www.boardinfinity.com/blog/groupby-python-function/#:~:text=groupby%20size()&text=It%20gives%20back%20a%20pandas,of%20the%20len()%20method 

<a id="30">[30]</a> Pandas.dataframe.reset_index# (no date) pandas.DataFrame.reset_index - pandas 2.2.2 documentation. Available at: https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.reset_index.html (Accessed: 30 April 2024). 

<a id="31">[31]</a> Inzaugarat, M.E. (2023) Reshaping Data with pandas, RPubs. Available at: https://rpubs.com/datttrian/reshaping-data-with-pandas (Accessed: 29 April 2024). 

<a id="32">[32]</a> Sekhar, R. (2021) Why pandas.dataframe.sum(axis=0) returns sum of values in each column where axis =0 represent rows?, Stack Overflow. Available at: https://stackoverflow.com/questions/61690632/why-pandas-dataframe-sumaxis-0-returns-sum-of-values-in-each-column-where-axis#:~:text=In%20pandas%2C%20axis%3D0%20represent,each%20columns%20and%20vice%2Dversa. (Accessed: 29 April 2024). 

<a id="33">[33]</a> Python:Pandas: Dataframe: .sort_values() (2023) Codecademy. Available at: https://www.codecademy.com/resources/docs/pandas/dataframe/sortvalues (Accessed: 29 April 2024). 

<a id="34">[34]</a> How to sort pandas DataFrame by one or multiple column (2023) Saturn Cloud Blog. Available at: https://saturncloud.io/blog/how-to-sort-pandas-dataframe-from-one-column/#:~:text=How%20to%20Sort%20Pandas%20DataFrame%20From%20One%20Column,of%20one%20or%20more%20columns. (Accessed: 29 April 2024). 

<a id="35">[35]</a> Shane (no date) Shane Lynn. Available at: https://www.shanelynn.ie/bar-plots-in-python-using-pandas-dataframes/ (Accessed: 29 April 2024).

<a id="36">[36]</a> GeeksforGeeks (2023) Adding value labels on a Matplotlib Bar Chart, GeeksforGeeks. Available at: https://www.geeksforgeeks.org/adding-value-labels-on-a-matplotlib-bar-chart/ (Accessed: 29 April 2024). 

<a id="37">[37]</a> How to calculate summary statistics# (2024) Pandas 2.2.2 documentation. Available at: https://pandas.pydata.org/docs/getting_started/intro_tutorials/06_calculate_statistics.html (Accessed: 29 April 2024). 

<a id="38">[38]</a> Simplilearn (2023) Exploring descriptive statistics: Everything you need to know!: Simplilearn, Simplilearn.com. Available at: https://www.simplilearn.com/what-is-descriptive-statistics-article

<a id="39">[39]</a> W3Schools (no date) Pandas dataframe describe() method. Available at: https://www.w3schools.com/python/pandas/ref_df_describe.asp#:~:text=The%20describe()%20method%20returns,The%20average%20(mean)%20value. (Accessed: 29 April 2024). 

<a id="40">[40]</a> Pannell, R. (2023) Histogram: A comprehensive guide, LeanScape. Available at: https://leanscape.io/histogram-a-comprehensive-guide/

<a id="41">[41]</a>  Nilimesh Halder, P. (2024) Exploring normal distribution: Statistical analysis and Data Interpretation, Medium. Available at: https://medium.com/@HalderNilimesh/exploring-normal-distribution-statistical-analysis-and-data-interpretation-c3bbd4be446d 

<a id="42">[42]</a> GeeksforGeeks (2023b) Pandas dataframe.dropna() method, GeeksforGeeks. Available at: https://www.geeksforgeeks.org/python-pandas-dataframe-dropna/ 

<a id="43">[43]</a> Numpy.histogram# (no date) numpy.histogram - NumPy v1.26 Manual. Available at: https://numpy.org/doc/stable/reference/generated/numpy.histogram.html (Accessed: 29 April 2024). 

<a id="44">[44]</a> Matplotlib.axis.xaxis.set_ticks_position# (no date) matplotlib.axis.XAxis.set_ticks_position - Matplotlib 3.8.4 documentation. Available at: https://matplotlib.org/stable/api/_as_gen/matplotlib.axis.XAxis.set_ticks_position.html (Accessed: 30 April 2024). 

<a id="45">[45]</a> (No date) Chatgpt. Available at: https://chat.openai.com/ (Accessed: 30 April 2024).

<a id="46">[46]</a> Normal fit from experimental data (2021) Stack Overflow. Available at: https://stackoverflow.com/questions/63556187/normal-fit-from-experimental-data

<a id="47">[47]</a> Safarli, J. (2024) Normal distribution with python, Medium. Available at: https://medium.com/@c_safarli/normal-distribution-with-python-ddbfd1d066ad

<a id="48">[48]</a> Renee, T. (2022) How to demarc the mean and median in a histplot in both python and R, Medium. Available at: https://medium.com/geekculture/how-to-demarc-the-mean-and-median-in-a-histplot-in-both-python-and-r-86a60c437e67 (Accessed: 30 April 2024). 

<a id="49">[49]</a> Legend guide# (no date) Legend guide - Matplotlib 3.8.4 documentation. Available at: https://matplotlib.org/stable/users/explain/axes/legend_guide.html (Accessed: 30 April 2024).

<a id="50">[50]</a> Chen, J. (2024) Normal distribution: What it is, uses, and Formula, Investopedia. Available at: https://www.investopedia.com/terms/n/normaldistribution.asp#:~:text=The%20Bottom%20Line-,Normal%20distribution%2C%20also%20known%20as%20the%20Gaussian%20distribution%2C%20is%20a,defined%20by%20the%20standard%20deviation. (Accessed: 30 April 2024). 

<a id="51">[51]</a> Correlation (2024) Wikipedia. Available at: https://en.wikipedia.org/wiki/Correlation

<a id="52">[52]</a> Chen, J. (no date) Line of best fit: Definition, how it works, and calculation, Investopedia. Available at: https://www.investopedia.com/terms/l/line-of-best-fit.asp#:~:text=A%20line%20of%20best%20fit,plot%20of%20different%20data%20points. (Accessed: 30 April 2024). 

<a id="53">[53]</a> Numpy.linspace# (no date) numpy.linspace - NumPy v1.26 Manual. Available at: https://numpy.org/doc/stable/reference/generated/numpy.linspace.html (Accessed: 30 April 2024). 

<a id="54">[54]</a> Seaborn.scatterplot# (no date) seaborn.scatterplot - seaborn 0.13.2 documentation. Available at: https://seaborn.pydata.org/generated/seaborn.scatterplot.html (Accessed: 30 April 2024). 

<a id="55">[55]</a> Bobbitt, Z. (2023) Seaborn: How to use Hue parameter in Pairplot, Statology. Available at: https://www.statology.org/seaborn-pairplot-hue/

<a id="56">[56]</a> Matplotlib.pyplot.plot# (no date) matplotlib.pyplot.plot - Matplotlib 3.8.4 documentation. Available at: https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.plot.html (Accessed: 30 April 2024). 

<a id="57">[57]</a> VanderPlas, J. (no date) Python Data Science Handbook, O’Reilly Online Learning. Available at: https://www.oreilly.com/library/view/python-data-science/9781491912126/ch04.html (Accessed: 30 April 2024). 

<a id="58">[58]</a> Matplotlib.axes.axes.set_xlabel# (no date) matplotlib.axes.Axes.set_xlabel - Matplotlib 3.8.4 documentation. Available at: https://matplotlib.org/stable/api/_as_gen/matplotlib.axes.Axes.set_xlabel.html (Accessed: 30 April 2024). 

<a id="59">[59]</a> Matplotlib.axes.axes.set_title# (no date) matplotlib.axes.Axes.set_title - Matplotlib 3.8.4 documentation. Available at: https://matplotlib.org/stable/api/_as_gen/matplotlib.axes.Axes.set_title.html (Accessed: 30 April 2024).

<a id="60">[60]</a> Matplotlib - axes limits (no date) Tutorialspoint. Available at: https://www.tutorialspoint.com/matplotlib/matplotlib_setting_limits.htm#:~:text=set_ylim()-,The%20ax.,a%20specific%20subplot%20or%20axis. (Accessed: 30 April 2024). 

<a id="61">[61]</a> Numpy.corrcoef# (no date) numpy.corrcoef - NumPy v1.26 Manual. Available at: https://numpy.org/doc/stable/reference/generated/numpy.corrcoef.html (Accessed: 30 April 2024). 

<a id="62">[62]</a> Frost, J. (2024) Interpreting correlation coefficients, Statistics By Jim. Available at: https://statisticsbyjim.com/basics/correlations/

<a id="63">[63]</a> Baruah, I.D. (2023) Dimensionality reduction techniques - PCA, LCA and SVD, Medium. Available at: https://medium.com/nerd-for-tech/dimensionality-reduction-techniques-pca-lca-and-svd-f2a56b097f7c

<a id="64">[64]</a> Sinha, A. (2023) Uncovering hidden patterns: Advanced clustering and segmentation methods in Data Science, Express Computer. Available at: https://www.expresscomputer.in/big-data-analytics/uncovering-hidden-patterns-advanced-clustering-and-segmentation-methods-in-data-science-wissen-tech/103821/#:~:text=Clustering%20Accelerates%20Hidden%20Pattern%20Matching&text=Using%20sophisticated%20algorithms%20and%20techniques,data%20insights%20of%20the%20same.

<a id="65">[65]</a>  Ray, S. (2024) 7 regression techniques you should know!, Analytics Vidhya. Available at: https://www.analyticsvidhya.com/blog/2015/08/comprehensive-guide-regression/