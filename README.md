# Data Collection
Contains over 1000 recipes from the Allrecipes website . The 2 datasets below contain the information as specified below-

recipes.csv
![image](https://user-images.githubusercontent.com/55248640/209846004-f9bbe912-26da-4853-a280-b489d55529d0.png)

test_recipes.csv	
![image](https://user-images.githubusercontent.com/55248640/209846117-33da7177-b7e6-4e7e-ae61-f29176489be2.png)

The datasets can be downloaded from Kaggle - https://www.kaggle.com/datasets/thedevastator/better-recipes-for-a-better-life
Alternatively it can also be downloaded from - https://drive.google.com/uc?id=1K2J4GryH4OyzFYyjfCeCjbRPNhugb1DH and https://drive.google.com/uc?id=1MBhfHXuoBZ6YccOuujdcrUEFAw6W__oD

# Pre-processing of the dataset-

1)Parsing through the list of ingredients to segregate them into unit quantity and the ingredient itself
2)This involves removing the verbs and stopwords, to retain only the actual ingredients
3)Parsing through the cuisine to retrieve the specific cuisine the recipe may belong to
4)Checking for potential outliers and null values in the dataset
5)Dropping out columns that are not a part of our analysis
6)Changing the Total time in both of the datasets into a standard format(minutes)

# Visualizations-

Distribution of the Cuisines from the dataset
Variation of Rating based on Cuisine
Variation of the nutrional content based on the ratings(Divided into 4 quartiles)

# Analysis of the Recipe Dataset bases on a few hypothesis-

1. Hypothesis 1-Top 10 Keto recipes
2. Hypothesis 2-The highest contributing ingredients are Sugar,salt,purpose flour
3. Hypothesis 3-Top 50 least time consuming recipes

