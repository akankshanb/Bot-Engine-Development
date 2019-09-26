# CSC510-22

## Problem Description
Plotting graphs from all sorts of data is a necessitty among people with or without some sort of programming background. They first need to know what kind of data they have and the type of graph that can be generated from it. This in itself is a challenging task as not all types of graphs can be generated from any dataset. Then comes the part of which library in what language to use for plotting the said data into graphs. A plethora of options are available to choose from and can overwhelm the user. There is a need for a quick solution to map any dataset into a graph for people with little to no knowledge on plotting graphs. Also, plotting graphs for data visualization is a frequent task for data engineers and machine learning enthusiasts. Even the data engineers get confused which plot to use and how to plot their data.

## BOT Description
This Library bot makes it easy for the users to choose the kind of plot and makes their work easy by also providing details of how to plot their data. Data visualization by plotting graphs is most common task for Data engineers, Machine learning enthusiasts and commonly preferred way to see the statistics of any study. One of the widely used library in Python for plotting graphs is **matplotlib**. matplotlib is a plotting library used in python programming language and it can be used in python scripts, shell, web application servers and other graphical user interface toolkits. There are many kinds of plots available in this library, but user might not be aware of which kind of plot to use for his data. So for the users working with Python, this bot will suggest the library to use for  plotting and also help users choose the right kind of plot based on the type of data user wants to visualize. Also, this bot will provide him with sample code for the kind of plot user wants to use and also lets him try out the code and see the way plot look like by providing some sample data.  
* This is a chatbot interface that will help the user to get the right graph for their data.
* This bot will not only provide with correct function but also its usage by providing a sample source code.
* The user can also test the correctness of the plot by visualizing their data input on the plot generated by the bot.
* The types of plots the bot can plot are:
   * Line graph
   * Histogram
   * Scatterplot
   * Piechart
   * Box-plot
   * 3D plot
Tagline: **Plotbot**

## Use cases
This is an example use case:
```
Use Case1: Give the user the right plot name with code snippet.
1 Preconditions
   User must have mattermost account.
2 Main Flow
   //User will request meeting and provide list of attendees [S1]. Bot will provide  possible meeting times and user confirms [S2]. Bot creates meeting and posts link [S3].
3 Subflows
  //[S1] User provides /meeting command with @username,@username list.
  //[S2] Bot will return list of meeting times. User will confirm time.
  //[S3] Bot will create meeting and post link to google calendar event.
4 Alternative Flows
  //[E1] No team members are available.
```
```
Use Case2: Plot the graph for the user with their sample data.
1 Preconditions
   User must have mattermost account.
   User must give the data in the format required by the bot.
2 Main Flow
   //User will request meeting and provide list of attendees [S1]. Bot will provide  possible meeting times and user confirms [S2]. Bot creates meeting and posts link [S3].
3 Subflows
  //[S1] User provides /meeting command with @username,@username list.
  //[S2] Bot will return list of meeting times. User will confirm time.
  //[S3] Bot will create meeting and post link to google calendar event.
4 Alternative Flows
  //[E1] No team members are available.
```
```
Use Case3: Provide admin with the ability to configure new plots into the server database.
1 Preconditions
  The admin must have a mattermost account.
  The admin must have permissions to configure the bot.
2 Main Flow
   //User will request meeting and provide list of attendees [S1]. Bot will provide  possible meeting times and user confirms [S2]. Bot creates meeting and posts link [S3].
3 Subflows
  //[S1] User provides /meeting command with @username,@username list.
  //[S2] Bot will return list of meeting times. User will confirm time.
  //[S3] Bot will create meeting and post link to google calendar event.
4 Alternative Flows
  //[E1] No team members are available.
```
