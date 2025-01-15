# Restaurant Data Analysis and Prediction

This project performs exploratory data analysis (EDA), geospatial analysis, feature engineering, and predictive modeling on a restaurant dataset to uncover valuable insights and make predictions regarding restaurant ratings.

## Libraries Used
- **pandas**: Data manipulation and analysis.
- **numpy**: Numerical operations.
- **matplotlib**: Data visualization.
- **seaborn**: Statistical data visualization.
- **folium**: Geospatial mapping.
- **scikit-learn**: Machine learning and model evaluation.

## Dataset

The dataset contains various restaurant details such as:
- Restaurant Name
- City
- Cuisines
- Latitude, Longitude
- Price Range
- Table Booking and Online Delivery Options
- Ratings (Aggregate)

The data is loaded from a CSV file, and the analysis is performed to derive useful insights and develop prediction models.

## Analysis and Tasks

### 1. Descriptive Analysis
- Statistical summary for numerical columns.
- Exploration of categorical variables like city, cuisine, and country.
- Insights on the most popular cuisines and cities.

### 2. Geospatial Analysis
- Visualizing restaurant locations on a map using **Folium**.
- Distribution of restaurants across cities.
- Correlation between restaurant location (latitude/longitude) and ratings.

### 3. Table Booking and Online Delivery Analysis
- Percentage of restaurants offering table booking and online delivery.
- Comparing ratings for restaurants that offer table booking.
- Analysis of online delivery options by price range.

### 4. Price Range and Feature Engineering
- Analysis of restaurant price ranges and average ratings.
- Feature engineering, including creating new features based on restaurant name length.

### 5. Predictive Modeling
- Predicting restaurant ratings using **Linear Regression** and **Random Forest** models.
- Evaluation metrics like RMSE and R² score for model performance.

### 6. Customer Preference and Data Visualization
- Analyzing ratings and popularity of cuisines.
- Visualizing the distribution of ratings and relationship between votes and ratings.

## Business Growth Insights

By analyzing the dataset, businesses in the restaurant industry can derive actionable insights to enhance their growth and customer satisfaction:

### 1. **Customer Preferences**
   - **Cuisines**: Understanding the most popular cuisines can help businesses optimize their menu offerings to cater to customer preferences and increase sales.
   - **Locations**: Identifying top cities with the highest number of restaurants allows businesses to target growth in areas with less competition or explore underserved regions.

### 2. **Service Offerings**
   - **Table Booking & Online Delivery**: Knowing the percentage of customers who prefer table booking and online delivery helps businesses enhance their services, offer promotions, and make strategic decisions for better customer engagement.
   - **Price Range**: Analyzing customer ratings based on different price ranges helps restaurants set competitive pricing strategies and optimize their value proposition to attract more customers.

### 3. **Improved Customer Experience**
   - **Rating Insights**: By predicting restaurant ratings, businesses can evaluate their performance based on key factors (such as price range, table booking, and customer votes) and focus on areas that require improvement.
   - **Personalized Offers**: Customer ratings and preferences can be used to design personalized promotions for specific cuisines or services, helping restaurants increase customer retention.

### 4. **Geospatial Optimization**
   - **Restaurant Locations**: Visualizing restaurant locations on a map enables businesses to spot areas with high competition or discover new locations that have high potential but are currently underserved.
   
### 5. **Data-Driven Decision Making**
   - The combination of statistical analysis, predictive modeling, and customer preference insights empowers restaurants to make data-driven decisions, resulting in higher customer satisfaction, improved services, and business growth.

## Files
- `restaurants_map.html`: A map displaying the locations of restaurants.
- The script performs all the tasks mentioned above and outputs key metrics and visualizations.

## How to Run
1. Clone the repository or download the script.
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn folium scikit-learn
3. Place your dataset CSV file in the appropriate path.
4. **Run the Notebook in Jupyter Lab:**
   - Open your terminal or command prompt and navigate to the directory where the Jupyter Notebook is saved.
   - Launch Jupyter Lab by running:
     ```bash
     jupyter lab
     ```
   - In Jupyter Lab, open the notebook (e.g., `restaurant_data_analysis.ipynb`).
   - Run the cells in the notebook one by one to perform the analysis.

5. **View the Output:**
   - The analysis results and visualizations (e.g., charts) will appear within the notebook.
   - A map will be saved as `restaurants_map.html` in the same directory.

6. **Optional: Visual Studio Code (VS)**
   - If you prefer, you can also open the Jupyter notebook in Visual Studio Code by installing the Jupyter extension.
   - Run the cells just as you would in Jupyter Lab.

## Conclusion

This project demonstrates how **data analysis** and **predictive modeling** can provide valuable insights to the restaurant industry. Through **exploratory data analysis (EDA)**, **geospatial visualization**, and **predictive models**, we identified key trends in restaurant ratings, customer preferences, and service offerings.

The findings highlight how businesses can leverage data to optimize their menu offerings, expand to high-demand areas, and improve customer experience. By understanding what drives customer satisfaction and the factors influencing restaurant ratings, businesses can take strategic actions to increase growth and retention.

### Future Directions:
- **Model Refinement**: Implement hyperparameter tuning and model optimization to improve prediction accuracy.
- **Expanded Data**: Integrate additional features, such as customer reviews or seasonal trends, to enhance model performance.
- **Advanced Modeling**: Explore more complex algorithms, such as **Gradient Boosting** or **XGBoost**, to further improve the prediction of restaurant ratings.

Overall, this project highlights the power of data science in transforming business strategies and supporting informed decision-making within the restaurant industry.
