
# Nutri Path: Calorie & Nutrient Recommender
Empowering Personalized Nutrition with Smart Food Insights
## Overview

**Nutri Path** is a personalized daily calorie and nutrient recommender based on the user's age, weight, height, activity level, and dietary type (Vegan, Vegetarian, Non-Vegetarian). The system retrieves food nutrient data using the USDA Food Central API and suggests a list of foods tailored to the user's dietary preferences and health goals.

## Key Features:
- **Personalized Recommendations**: Provides daily calorie intake and nutrient distribution for the user.
- **Dietary Preferences**: Supports Vegan, Vegetarian, and Non-Vegetarian options.
- **Nutritional Data Retrieval**: Uses USDA Food Central API to gather nutrient information for various food items.
- **Visualizations**: Provides advanced visualizations of nutrient breakdown, caloric distribution, and food contributions.

## Tech Stack:
- **Python**: Core programming language.
- **Jupyter Notebook**: Interactive environment for data analysis and model training.
- **USDA Food Central API**: For fetching food and nutrient data.
- **Matplotlib & Seaborn**: For data visualization.
- **Pandas & NumPy**: For data manipulation and analysis.
- **scikit-learn**: For training the recommendation model.

## Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/KRISHNARAJ-D/Nutri-Path.git
   cd Nutri-Path-Calorie-Nutrient-Recommender
## User Input:
### Input data
age 
weight
height
activity_level
dietary_type 

## Get recommendations
recommendations = get_recommendations(age, weight, height, activity_level, dietary_type)

## Output:
![output ibm](https://github.com/user-attachments/assets/8604ca14-1a79-4260-868b-eaf35a94f1c8)

![chart ibm](https://github.com/user-attachments/assets/07e8604b-f203-43c1-a94c-0d187938fec7)
