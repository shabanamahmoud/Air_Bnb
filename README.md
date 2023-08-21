# Air_Bnb

### The provided code performs various data analysis tasks on the Airbnb dataset for Amsterdam. Here is a summary of the code's functionality:

1. Data Import and Inspection:

   - The necessary libraries are imported.
   - The dataset is read from the "listings.csv" file into a DataFrame.
   - Basic information about the DataFrame, such as column names and data types, is displayed.

2. Data Cleaning and Preparation:

    - The "neighbourhood_group" and "id" columns, which are not required for analysis, are dropped.
    - Duplicate IDs are checked and removed if found.
    - The distribution of listings by host names is analyzed.
3. Data Visualization:

    - Histograms are plotted to visualize the distribution of numeric columns.
    - A heatmap is created to show the correlation between numeric columns.
    - The geographic distribution of rentals in Amsterdam is visualized using scatter plots.
    - Bar plots are generated to display the number of listings in each neighborhood, room type, and for specific hosts.
4. Neighborhood Analysis:

    - The distribution of rentals in each neighborhood is explored and visualized.
    - The neighborhoods where a specific host (e.g., "Martijn") owns properties are analyzed and compared to the overall distribution of neighborhoods.
    
The code demonstrates how to load and clean the dataset, visualize data using histograms, heatmaps, and scatter plots, and perform analysis on specific columns such as neighborhoods, room types, and host properties. It provides insights into the distribution of Airbnb listings in Amsterdam and allows for comparisons between different neighborhoods and hosts.

The code and its outputs can be used as a starting point for further analysis or as a reference for understanding the dataset. 
