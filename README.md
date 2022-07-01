<h1 align="center"> Baby names </h1>  

### Group J :  

Olaya Hanid   
Mohammed Amine Laouaouda   
Asmae Mejait    
Andres Soto  


In this mini-project, we will be working with a data set of baby names in France. It contains the list of all baby names registered in France, year by year, from 1900 through 2019. There are two data sets: one aggregated to the national level, and another with data by department. 
Our goal is to create 3 different visualizations around these data, each focused on answering different kinds of questions about the data:

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

For this part, we chose : 
- a choropleth map showing the distibution of names per department 
- a bar chart ordering the most frequent names for each department
<picture>
  <img src="https://github.com/IGR204/Baby_names/blob/main/dash2-1.jpeg">
</picture>

<picture>
  <img src="https://github.com/IGR204/Baby_names/blob/main/dash2-2.jpeg">
</picture>

In the first graph, we can see that the number of names varies by department. Indeed, the southern and central departments are characterised by a low frequency of names, while those in the far north are characterised by a higher number of names.

In the second graph, we take the example of the department of Paris, and we notice a peak in popularity for the first name "Jean" which occurs more than 140k times. Moreover, only 2 female names exist in the top 10 most popular names in Paris.


## Visualization 3 (Altair):

1. Are there gender effects in the data? 
2. Does popularity of names given to both sexes evolve consistently? 
(Note: this data set treats sex as binary; this is a simplification that carries into this assignment but does not generally hold.)

<picture>
  <img src="https://github.com/IGR204/Baby_names/blob/main/visualization3.png">
</picture>

To answer this question, we decided to plot the logarithmic ratio of the use of first names by girls and boys over the years on a graph. This approach allows us to better visualise the proportions of use of these first names by both sexes, since the proximity of a curve to the 0 axis indicates the degree of use of a first name, so the closer this curve is to 0, the more the first name is used by both sexes. Now, when we analyse this graph and the various curves, we can see that there are gender effects in certain specific periods, in particular the period 1930-1960, which marked a period of high use of popular mixed first names, and the post-1960 period, which marked the beginning of a decline in the use of these mixed first names. The curve for the name Dominique stands out from the others because, although it is predominantly male, it increased sharply among girls between the 1920s and 1950s, even becoming a predominantly female name in the early 1950s. Similarly, but to a lesser extent, the name Nathalie, which is exclusively feminine nowadays, experienced a strong progression among men between the 1900s and 1940s, to the point of becoming very popular among the latter, before experiencing a rapid decline among men after the 1940s. The name Claude is one of the most popular known mixed names, and if we look at its curve we can see that it remained very popular from the 1900s to the 2000s, keeping a certain constancy over time, which distinguishes it particularly from the others. Overall, mixed names reached a peak in the 1950s before slowly decreasing, however, some popular names such as Dominique or Claude have maintained their popularity throughout the twentieth century and even up to the present day as they are still as popular. 
