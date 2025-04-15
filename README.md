# Restaurant-Analysis

In this notebook, I explored, preprocessed, and analyzed restaurant data to uncover useful insights—especially around customer ratings.

🧪 Task 1: Data Exploration and Preprocessing

Imported the necessary libraries—Pandas and NumPy for data manipulation, and Matplotlib and Seaborn for visualization.

📂 Dataset Loading

Loaded the dataset into a DataFrame named rest_data.
This dataset contains various features related to restaurants, such as cuisines, ratings, price range, and more.

🔍 Basic Exploration

Checked the shape of the dataset—the number of rows and columns.
Then, I inspected the structure and checked for missing values across each column.
This helped me to decide how to handle any incomplete data—either by filling it or removing it depending on the context.

🔄 Data Cleaning

Performed some cleaning operations.
For instance, I might drop irrelevant columns and converted data types
This step is crucial to ensure our data is ready for meaningful analysis.

📊 Target Variable: Aggregate Rating

Analyzed its distribution to understand how customers are rating the restaurants.

Interestingly, the least common rating is 1.8, which only appears once.
This kind of imbalance might affect model training if we were to build a predictive model later.

📈 Visualizations and Insights

Used Seaborn and Matplotlib to visualize the data.
This includes plotting rating distributions, relationships between price and rating, or how different cuisines perform.
These visuals helped to spot trends and patterns.

🧠 Key Observations

Certain cuisines tend to receive higher ratings.

Higher price ranges often correlate with better ratings.

Some locations consistently perform better than others.

✅ Conclusion

In conclusion, this analysis helps uncover important insights that can support Restaurant business strategy.
Understanding which factors influence customer satisfaction can guide better decisions in marketing, pricing, and expansion.













