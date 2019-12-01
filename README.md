Jacob Boeckenstedt

Edgar Mendoza

Lanea Blackburn

Priya Panati


## How to run the project:

To run this project you will want to download the zip file to your local machine. Once this is done, you will need to unzip the file, then open a terminal on your device. Then you will need to place the path to the file onto the terminal (on some machines you can also use cd then drag and drop the file onto your terminal). Once this is done, open up a local server to run the documents on, with many machines you will use the command ‘python -m http.server’, once the server is up and running you will go to a browser and type in ‘localhost:8000’ this will open your personal server and from there you will be able to view all of the visualizations and their associated programs.

## Visualization 1: 
For the first visualization we were working to start to develop a visualization that could be a representation of categorical analysis to look into how art has changed over time and how the popularity of certain art has changed. To start the process of our visualization we looked to see how we could best graph the dataset that contained many pieces of unclean data. This was at first a bit of a barrier to overcome as we had to be specific when looking at what data was important to our overall analysis but once we were able to figure out how the data flowed together this process became much easier. 
In the final version of our first visualization we used the python library plotly that can visualize interactive data. By allowing our visualization to be interactive it allows us to gain much more insight into how the data interacts with one another and how to pieces of the data start to build the story. With this first categorical visualization we were able to see more insight to how the styles have evolved over the years and then start to see the perceptual image grow with how art has continued to change. By having the different colors it allows the user to start to gain a gist of the data collected and they can start to choose how they want to look into the data. 

## Visualization 2: 
For the second visualization, we created a scatter plot to determine the correlation between the mean and happiness ratings of paintings before 1500(quantitative). The paintings were all made with the Renaissance style and had three different categories: early renaissance, high renaissance, and northern renaissance. These are all distinguishable in our visualization with different colors. The x-axis is the mean rating and y-axis is the happiness rating. In addition, the size of the data point is determined by love rating. Overall, we can see that there is a positive correlation with happiness and mean ratings. Also, the love rating tends to be higher as happiness and mean increases as well.
Because you can’t really tell that each data point is a painting, we also added in a tooltip feature that allows the user to see each of the data points’ attributes. If you go over a data point, you will see its mean rating, happiness rating, love rating, and category.
We used R to make these visualizations. We chose happiness, love, and mean because these are all positive attributes to any painting. A scatterplot was also chosen because it’s the best way to represent correlation.

## Team Roles: 
Priya created the first visualization outlining the different ways that art has changed overtime. She used plotly to finish the interactive visualization then exported it to an HTML.

Lanea worked to finish part of the write up looking at different ways that we can improve the visualization to best represent the data.

Jacob created the quantitative visualization using R’s ggplot. He then was able to export that file into HTML to be able to see the visualization.

Edgar reviewed both the visualizations to make them as clear as possible. In addition, he wrote part of the read me.
