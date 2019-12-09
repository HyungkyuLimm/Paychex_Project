# Paychex Practicum Project

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>
Create a recommendation engine capable of making most relevant item recommendations to clients.

Goal 1. Conduct exploratory analysis to uncover hidden patterns in the data.
 - Get data distribution based on Representative Level, Size, and Industry features 
 - Get the frequencies of each product individually and by high-level categories 

Goal 2. Improving the K-modes clustering model
Decided on the best clustering number of 6 by iteration when getting the highest general accuracy and minimum cost. 
 
Goal 3. Developing the evaluation metrics based on general accuracy 
 - Created the test dataset by masking random selected purchased products in each transaction. 
 - Checked whether the products recommended are the user actually ended up purchasing in the end. 
 - Marked the prediction right when the recommended products cover any masking products. The general accuracy is around 60%.


## File Descriptions <a name="files"></a>

The notebooks is exploratory in searching through the data pertaining to the questions showcased by the notebook title.  Markdown cells were used to assist in walking through the thought process for individual steps.  

If you **cannot see** .ipynb file, copy the url of .ipynb file and please go to http://nbviewer.jupyter.org. Thank you :) 
