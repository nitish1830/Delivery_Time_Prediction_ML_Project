## Project Summary

### Plan Stage
- **Goal**: Our aim was to build a model that predicts how long it takes for a food order to be delivered.
- **Data**: We had two datasets to work with - `Data_Train.xlsx` and `Data_Test.xlsx`. These contained details about restaurants, average cost, minimum order, ratings, votes, reviews, location, and cuisines.

### Analyze Stage
- **Data Exploration**:
  - First, we took a close look at the data to understand its structure and what it holds.
  - We checked how many rows and columns the datasets had, got an idea of the values they contain, and looked for any missing information.
- **Data Cleaning and Preprocessing**:
  - We needed to make sure the data was in a usable state. This involved fixing things like strange characters in the 'Average_Cost' and 'Minimum_Order' columns.
  - We also wanted to handle missing or incorrect values in columns like 'Rating', 'Votes', and 'Reviews'. Making them numeric and uniform was important.
  - We broke down some columns like 'Location' and 'Cuisines' into separate components for easier analysis.

### Construct Stage
- **Data Visualization**:
  - We used graphs and plots to visually explore the data. This helped us see patterns and relationships between different aspects like ratings, votes, and the delivery time.
- **Data Preprocessing**:
  - We needed to ensure the data was ready for the model. This involved tasks like handling any missing values by marking them as "NAN".
  - Some algorithms work better with numerical data, so we converted non-numeric data into numeric form using a technique called label encoding. We also scaled the data to ensure all features had equal importance.
- **Model Building**:
  - To create the predictive model, we used a popular algorithm called XGBoost. It's known for its accuracy and efficiency.

### Execute Stage
- **Model Evaluation**:
  - We wanted to see how well our model worked. So, we split the data into two parts: one for training the model and another for testing it.
  - After training the model, we checked its accuracy - it turned out to be 0.78, a decent score indicating the model's ability to predict delivery times accurately.
- **Feedback and Conclusion**:
  - Finally, we shared this outcome and our insights with stakeholders. We emphasized that our model could be further improved and that their feedback is vital for refining it. Overall, the project showcased how we could estimate delivery times for food orders effectively using this approach.
