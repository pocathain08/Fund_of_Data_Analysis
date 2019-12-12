# Fund_of_Data_Analysis
Repository for the FDA Assignment
This assessment concerns the well-known tips dataset. It will be described and analised using the Python packages seaborn and jupyter.

The ultimate goal of my analysis of this Dataset is to attempt to discover what combination of variables will yeild the largest tip, or to determine which variable has the greatest influence on tips. 

The majority of my commentry on my findings will be in the ipynb file, as it will refer and relate to the plot above it. 

Through my research, I will reference in a mark-down cell the sources I used to help me code my data. Obviously, I will be heavily reliant an what I learned in the lectures provided. In the end, I will add a lessons identified/learned that would assist me in any future coding of this nature. 

#Description
The first part of my repository will use descriptive statistics and plots to describe the tips dataset. 
I started this by sreating a repository and cloning using the cmd interface. After this, I downloaded the tips dataframe as a CVS file to the project folder. I also imported all the libraries that I felt I would need. I then looked at at the data shape and info and checked for missing elements of the df using df.info. I changed the col names to one capitalised word. This is to make it look a little better but also to make the Col easier to call for later analysis. 

I then looked at a A scatter plot matrix of the data, this is a collection of variables where each of the variables will be plotted against each other 
(Ref: https://subscription.packtpub.com/book/big_data_and_business_intelligence/9781784390150/4/ch04lvl1sec37/a-scatter-plot-matrix).
I also called a plot of the data, showing Bill, Party and Tip.

As outlined, one of the key relationships that I was curious about we what factor most influenced the amount of the tip. From the Scatter matrix, it would seem that males (in red dots) tended to be slight outliers. The majority of the dots were concentrated away from the origin were red, representing males, but with a few green dots also.
Looking at the Party/Bill and Party/tips, both plots look very similar, which suggests that there is a correlation between party size and tips. But equally, the Bill/Bill and Tips/Tips histograms also look similar. 


Regression: 
To the above jupyter notebook add a section that discusses and analyses whether there is a relationship between the total bill and tip amount.
Ref: https://github.com/ianmcloughlin/jupyter-teaching-notebooks/blob/master/simple-linear-regression.ipynb
 
 https://stackoverflow.com/questions/12182063/how-to-calculate-the-regularization-parameter-in-linear-regression


Analyse: 
Again using the same notebook, analyse the relationship between the variables within the dataset. You are free to interpret this as you wish — for example, you may analyse all pairs of variables, or select a subset and analyse those. This part is worth 40%.

Lessons identified/learned.
stackoverflow is an excellent resource, but it is important to ask the correct question.
A clear plan at the start of the assignemnt is important and give the assignemnt focus. This was very much influenced by the breakdown of the question. 
It is very easy to go down rabbit holes with the coding aspect. 
