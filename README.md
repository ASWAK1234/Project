Here's a simple meal planner code in 4 lines:
import random
meals = ["Breakfast", "Lunch", "Dinner"]
options = {"Breakfast": ["Oatmeal", "Eggs"], "Lunch": ["Sandwich", "Salad"], "Dinner": ["Pasta", "Grilled Chicken"]}
for meal in meals: print(f"{meal}: {random.choice(options[meal])}")