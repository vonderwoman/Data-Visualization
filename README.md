# Data-Visualization
A Deep Dive into Matplotlib and Seaborn
 
# Introduction to Data Visualization  

Data representation refers to the form in which you can store, process, and transmit data. Representations can narrate a story and convey fundamental discoveries to your audience. Without appropriately modeling your information to use it to make meaningful findings, its value is reduced. Creating representations helps us achieve a more precise, more concise, and more direct perspective of information, making it easier for anyone to understand the data. Information isn't equivalent to data. Representations are a useful apparatus to derive insights from the data. Thus, representations transform data into useful information. 

 **Advantages of Visualizing data** 

-Complex data can be easily understood. 

 -A simple visual representation of outliers, target audiences, and futures markets can be created 

-Storytelling can be done using dashboards and animations.  

 -Data can be explored through interactive visualizations. 

**All you need to know about plots**

  1)Comparison plots 

    -Line chart 
    -Bar chart 
    -Radar chart 
   2)Relation plots 

     -scatter 

     -Bubble 

     -Corregram 

     -heatmap 
    3)Composition plots 

     -donut/pie chart 

     -Stacked bar 

     -Stacked area chart 

    4)Venn diagram 

    5)Distribution plots 

     -Histogram 

     -Density line chart 

     -Boxplot 

     -Violin 

    6)Geoplots 

     -Dot map 

     -cheropleth map 

     -Connection map 

      

    **What makes a good Visualization?** 

    -Most importantly,your visualization should be self explanotry and Visualying appealing 

    -Your visualization should tell a story and should be designed for your audience. 

# Visualizing Stock Trends by Using a Line Plot 

###Scenario of the project###

You are interested in investing in stocks. You downloaded the stock prices for the "big five": Amazon, Google, Apple, Facebook, and Microsoft. You want to visualize the closing prices in dollars to identify trends.  

###Objective###

-To create a line plot to showcase stock trends 

-Using Labels,title and legend to make the visualization self-explanatory and complete 

 

We are presented with 5 dataset from Google,Facebook,Apple,Amazon and Microsoft. We will use pandas to read the datasets (GOOGL_data.csv, FB_data.csv, AAPL_data.csv, AMZN_data.csv, and MSFT_data.csv) located in the Datasets folder. The read_csv() function reads a .csv file into a DataFrame. 

Using Matplotlib to create a line chart visualizing the closing prices for the past 5 years (whole data sequence) for all five companies. Add labels, titles, and a legend to make the visualization self-explanatory. Use plt.grid() to add a grid to your plot. If necessary, adjust the ticks in order to make them readable. 

# Movie Comparison using Bar Plots 

In this project,we will be using the Bar plots to compare the five movies with scores from Rotten Tomatoes. 

##Associated  Tasks##

Use Matplotlib to create a visually appealing bar plot comparing the two scores for all five movies. 

Use the movie titles as labels for the x-axis. Use percentages at intervals of 20 for the y-axis and minor ticks at intervals of 5. Add a legend and a suitable title to the plot.  

Use functions that are required to explicitly specify the axes.

