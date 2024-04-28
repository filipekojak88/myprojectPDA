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
The penguin csv file used for this analysis was from the [Seaborn](https://github.com/mwaskom/seaborn/blob/master/README.md)'s repository as recommended on the Assessment Instructions for the module of Principles of Data Analytics [[11]](#11).     

## Use of this project

This project is useful for other users as a source of examples of data analysis that can be completed using Python, and direct them on some conclusions that you can draw from the data.
Perhaps, the perspective adopted in this project can be also adapted by other students to investigate different datasets.
Nonetheless, this project reflects the author's understanding and knowledge from the Python programming skills learned so far in this course. Therefore, any contribution or ideas to improve this project will be always welcomed.     

## Get Started 

To get started with this project click on this link '[penguins.ipynb](penguins.ipynb)' and navigate through the different sections of this Jupyter from the beginning to the end. But you if you prefer to go to a specific section, then here you can get a quick overview of what is covered:     
- Loading the Database: This section displays the different imported Python modules used in the analysis of the penguins dataset and the script used to load the data set from the Seaborn repository in GitHub.        
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

I am current a Quality Engieer with a Production Engineering & Management background. Though I have had around 12 years of experience swinging between the medical device and car assembly industry, I am currently chasing a change in my career throught this course of Data Analytics in ATU. My long term goal is to move into Artificial Intelligence. 
If you want to know more about me, please add me on LinkedIn: [Filipe Carvalho](https://www.linkedin.com/in/filipe-carvalho-8146232a/)      

## References:      

<a id="1">[1]</a> https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes     

<a id="2">[2]</a> https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax        

<a id="3">[3]</a> Horst, et al. (2022) "Palmer Archipelago Penguins Data in the palmerpenguins R Package - An Alternative to Anderson's Irises", The R Journal. Available at: https://journal.r-project.org/articles/RJ-2022-020        

<a id="4">[4]</a> Gorman, et al. (2014) Ecological Sexual Dimorphism and Environmental Variability within a Community of Antarctic Penguins (Genus Pygoscelis). PLOS ONE 9(3): e90081. https://doi.org/10.1371/journal.pone.0090081

<a id="5">[5]</a> Palmer Penguins (2021) UCI Machine Learning Repository. Available at: https://archive.ics.uci.edu/dataset/690/palmer+penguins-3 (Accessed: 26 April 2024). 

<a id="6">[6]</a> Google Maps (2024) Palmer Station, Antarctica, Type of Map: Terrain, Scale: 500km. Available at: https://www.google.com/maps/place/Palmer+Station,+Antarctica/@-60.0342296,-67.7558616,3.36z/data=!4m6!3m5!1s0xbc7f6b08d86317c9:0xe343fed7cb6c11e3!8m2!3d-64.7744286!4d-64.053186!16s%2Fg%2F11l2p50kmk?entry=ttu. 

<a id="7">[7]</a> Shiva, A. (2016) Chinstrap penguin (Pygoscelis antarctica), Wikipedia. Available at: https://en.wikipedia.org/wiki/File:South_Shetland-2016-Deception_Island–Chinstrap_penguin_(Pygoscelis_antarctica)_04.jpg. 

<a id="8">[8]</a> Shiva, A. (2016) Gentoo penguin (Pygoscelis papua), Wikipedia. Available at: https://en.wikipedia.org/wiki/File:Brown_Bluff-2016-Tabarin_Peninsula–Gentoo_penguin_(Pygoscelis_papua)_03.jpg. 

<a id="9">[9]</a> Shiva, A. (2016) Adélie penguin (Pygoscelis adeliae), Wikipedia. Available at: https://en.wikipedia.org/wiki/File:Hope_Bay-2016-Trinity_Peninsula–Adélie_penguin_(Pygoscelis_adeliae)_04.jpg. 

<a id="10">[10]</a> Kakati, M. (2020) Know About The Palmer Penguins!, Tableau. Available at: https://public.tableau.com/views/PalmerPenguin_makeovermonday/Dashboard1?%3Aembed=y&%3AshowVizHome=n&%3Adisplay_count=y&%3Adisplay_static_image=y&%3AbootstrapWhenNotified=true&%3Alanguage=en&%3Amobile=true&%3AapiID=host0. 

<a id="11">[11]</a> McLoughlin, I. (2024) Principle of Data Analytics - Assessment, GitHub. Available at: https://ianmcloughlin.github.io/2324_principles_of_data_analytics/ (Accessed: 28 April 2024). 