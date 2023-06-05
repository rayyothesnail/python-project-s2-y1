# python-project-s2-y1
Introduction:  
The code is a Python script that performs data processing, analysis, and visualization on NBA player statistics data. It uses various libraries such as numpy, pandas, seaborn, and matplotlib to load, clean, analyze, and visualize the data. The script defines three classes: DataProcessor, DataAnalyzer, and DataVisualizer, each with specific methods to perform different tasks.  
  
Data Processing:   
The DataProcessor class has two methods: load_data() and clean_data(). The load_data() method reads the NBA player statistics data from a CSV file, and the clean_data() method removes any rows with missing values. The cleaned data is stored in a variable called CleanedDataFrame.  
  
Data Analysis:   
The DataAnalyzer class takes the cleaned data as input and has four methods: get_average_of_column(), get_distribution_of_column(), get_median_of_column(), and get_mode_of_column(). These methods calculate and return the average, standard deviation, median, and mode of a specified column in the cleaned data, respectively. Each of these methods takes a column name as input and returns a statistical measure of that column if it is numeric. If the column is not numeric, the method prints an error message. 
  
Data Visualization:  
The DataVisualizer class takes the cleaned data as input and has four methods: plot_line_chart(), plot_distribution(), plot_pie(), and plot_scatter(). These methods create line charts, bar charts, pie charts, and scatter plots, respectively, to visualize the data. The user is prompted to save each figure or not. Each of these methods takes one or more column names as input and creates a visualization of the data using seaborn and matplotlib.pyplot libraries. The user is prompted to save the figure or not. 
  
Conclusion:   
Overall, the code is a useful tool for analyzing and visualizing NBA player statistics data. It allows users to easily load, clean, analyze, and visualize the data using Python.  
