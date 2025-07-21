🚗 US Accidents Data Analysis (2016–2023)
This project analyzes motor vehicle accidents in the United States from 2016 to 2023 using a large dataset containing over 7 million records, sourced from the internet. The goal is to understand trends, geographical distributions, and contributing factors to accidents, with a focus on weather, traffic, time, and location.

📁 Dataset Overview
The dataset includes key features such as:

📍 Location: City, State, Latitude, Longitude

🕒 Time: Start Time, End Time

📊 Severity: Scale from 1 to 4

🌦️ Weather: Conditions, Temperature, Wind Speed, Visibility

🚧 Road Conditions: Presence of bumps, curves, junctions

🚦 Traffic Influence

⚠️ Note: Data for New York City is missing, despite its population and significance.

🧹 Data Cleaning
Removed columns with high missing values to ensure quality.

Ensured datetime columns were in proper format.

Identified and handled outliers in numerical data.

📊 Exploratory Data Analysis (EDA)
Key Discoveries:
City Distribution: A few cities account for most accidents, while 1000+ cities had only one recorded accident.

Day of Week: Weekdays see more accidents than weekends.

Weather Conditions: Surprisingly, many accidents occurred under fair weather.

Time of Day: Peak hours were 6 AM – 10 AM and 3 PM – 6 PM.

Yearly Trends: Fluctuations observed year over year, possibly due to changing traffic laws or societal behavior.

❓ Questions Explored
Are there more accidents in warmer or colder regions?

Which five states have the most accidents?

Also analyzed accidents per capita.

Is New York City present in the data?

Among the top 100 cities, which states dominate?

Which times of day are most accident-prone?

How do weekdays vs weekends compare?

What are the peak months for accidents?

What are the yearly trends in accident numbers?

When are accidents per traffic unit the highest?

How are accidents distributed hourly across weekdays/weekends?

What is the impact of weather on accident rates?

Does temperature influence severity?

📌 Key Insights
🚫 Missing NYC Data: A major gap in the dataset.

📉 Skewed Distribution: Only <8% of cities report more than 1000 accidents.

🏙️ Sparse Cities: Over 1000 cities report only a single accident.

📅 Weekday Traffic: Heavier accident rates compared to weekends.

📈 Data Visualization (via Tableau)
🗺️ Heat Maps: Visualized accident density using latitude & longitude.

📊 Bar Charts: Displayed accident counts by state, city, and weather.

📉 Line Graphs: Showed accident trends across months and years.

Visualizations were created to reveal patterns and support strategic decision-making.

🧰 Tools & Technologies
Python (Pandas, NumPy, Matplotlib, Seaborn)

Tableau for interactive dashboards

Jupyter Notebook for analysis

📎 License
This project is for educational and analytical purposes only. Data is sourced from publicly available platforms(Kaggle).

🙌 Acknowledgments
Thanks to the creators of the US Accidents dataset and the open-source community for supporting data-driven insights.
