# 🚢 Titanic Survival Prediction – A Machine Learning Project

This project is built around the famous Titanic dataset to explore passenger data and predict survival using a machine learning classification model.

## 🎯 Objective

The goal was to develop a predictive model that can determine whether a passenger survived the Titanic disaster based on features like age, gender, passenger class, fare, and port of embarkation. The project emphasizes data preprocessing, model development, and performance evaluation.

## 📊 Dataset Information

The dataset contains the following key features:
- `Pclass` – Ticket class (1st, 2nd, 3rd)
- `Sex` – Gender of the passenger
- `Age` – Age in years
- `SibSp`, `Parch` – Number of siblings/spouses/parents aboard
- `Fare` – Ticket price
- `Embarked` – Port of Embarkation (C, Q, S)
- `Survived` – Target variable (0 = No, 1 = Yes)

## 🧪 What I Did

- **Exploratory Data Analysis (EDA)** to understand trends.
- **Handled missing values** in columns like `Age` and `Embarked`.
- **Encoded categorical variables** like `Sex` and `Embarked`.
- **Feature selection** based on correlation and relevance.
- **Trained a Random Forest classifier** for binary classification.
- **Evaluated performance** using Accuracy, Precision, Recall, and Confusion Matrix.
- **Visualized insights** using seaborn and matplotlib.

## 🎯 1. Most Passengers Did Not Survive

A pie chart of the overall survival rate revealed that only about 38% of passengers survived, while 62% perished in the tragedy.

📊 This reflects the scale of the disaster, where more than half of the passengers lost their lives.
## 🎩 2. Class and Gender Significantly Influenced Survival

A bar plot comparing survival by class and gender showed:

    1st class passengers, especially females, had the highest survival rates.

    3rd class passengers, particularly males, were the least likely to survive.
🚢 This indicates a strong class divide in evacuation, and that being in first class dramatically increased one's chance of survival.
## 👶 3. Age and Gender Influenced Survival Patterns

A violin plot examining age distribution among survivors showed:

    Survivors tended to be younger.

    Children and females were more likely to survive, supporting the historic “women and children first” evacuation protocol.
👩‍👧 This policy visibly shaped who had a better chance of making it out alive.
## 💰 4. Higher-Class Passengers Paid More

A box plot visualizing fare by class revealed:

    Passengers in 1st class paid significantly more.

    The fare distribution increased sharply from 3rd to 1st class, emphasizing the economic divide onboard.
💸 Wealth directly influenced not just travel experience, but also survival opportunities.
## 🧾 5. High Fare Correlated with Higher Survival

A swarm plot of fare vs. survival showed that:

    Passengers who paid higher fares were more likely to survive.

    This reaffirms the idea that first-class passengers were prioritized during evacuation.
🛟 Money, in this case, could buy a better chance at life.
## 🚢 6. Embarkation Port Affected Survival Rates

Stacked bar charts revealed that:

    Passengers who embarked from Cherbourg (C) had the highest survival rate.

    Those from Queenstown (Q) had the lowest.
🧳 This might be linked to socio-economic status and class distribution by boarding port.
## 7. 🔍 Feature Correlations Support Observations

The correlation heatmap showed:

    Fare had a positive correlation with survival.

    Pclass had a negative correlation, meaning higher class (lower number) was linked to better survival odds.
📈 The data backs up the earlier observations — wealth and class mattered deeply.

# ✅ Conclusion

This project demonstrated how machine learning and data analysis can uncover meaningful patterns from historical events. Survival on the Titanic was clearly influenced by passenger class, gender, age, fare, and embarkation port—highlighting social and economic divides.

Using a Random Forest Classifier, we built an effective model that predicted survival with good accuracy, while also gaining insights through visual exploration. The analysis reflected real-world priorities of the time, such as the “women and children first” policy and the privilege of higher-class passengers.

Overall, this project showcased the power of combining data science with storytelling to understand and predict real-world outcomes.
