<h1 align="center"> Baby names </h1>  

### Group J :  

Olaya Hanid   
Mohammed Amine Laouaouda   
Asmae Mejait    
Andres Soto  


In this mini-project, we will be working with a data set of baby names in France. It contains the list of all baby names registered in France, year by year, from 1900 through 2019. There are two data sets: one aggregated to the national level, and another with data by department. 
Our goal is to create 3 different visualizations around these data, each focussed on answering different kinds of questions about the data:

## Visualization 1: 

1. How do baby names evolve over time? 
2. Are there names that have consistently remained popular or unpopular? 
3. Are there some that have were suddenly or briefly popular or unpopular? 
4. Are there trends in time?
<picture>
  <img src="https://github.com/IGR204/Baby_names/blob/main/dash1-1.jpeg">
</picture>

<picture>
  <img src="https://github.com/IGR204/Baby_names/blob/main/dash1-2.jpeg">
</picture>

This first visualisation is a dashboard made using the Tableau tool. In this dashboard, we have a first graph corresponding to the evolution of the number of births by sex over the period 1900-2020. This first graph, which is intended for demographic purposes, gives an overview of the evolution of births over the last century, showing in particular periods of strong growth in births (the post-war periods) as well as periods of strong decline (war periods). Here, this first graph gives an initial overview of the context in which we find ourselves, namely the names of babies in France since 1900.

The second graph on the dashboard shows the evolution of baby names over time. This graph allows us to plot for each selected name the evolution curve of its total number per year over time, so that we can compare the evolution curves of each name and see the different trends over time, i.e. the periods of strong use of these names and the periods of decline. One of the advantages of this visualisation is that it allows you to compare the evolution of each chosen name by plotting their evolution curves on the same graph. Thus, this graph makes it possible to answer the first question, which is to know the evolution of the first names over time. 

The third graph on this dashboard shows the popularity of names. It is composed of a first inverted histogram showing the most used names in descending order over the entire period, with a colour code that shows the different proportions of use of each of these names according to gender.  The second component of this graph is a scatter plot showing for each name its average number of uses per year for each of the two sexes (if this is the case) over the whole period. This visualisation is very interesting as it gives an overview of the most popular first names over the whole selected period. It allows to know for different time intervals and periods the most used first names, and thanks to the averages we can see if these first names have remained popular or not over these periods. Moreover, thanks to the colour code, we can see that 4 of the 5 most used names over the period correspond to predominantly male names, and we find the same tendency in the rest of the ranking, which could suggest that there is a greater diversity of names among men than among women. However, one of the disadvantages is that we don't have a visual on the popularity of first names by gender, because here we are ranking the first names of all genders together and although we have this colour code, it doesn't allow us to have the same number of male and female first names in the ranking. It would therefore have been more appropriate to classify them by sex in order to know which names are the most popular for boys and girls.

The fourth graph of the dashboard concerns the evolution of the 5 most popular names and the 5 least popular names. This graph plots the evolution of these names over the entire selected period. Thus, it makes it possible to know whether these names have always been popular/unpopular or not. The disadvantage here is that these evolution curves are plotted horizontally and therefore on small areas which do not allow for a good visualization of all the trends over the period, an improvement would be to plot the evolution curves of these first names on the same graph, and therefore to have 2 horizontal graphs for each of the 2 groups. This would allow a better visualisation of these trends. 


## Visualization 2: 

1. Is there a regional effect in the data? 
2. Are some names more popular in some regions? 
3. Are popular names generally popular across the whole country?
<picture>
  <img src="https://github.com/IGR204/Baby_names/blob/main/dash2-1.jpeg">
</picture>

<picture>
  <img src="https://github.com/IGR204/Baby_names/blob/main/dash2-2.jpeg">
</picture>

In the first graph, we can see that the number of names varies by department. Indeed, the southern and central departments are characterised by a low frequency of names, while those in the far north are characterised by a higher number of names.

In the second graph, we take the example of the department of Paris, and we notice a peak in popularity for the first name "Jean" which occurs more than 140k times. Moreover, only 2 female names exist in the top 10 most popular names in Paris.


## Visualization 3 (bonus):

1. Are there gender effects in the data? 
2. Does popularity of names given to both sexes evolve consistently? 
(Note: this data set treats sex as binary; this is a simplification that carries into this assignment but does not generally hold.)
