Bike-Sharing Data Analysis – My Report

I analyzed a bike-sharing dataset, 'Bike_sharing_data.csv', to explore usage patterns using Python. The dataset includes columns: datetime, season, holiday, workingday, weather, temp, atemp, humidity, and windspeed. My goal was to clean the data, analyze environmental impacts on bike usage, and visualize insights.

I cleaned the data by filling missing numeric values (temp, humidity) with medians and categorical values (season, weather) with modes. Outliers, like unrealistic windspeed, were corrected. I ensured datetime was properly formatted, extracting hours and days for analysis.

I calculated statistics for temp, humidity, and windspeed, and analyzed trip counts (assumed available) by season, weather, and workingday. I filtered trips for clear weather (weather == 1) and sorted by temp to identify high-demand conditions. Using groupby, I aggregated trip counts by season, and pivot tables summarized usage by weather and holiday.

Visualizations included a histogram of trip counts, a bar plot of trips by season, a scatter plot of trips vs. temp, and a box plot of trips by weather. These revealed higher usage in warm, clear conditions.

This project honed my data cleaning and visualization skills. I’d next explore machine learning to predict demand based on season and weather.
