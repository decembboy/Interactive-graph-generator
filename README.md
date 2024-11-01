# Dynamic Data Plotting with Pandas, Matplotlib, and Ipywidgets

This project provides an interactive data visualization tool for exploring CSV datasets using Python's pandas, matplotlib, and ipywidgets. The primary goal is to allow users to create dynamic plots from a dataset with minimal code input. Users can select various data fields and plot types directly from dropdown menus, making the data exploration and plotting experience streamlined and intuitive.
Key Features
•	Dynamic Plotting: Use a combination of dropdown widgets to choose columns and plot types (e.g., bar, scatter, line, etc.) without writing new code each time.
•	Automated Data Extraction: Custom functions auto-generate code to extract and map fields within the CSV dataset, allowing for quick selection of data columns.
•	Flexible Code Execution: With exec() functions, selected data and plot configurations are processed to execute plotting code dynamically based on user input.
•	Data Mapping for Visualization: Generates dictionaries for rapid access to column names and their values for plotting.
•	User-friendly Interface: Combines ipywidgets dropdown menus for selecting columns and plot types to simplify visualization.
Setup and Usage
1.	Data Loading: Load any CSV file to start exploring and visualizing data.
2.	Widget Interaction: Choose columns from bar_1 and bar_2 dropdowns and select the desired plot type from the option dropdown.
3.	Generate Plots: Click to plot the selected data, with options for bar charts, scatter plots, and more.

