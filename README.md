# A. Executive Summary
After analyzing 150,000 snack products, the biggest market gap is High-Protein, Low-Sugar products. Protein and Energy Bars show the strongest opportunity with average 24.3g protein and under 8.2g sugar per 100g. Top protein sources are Whey, Peanuts, and Almonds.

# B. Project Links
   Notebook: https://github.com/rajeeakbar/The-Market-Gap-Analysis/blob/main/Market_Gap_Analysis.ipynb
   Dashboard: Looker Studio
   Presentation: Google Slides/PDF

# C. Technical Explanation
   # How data cleaning was handled
      Data was cleaned by dropping nulls in sugars_100g/proteins_100g and filtering outliers (0-100g range). Categories were created by keyword matching        on categories_tags. My Candidate's Choice added a Protein-to-Sugar Efficiency Ratio to identify the most nutritionally efficient categories

   # An Explanation of my Choice on the "Candidate Choice" addition
   --------------------------------------------------
   Top performers: Protein & Energy Bars (Ratio: 63.20)
   I added a Protein-to-Sugar Efficiency Ratio  to help show that most consumers want high protein WITHOUT high sugar.
   This identifies which categories deliver the best nutritional value.
