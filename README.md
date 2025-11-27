<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">

</head>
<body>

<h1><img width="48" height="48" alt="image" src="https://github.com/user-attachments/assets/c8bcac37-2523-4992-9872-3a64573d3282" />IMDB Movie Sales Analysis: A Power BI Dashboard</h1>

<h2>📄 **Project Description:-**</h2>
<p>
  This project leverages Power BI to explore and analyze weather data from 2021 to 2024 across Telangana's districts and mandals. It visualizes patterns in rainfall, temperature, humidity, and wind speed to uncover climate behavior, seasonal shifts, and extreme weather events. These insights aim to support sustainable decision-making in agriculture, disaster management, and climate adaptation planning.
</p>

<hr>

<h2>🎯** Project Goal:-**s</h2>
<ul>
<li>🔎 Understand what historical factors (genre, budget, cast, release date, IMDb rating etc.) correlate with movie financial success.</li> 
<li>📈 Build predictive models (regression or classification) to estimate a movie’s box-office revenue or success probability before its release. :contentReference[oaicite:1]{index=1}</li> 
<li>📊 Analyze patterns and trends over time — e.g. how genre preferences, budget-to-revenue ratios, ratings vs revenue relationships change across years. :contentReference[oaicite:2]{index=2}</li> 
<li>🧰 Provide actionable insights/visual dashboards for studios, producers, marketers — to help them optimize production budget, marketing strategy, release timing, and casting decisions. :contentReference[oaicite:3]{index=3}</li>
 <li>📚 Explore qualitative and quantitative movie attributes (e.g. user ratings, genre, cast, runtime, reviews) to understand their impact on both critical and commercial success. :contentReference[oaicite:4]{index=4}</li>
 <li>🎯 Help stakeholders (producers, investors, data-analysts) reduce risk when green-lighting projects by offering data-driven revenue forecasts and success-likelihood assessments. :contentReference[oaicite:5]{index=5}</li> </ul>
</ul>

<hr>

<h2>📊** Key Analysis Sections:-** </h2>
<ul> 
  <li>🎯 **Overview / Dashboard Summary** — KPI cards for Total Movies, Total Box-Office Revenue, Average Rating, Average ROI, Total Budget, Total Profit; quick snapshot of overall performance. </li>
  <li>📅 **Trend Over Time** — Line chart or area chart: “Box-Office Revenue (Year-wise)”, “Number of Movies Released (Year-wise)”, “Average Rating Over Years”, “Budget vs Revenue Trend”. </li>
  <li>🎬 **Genre & Category Analysis** — Bar / column charts: “Top-Grossing Genres”, “Movies Count by Genre”, “Average ROI by Genre”, “Average Rating by Genre”. </li>
  <li>🏭 **Studio / Production Company / Director Analysis** — Charts / tables: “Top Studios by Total Revenue”, “Average Budget vs Revenue by Studio/Director”, “Most Profitable Directors/Studios”. </li>
  <li>🌍 **Regional / Market Analysis** — Maps or bar charts / heat-maps: “Revenue by Region / Country”, “Number of Movies by Region”, “ROI by Region / Market”, “Rating by Region” (if applicable). </li>
  <li>📈 **Budget vs Revenue & Profitability Analysis** — Scatter plots or bar charts: “Budget vs Gross”, “Gross/Budget Ratio by Movie or Studio”, “Profit Margin Distribution”, “Low-Budget High-Return Movies”. </li>
  <li>⭐ **Ratings & Audience Reception Analysis** — Charts / tables: “IMDb Rating Distribution”, “Rating vs Gross Scatter Plot”, “Votes / Reviews vs Box-Office Performance”. </li>
  <li>📊 **Top Performers & Outliers** — Lists / bar charts / tables: “Top 10 Highest Grossing Movies”, “Top Rated Movies vs Box-Office”, “Movies with Highest ROI”, “Underperforming Big-Budget Movies”. </li>
  <li>📆 **Release Timing & Seasonality Analysis** — Heat-map or line/bar charts: “Releases by Month/Quarter”, “Revenue by Release Month/Season”, “Success Rate by Release Timing”. </li>
  <li>📑 **Detailed Movie/Profile View (Drill-Down)** — When a user selects a movie: show detailed attributes — Title, Year, Genre, Budget, Box-Office Gross, Rating, Votes, ROI, Studio, Director, etc. — and compare to decade or genre averages. </li>
  <li>🔎 **Custom Filter & Segmentation Panel** — Filter / slicer controls for Year, Genre, Studio, Region, Budget Range, Rating Range — letting users slice the data to focus on segments of interest. </li>
