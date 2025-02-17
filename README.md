IPL Match Analysis with Pandas, Matplotlib, and Seaborn

This project analyzes IPL match data using Python libraries such as Pandas, Matplotlib, and Seaborn. The notebook explores team performances, player achievements, and match trends, offering both statistical insights and visualizations.


---

📊 Project Structure

1. Dataset:

A custom IPL dataset containing information about matches, including seasons, teams, winning teams, cities, players of the match, and runs scored.

The dataset is created using a Python dictionary and converted into a Pandas DataFrame.



2. Data Exploration:

Displays the first five rows of the dataset.

Provides a summary of data types and non-null counts using info().

Offers descriptive statistics (mean, max, min, etc.) with describe().



3. Team Performance Analysis:

Groups matches by city and calculates the number of wins for each team in each location.

Uses groupby and value_counts to create a pivoted DataFrame for city-wise wins.



4. Player of the Match Analysis:

Identifies the top 3 players with the most "Player of the Match" awards.

Uses value_counts to quickly extract top performers.



5. Runs Scored Insights:

Finds the highest runs scored in a match using the max() method.





---

📈 Visualizations

1. Wins by City:

A bar plot comparing the number of wins for Mumbai Indians (MI) and Chennai Super Kings (CSK) across different cities.

Created using Seaborn’s barplot with clear legends and axis labels.



2. Runs Distribution:

A histogram showing the distribution of runs scored in matches.

Helps visualize match frequency based on runs, using Matplotlib.





---

🚀 Technologies Used

Pandas: DataFrame creation and manipulation.

Matplotlib: Plotting graphs and visualizing trends.

Seaborn: Creating attractive and informative statistical graphics.



---

📝 How to Run

1. Open the Google Colab notebook here.


2. Run the cells in order to explore IPL match trends.


3. Modify the dataset to analyze additional teams, seasons, or players.




---

✨ Contributions & Feedback
Feel free to fork this repository, open issues, or submit pull requests if you’d like to enhance the analysis or add new features!

