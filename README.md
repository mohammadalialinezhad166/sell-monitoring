<h1>Sell-Monitoring Program</h1>
<h2>Overview</h2>

This Python-based Sell-Monitoring Program helps track and visualize sales data over specific time periods. It reads sales data from a CSV file, processes the information, and presents various insights, including daily, weekly, and monthly sales. The program also allows the user to add new data entries. It includes built-in functionalities to display sales trends and calculate total sales in different timeframes.
<hr>
<h2>Features</h2>

Sales Monitoring: View total sales over custom date ranges (monthly or weekly).

Data Input: Easily add new sales data directly from the program.

Data Visualization: Visualize trends and patterns in sales using interactive plots.

CSV-Based Storage: Sales data is stored and retrieved from a CSV file (dataset.csv), making it easy to maintain and update.
<hr>
<h1>Tasks and Approaches</h1>

1.Input New Sales Data:

Users can add sales data directly via the terminal. The program automatically calculates the total sale per item and appends it to the dataset.

2.Monthly Sales Monitoring:

Users can check total monthly sales. A filtered dataset is plotted with sales over a selected time range.

3.Weekly Sales Monitoring:

Users can view weekly sales for multiple time periods, with visual plots that distinguish between different sales intervals.

4.Total Sales Calculation:

The program computes total sales for a given range and provides a graphical output for visual analysis.
<hr>
<h2>Program Workflow</h2>

1.Reading Data:

The program uses pandas to load the CSV file containing sales data, with columns for item name, count, price, date, and sale.

2.Input Options:

The user is presented with four input options:
"n" for new data input
"m" to check monthly sales
"w" to check weekly sales
"t" to check total sales

3.Plotting Sales Data:

The program visualizes sales data using Matplotlib:
Monthly/weekly sales trends are plotted with labeled dates and sales values.
Green grids and rotated date labels make the graph easy to interpret.

4.Updating the Dataset:

When new sales data is entered, the program calculates total sales and updates the CSV file. The user can re-run the analysis to see the updated sales.
<hr>
<h2>Programming Map</h2>

<li>Data Input:</li>
Users input new sales data (name, count, price, date). The program calculates total sale and appends it to the dataset.csv file.

<li>Monthly/Weekly Sales Calculation:</li>
Users enter a start and end date. The program filters the sales data within the specified range and generates plots for both monthly and weekly sales trends.

<li>Total Sales Analysis:</li>
The total sales for a given period are calculated and displayed on a graph.
<hr>
<h2>Technologies and Libraries Used</h2>
<li><b>Python:</b> Core programming language for implementation.</li>
<li><b>pandas:</b> For data manipulation and CSV file handling.</li>
<li><b>Matplotlib:</b> For generating graphical representations of sales data.</li>
<li><b>CSV:</b> Used for storing and retrieving sales data.</li>
<hr>
<h2>Getting Started</h2>
    <p>To run this project on your local machine:</p>
    <ol>
        <li>Clone this repository to your local machine.</li>
        <pre><code>git clone https://github.com/yourusername/sell-monitoring-program.git</code></pre>
        <li>Install the required libraries using the following command:</li>
        <pre><code>pip install pandas matplotlib</code></pre>
        <li>Place your <code>dataset.csv</code> file in the same directory as the script.</li>
        <li>Run the Python script using:</li>
        <pre><code>python sales_monitor.py</code></pre>
    </ol>
<h2>Usage</h2>
    <p>Once you run the program, you will have the following options:</p>
    <ul>
        <li>Enter <strong>"n"</strong> to input new sales data.</li>
        <li>Enter <strong>"m"</strong> to visualize monthly sales data.</li>
        <li>Enter <strong>"w"</strong> to visualize weekly sales data.</li>
        <li>Enter <strong>"t"</strong> to check total sales for a specific date range.</li>
    </ul>

<h2>Example</h2>
    <p>The following is an example of how to input new data:</p>
    <pre><code>
    Enter your new data: product_name count price date
    Example: "Product1 10 200 1402-12-09"
    </code></pre>

<h2>Tasks & Approaches</h2>
    <p>This project uses the following approaches:</p>
    <ul>
        <li>Data processing with <strong>Pandas</strong> for reading and manipulating CSV data.</li>
        <li>Visualization with <strong>Matplotlib</strong> to create line plots for sales data.</li>
        <li>Interactive user input for adding new data and selecting date ranges.</li>
        <li>Efficient grouping and filtering of sales data by date to visualize trends.</li>
    </ul>

<h2>Programming Map</h2>
    <ol>
        <li>Load data from <code>dataset.csv</code>.</li>
        <li>Provide an option for users to input new data.</li>
        <li>Plot and visualize sales trends (weekly, monthly, total).</li>
        <li>Save any new data entries back to the CSV file for future use.</li>
    </ol>

<h2>Contributing</h2>
    <p>Feel free to contribute to this project by submitting a pull request or reporting issues.</p>

<h2>License</h2>
    <p>This project is licensed under the MIT License.</p>
