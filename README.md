<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Data Analysis & Advanced Visualization (Baby Names Dataset)</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
        }
        h1, h2 {
            color: #333;
        }
        code {
            background-color: #f4f4f4;
            padding: 2px 4px;
            border-radius: 4px;
        }
        pre {
            background-color: #f4f4f4;
            padding: 10px;
            border-radius: 4px;
            overflow-x: auto;
        }
        ul {
            margin: 10px 0;
        }
        a {
            color: #1a73e8;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <h1>Data Analysis & Advanced Visualization (Baby Names Dataset)</h1>

    <h2>Overview</h2>
    <p>
        This project analyzes the popularity of baby names in the United States over time, utilizing the dataset <code>us_baby_names.csv</code>. It explores the trends in baby names from 1880 to 2018, including the identification of evergreen names, most popular names, and unisex names. The project also delves into creating advanced visualizations and features like popularity and rank, offering insights into how certain names have maintained or changed their popularity over the years.
    </p>

    <h2>Setup</h2>

    <h3>Prerequisites</h3>
    <ul>
        <li>Python 3.x</li>
        <li>Libraries: <code>pandas</code>, <code>matplotlib</code>, <code>numpy</code>, <code>seaborn</code></li>
    </ul>

    <h3>Installation</h3>
    <pre><code>pip install pandas matplotlib numpy seaborn</code></pre>

    <h3>Dataset</h3>
    <p>Ensure the dataset <code>us_baby_names.csv</code> is available in the project directory.</p>

    <h2>Code Structure</h2>

    <h3>1. Initial Data Inspection</h3>
    <ul>
        <li><strong>Load</strong> and <strong>inspect</strong> the dataset.</li>
        <li>Check for unique values and data types, and convert the <code>Gender</code> column to a categorical data type.</li>
    </ul>

    <h3>2. Analyzing the Most Popular Names in 2018</h3>
    <ul>
        <li>Identify the top 10 most popular baby girl and boy names for the year 2018.</li>
        <li><strong>Function</strong> <code>most_pop(year, gender, n)</code>: Returns the <code>n</code> most popular names for a specified year and gender.</li>
    </ul>

    <h3>3. Evergreen Names (1880 - 2018)</h3>
    <ul>
        <li>Find evergreen boy and girl names that were among the top 20 most popular names in both 1880 and 2018.</li>
        <li>Use data merging techniques to identify these names.</li>
    </ul>

    <h3>4. Advanced Data Aggregation</h3>
    <ul>
        <li>Create an aggregated DataFrame <code>agg</code> to summarize name statistics, including total counts, the number of years the name appeared, first and last appearances, the maximum count in a single year, and the most popular year.</li>
        <li>Reset the index and filter for specific name-gender combinations, such as <code>(Mary, F)</code>.</li>
    </ul>

    <h3>5. Most Popular Names of All Time</h3>
    <ul>
        <li>Identify the top 10 most popular male and female names of all time based on total count.</li>
        <li>Visualize the results using a bar plot.</li>
    </ul>

    <h3>6. General Trends Over Time (1880 - 2018)</h3>
    <ul>
        <li>Count and visualize the total number of registered babies and unique names per year.</li>
        <li>Create bar plots to show trends over time.</li>
    </ul>

    <h3>7. Creating Features "Popularity" and "Rank"</h3>
    <ul>
        <li>Add columns to calculate the popularity (babies per million) and rank of names for each year.</li>
        <li>Update the DataFrame to include these new features.</li>
    </ul>

    <h3>8. Visualizing Name Trends Over Time</h3>
    <ul>
        <li>Create visualizations to show the popularity and rank of specific names over time.</li>
        <li>Use a reusable function to plot trends for evergreen names.</li>
    </ul>

    <h3>9. Investigating Popularity Changes</h3>
    <ul>
        <li>Add columns to track the change in popularity from the previous year.</li>
        <li>Filter and visualize names that experienced the most significant changes in popularity.</li>
    </ul>

    <h3>10. Persistent vs. Spike-Fade Names</h3>
    <ul>
        <li>Analyze names with persistent popularity versus those that had a sudden spike and faded.</li>
        <li>Create visualizations for both persistent and spike-fade names.</li>
    </ul>

    <h3>11. Most Popular Unisex Names</h3>
    <ul>
        <li>Identify the most popular unisex names, defined as names given to both boys and girls.</li>
        <li>Filter the results to find names that are almost equally popular among both genders.</li>
    </ul>

    <h2>Running the Project</h2>
    <p>
        Execute the code sequentially to reproduce the analysis and visualizations. Each section of the code is self-contained and can be run independently, depending on the analysis you wish to perform.
    </p>

    <h2>Results</h2>
    <p>
        This project provides a comprehensive analysis of baby names in the U.S., revealing trends and insights into the changing popularity of names over the years. Visualizations and summary statistics offer a clear understanding of these trends, making the project valuable for anyone interested in names, cultural shifts, or data analysis.
    </p>
</body>
</html>
