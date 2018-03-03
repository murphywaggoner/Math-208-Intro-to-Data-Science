The idea behind a Case Study Assignment is to have all students in the class read/view the
case study, but one group of students would present on the case study.

- What is the question to be answered?

- What is the dataset?

- Describe in detail a specific method used.

- Does the case study use the tidyverse?

    - If not, could you understand the code?  Could you rewrite the code to use the tidyverse?
    
    - If so, did the case study use the tidyverse in the way we would?

- Describe something you learned that was new.

- What is one piece of advice/whatever that you learned that you think is most important?

## International Adoptions

This case study uses a dataset from the May 1993 *Ours Magazine* published by [Adoptive Parents](https://www.adoptivefamilies.com/)
to investigate changes in the
number of visas issued to prospective parents from the U.s. who are adopting from other countries.  The data has a long right 
tail and so a transformation of the data is needed to understand it.  The original case study comes from 
*A Casebook for a First Course in Statistics and Data Analysis* by Chatterjee, Handcock, and Simonoff.  A version of it with
R code is in your course Scholar site along with the data set.  It might be possible to do a more contemporary study or long-term
study using data from the [U.S. government travel site](https://travel.state.gov/content/travel/en/Intercountry-Adoption/adopt_ref/adoption-statistics.html.).

## La Quinta

[A well-developed case study](https://www.rstudio.com/resources/webinars/data-science-case-study/)
on scraping the web for data for La Quinta Hotels 
and Denny's Restaurants to see the geographical relationship between these companies. 
Includes a video and other materials.


## Irises

The iris dataset  has been analyzed by many people, but 
[this case study](https://github.com/rhiever/Data-Analysis-and-Machine-Learning-Projects/blob/master/example-data-science-notebook/Example%20Machine%20Learning%20Notebook.ipynb) lays out
the analysis beginning with a good look at the data.


## Flights

[This case study](https://www.r-bloggers.com/a-data-science-case-study-in-r/) attempts to answer questions about flight data similar to what we have used in class.

## Old Faithful

The data on eruption time and intervals between eruptions has been analyzed in many ways.  [Mike Anderson's analysis](http://faculty.business.utsa.edu/manderso/R-examples/Geyser/Geyser.html) focuses on models of the data on Old Faithful found in the **geyser** dataset on R.  Flip through all the tabs in this analysis to see all the models.  The **geyser** dataset is taken from Azzalini and Bowman, “A look at some data on the Old Faithful Geyser”, JRSS-C (Applied Statistics), 39(3), pp357-365 (1990).  For this case study, you are asked to go beyond just what is in Anderson's website, which analyzes data from the 1980s.  At [The Geyser Study and Observation Association](http://www.geyserstudy.org/geyser.aspx?pGeyserNo=OLDFAITHFUL)  you'll find Old Faithful data for 2000 to 2011.  However, the data is in a different format than the **geyser** data.  Use R to read the data there, create a tibble with the same variables as **geyser** and rerun Anderson's analysis.  Are the results the same?


## Internal Positioning System

Chapter 1 from **Data Science in R: A Case Studies Approach
to Computational Reasoning and Problems Solving** by Deborah Nolan and Duncan Temple Lang is a more sophistocated case study on using an indoor position system to predict locations.  The case study changes the shape of the data and uses a *k*-nearest neighbors model to make predictions on locations of transmitters.  The [R code](http://rdatasciencecases.org/GeoLoc/code.R) and the [first 32 pages of the case study](https://books.google.com/books?id=A5O9BwAAQBAJ&printsec=frontcover&source=gbs_ge_summary_r&cad=0#v=onepage&q&f=false) are available online. 

## Beer Ratings

This open-ended case study asks you to look at data about beer and customer ratings.  Dr. James D. Wilson of University
of San Francisco wrote the [questions](https://github.com/murphywaggoner/Intro-Data-Science/blob/master/Code_Demonstrations/Case%20Study%201/Beer_Analysis.pdf) and gathered the [data](https://github.com/murphywaggoner/Intro-Data-Science/blob/master/Code_Demonstrations/Case%20Study%201/beer.data.RData).

## Text Analysis

This open-ended case study asks you to use text manipulation and regular expressions to gather information from a set of 
tweets and the State of the Union speeches from 1790 to 2012.  Dr. James D. Wilson of University
of San Francisco wrote the [questions](https://github.com/murphywaggoner/Intro-Data-Science/blob/master/Code_Demonstrations/Case%20Study%202/CaseStudy2.pdf) and gathered the [data](https://github.com/murphywaggoner/Intro-Data-Science/tree/master/Data).