</ul>

<hr>

<h2>🛠️ **Tools and Technologies:-**</h2>
<ul>
  <li>Power BI Desktop – Visualizations & DAX Power</li>
  <li>Query – Data transformation </li>
  <li>Excel/CSV – Raw dataset source</li>
  <li>DAX – Measures & calculated columns</li>
</ul>

<hr>

<h2>🌍 **Real-World Applications (IMDb Movie & Sales Analysis):-** </h2>
<ul>
  <li>🎞️ Studios & Producers – Forecast box-office earnings and Return on Investment (ROI) before production or release, using historical IMDb + revenue + metadata. :contentReference[oaicite:1]{index=1}</li> 
  <li>📈 Distributors & Marketers – Analyze which genres, release timings, casts or budgets tend to succeed, to optimize release date, marketing spend and distribution strategy. :contentReference[oaicite:2]{index=2}</li> 
  <li>🧠 Data Scientists & Analysts – Use IMDb datasets (ratings, votes, metadata) + box-office/budget data to build predictive models (regression, ML, deep learning) for movie success or failure. :contentReference[oaicite:3]{index=3}</li> 
  <li>🎯 Content Strategy & Production Planning – Identify emerging trends: which genres, run-times, themes or “emotional arcs” resonate more with audiences and yield higher returns. :contentReference[oaicite:4]{index=4}</li> 
  <li>📰 Film Critics / Media Analysts – Use IMDb + box-office data to study relationships / correlations: e.g. between user-votes or ratings and actual financial performance; examine what factors drive popularity vs profit. :contentReference[oaicite:5]{index=5}</li>
   <li>👥 Fans & General Public – Explore patterns in movie success, understand market trends (popular genres, typical budgets vs hits), and make data-driven recommendations or predictions about upcoming releases. </li>
</ul>

<hr>

<h2>📁 **Dataset Details:-**</h2>
<ul>
  <li>Data Source: Movie Sales Analysis Records (Simulated Dataset)</li> 
  <li>Time Frame: 2006 to 2016</li>
  <li>Features: Count of titles, genres, actors, directors, and average runtime.</li>
  <li>KPI Tracking: Target vs. actual revenue, including % overachievement.</li>
</ul>

<hr>

<h2>🧭 **How to Explore the Dashboard:-**</h2>
<ul>
  <li>Use filter panels to switch between Dates, districts, Mandal and seasons</li>
  <li>Use filter panels (e.g. date-range pickers, region/ district / category selectors) to refine which subset of data you want to view — this helps focus on relevant periods or segments. :contentReference[oaicite:0]{index=0}</li> 
  <li>Hover over charts or data points to see tooltips or data labels for more detailed values and context without cluttering the main view. :contentReference[oaicite:1]{index=1}</li> 
  <li>Switch between different analysis tabs or views (for example: Rainfall, Temperature, Humidity, Wind Speed — or equivalent in your domain) to explore different facets of the data. </li> 
  <li>Use drill-down or click-on-visual features (where available) to dive deeper — e.g. clicking on a bar/region to view underlying data breakdowns. :contentReference[oaicite:2]{index=2}</li> 
  <li>Reset or clear filters when you want to return to a full or default view. A visible “Reset” or “Clear Filters” button helps ensure users don’t get stuck in a narrow filtered state. :contentReference[oaicite:3]{index=3}</li>
</ul>

<h2>📌** In summary:-** </h2>
<p>
  This analysis provides a comprehensive understanding of factors influencing movie ratings on IMDB. The findings can guide future movie productions in choosing genres, directors, and budgeting to optimize success. Ongoing analysis and additional factors such as marketing, release timing, and audience demographics can further refine these insights.

</p>
</body>
</html> 
