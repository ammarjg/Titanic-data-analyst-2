# Titanic Data Analysis

This repository contains an in-depth analysis of the Titanic dataset using Python and Pandas. The project explores passenger survival trends, socio-economic impacts, and other interesting insights based on the data.

---

## Key Features
- Calculation of survival rates by class, gender, and embarkation port.
- Identification of duplicate ticket holders and group travel dynamics.
- Analysis of cabin assignments and deck distributions.
- Exploration of socio-economic disparities affecting survival.

---

## Key Insights
1. **Survival Rates by Class:**
   - First-class passengers had a significantly higher survival rate compared to those in third class.

2. **Port of Embarkation Impact:**
   - Passengers from Cherbourg had the highest survival rate (55.4%) compared to Queenstown (38.9%) and Southampton (33.7%).

3. **Group Travel Dynamics:**
   - 134 unique tickets were shared among multiple passengers, likely representing families or groups.

4. **Cabin Assignments:**
   - Only 22.9% of passengers had assigned cabins, indicating most third-class passengers did not have designated accommodations.

5. **Fare Disparities:**
   - Passengers from Cherbourg paid the highest fares, suggesting a wealthier demographic, which contributed to higher survival rates.

---

## Dataset Description

The dataset contains the following columns:

| Column Name   | Description |
|---------------|-------------|
| **PassengerId** | A unique identifier for each passenger. |
| **Survived**   | Survival indicator (0 = No, 1 = Yes). |
| **Pclass**     | Ticket class (1 = First, 2 = Second, 3 = Third). |
| **Name**       | Passenger’s full name. |
| **Sex**        | Gender of the passenger (`male` or `female`). |
| **Age**        | Passenger's age in years. |
| **SibSp**      | Number of siblings or spouses aboard the Titanic. |
| **Parch**      | Number of parents or children aboard the Titanic. |
| **Ticket**     | Ticket number assigned to the passenger. |
| **Fare**       | Fare paid for the ticket. |
| **Cabin**      | Cabin number (if assigned). |
| **Embarked**   | Port of embarkation (`C = Cherbourg`, `Q = Queenstown`, `S = Southampton`). |

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/ammarjg/titanic-data-analysis.git

2. Install required libraries:
```bash
    pip install pandas matplotlib seaborn




