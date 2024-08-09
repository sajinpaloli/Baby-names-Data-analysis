<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Data Analysis & Advanced Visualization (Baby Names Dataset)</title>
</head>
<body>

<h1>Data Analysis & Advanced Visualization (Baby Names Dataset)</h1>

<h2>Overview</h2>
<p>This project provides a comprehensive analysis of the US baby names dataset from 1880 to 2018. It involves data inspection, aggregation, visualization, and the creation of functions to explore trends and patterns in baby names over time.</p>

<h2>Dataset</h2>
<ul>
    <li>The dataset used is <code>us_baby_names.csv</code>, which contains records of baby names in the United States from 1880 to 2018.</li>
</ul>

<h2>Project Structure</h2>
<p>The project is structured into various sections, each performing a specific analysis or task:</p>

<h3>1. First Inspection: The Most Popular Names in 2018</h3>
<ul>
    <li><strong>Load and Inspect Data:</strong> Load the dataset into a DataFrame and inspect it.</li>
    <li><strong>Most Popular Names in 2018:</strong> Identify the most popular baby girl and boy names in 2018.</li>
    <li><strong><code>most_pop()</code> Function:</strong> A custom function to return the <code>n</code> most popular names for a given gender in a specified year.</li>
</ul>

<h3>2. Evergreen Names (1880 - 2018)</h3>
<ul>
    <li><strong>Evergreen Names:</strong> Find names that were popular both in 1880 and 2018 among the top 20 names for each gender.</li>
</ul>

<h3>3. Advanced Data Aggregation</h3>
<ul>
    <li><strong>Aggregated DataFrame:</strong> Create an aggregated DataFrame <code>agg</code> that summarizes each name's total count, the number of years it appeared, and its first and last year of appearance.</li>
    <li><strong>Best Year:</strong> Identify the year when each name was most popular.</li>
</ul>

<h3>4. Most Popular Names of All Time</h3>
<ul>
    <li><strong>Top 10 Names:</strong> Find the 10 most popular male and female names across all years.</li>
</ul>

<h3>5. General Trends Over Time (1880 - 2018)</h3>
<ul>
    <li><strong>Babies per Year:</strong> Count and visualize the total number of registered babies per year.</li>
    <li><strong>Unique Names per Year:</strong> Count and visualize the number of unique names per year.</li>
</ul>

<h3>6. Creating the Features "Popularity" and "Rank"</h3>
<ul>
    <li><strong>Popularity:</strong> Add a column to the DataFrame representing the popularity of each name in terms of babies per million.</li>
    <li><strong>Rank:</strong> Add a column to rank names within each gender and year.</li>
</ul>

<h3>7. Visualizing Name Trends Over Time</h3>
<ul>
    <li><strong>Name Trends:</strong> Visualize the popularity and rank of names over time for evergreen names.</li>
</ul>

<h3>8. Sudden Changes in Popularity</h3>
<ul>
    <li><strong>Popularity Lag and Diff:</strong> Add columns to capture changes in popularity from the previous year.</li>
    <li><strong>Top Changes:</strong> Identify names with the largest sudden changes in popularity.</li>
</ul>

<h3>9. Persistent vs. Spike-Fade Names</h3>
<ul>
    <li><strong>Spike Scores:</strong> Calculate and sort names based on their spike scores, identifying names that either persisted or faded quickly.</li>
</ul>

<h3>10. Most Popular Unisex Names</h3>
<ul>
    <li><strong>Unisex Names:</strong> Identify the most popular unisex names of all time and compare their usage across genders.</li>
</ul>

<h2>Installation and Usage</h2>
<ol>
    <li><strong>Clone the Repository:</strong>
        <pre><code>git clone https://github.com/your-username/baby-names-analysis.git</code></pre>
    </li>
    <li><strong>Navigate to the Project Directory:</strong>
        <pre><code>cd baby-names-analysis</code></pre>
    </li>
    <li><strong>Install Required Packages:</strong> Install the necessary Python packages using the requirements file.
        <pre><code>pip install -r requirements.txt</code></pre>
    </li>
    <li><strong>Run the Notebook:</strong> Open and run the Jupyter notebook to perform the analysis.
        <pre><code>jupyter notebook baby_names_analysis.ipynb</code></pre>
    </li>
</ol>

<h2>Dependencies</h2>
<ul>
    <li>Python 3.x</li>
    <li>Pandas</li>
    <li>Matplotlib</li>
    <li>Seaborn</li>
    <li>Numpy</li>
</ul>

<h2>Results</h2>
<p>Visualizations and insights on the most popular names, evergreen names, general trends, and more. A set of reusable functions for analyzing baby names.</p>

<h2>Contributing</h2>
<p>If you'd like to contribute, feel free to fork the repository and submit a pull request. All contributions are welcome!</p>


<h2>Acknowledgments</h2>
<ul>
    <li>The dataset is sourced from the United States Social Security Administration (SSA).</li>
    <li>Inspiration for the analysis was drawn from various data science and visualization resources.</li>
</ul>

</body>
</html>
