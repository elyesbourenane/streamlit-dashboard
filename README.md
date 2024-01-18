# Dashboard README

This dashboard is designed to provide insights into a dataset using Streamlit, Plotly, and Pandas. The code reads a dataset from an Excel file, filters the data based on user inputs for date range, region, state, and city, and then visualizes the data using various Plotly charts. Additionally, the dashboard allows users to download filtered and original data as CSV files.

## Video Demonstration

Explore a guided walkthrough of the dashboard by watching the "Program Demonstration" video available in the repository. The video provides a step-by-step overview of the dashboard's features and functionalities, helping you get started quickly.

## Instructions:

1. **Installation:**
   - Make sure you have Python installed on your machine.
   - Install the required libraries using the following command:
     ```
     pip install streamlit plotly pandas openpyxl plotly_express plotly figure_factory
     ```

2. **Run the Dashboard:**
   - Save the provided code in a file with a ".py" extension.
   - Open a terminal and navigate to the folder containing the file.
   - Run the following command to start the Streamlit app:
     ```
     streamlit run your_file_name.py
     ```

3. **Interact with the Dashboard:**
   - The dashboard will be accessible in your web browser. Interact with the date range, region, state, and city filters on the sidebar to dynamically update the visualizations.

4. **Visualizations:**
   - **Category wise Sales:** Bar chart displaying sales for each category.
   - **Region wise Sales:** Pie chart illustrating sales distribution across regions.
   - **Time Series Analysis:** Line chart depicting sales trends over time.
   - **Hierarchical view of Sales using TreeMap:** Treemap showcasing sales hierarchy by region, category, and sub-category.
   - **Segment wise Sales and Category wise Sales:** Pie charts displaying sales distribution by segment and category.
   - **Scatter Plot:** Scatter plot showing the relationship between sales, profit, and quantity.

5. **Download Data:**
   - Download filtered data for Category and Region, as well as Time Series data and the original dataset.

6. **Summary Tables:**
   - View a summary table of the top 5 rows and a pivot table showing month-wise sub-category sales.

7. **Scatter Plot and Data View:**
   - Explore a scatter plot depicting the relationship between sales and profits, and view a subset of the filtered dataset.

8. **Download Original DataSet:**
   - Download the entire original dataset.

