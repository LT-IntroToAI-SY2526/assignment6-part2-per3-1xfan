# Assignment 6 Part 2 - Writeup

---

## Question 1: Feature Importance

Based on your house price model, rank the four features from most important to least important. Explain how you determined this ranking.

**YOUR ANSWER:**
1. SquareFeet
2. Bedrooms
3. Bathrooms
4. Age

**Explanation:**
Based on our data, square feet seems to have the largest impact on the house price compared to the other variables, as well as the most linear correlation to the price. Although Bedrooms and bathrooms are similar in their impact on the final price, they still individually have less of an impact than the size of the house. 



---

## Question 2: Interpreting Coefficients

Choose TWO features from your model and explain what their coefficients mean in plain English. For example: "Each additional bedroom increases the price by $___"

**Feature 1:**


**Feature 2:**


---

## Question 3: Model Performance

What was your model's R² score? What does this tell you about how well your model predicts house prices? Is there room for improvement?

**YOUR ANSWER:**




---

## Question 4: Adding Features

If you could add TWO more features to improve your house price predictions, what would they be and why?

**Feature 1:**
Backyard Size

**Why it would help:**
Many inviduals may be looking for houses with backyard space, whether its for their kids, their pets, or their personal hobbies. Knowing this, sellers will likely mark up the house price based on how much extra space the backyard provides.

**Feature 2:**
External Storage Space (sq. ft)

**Why it would help:**
This statistic would count the surface area of any sheds, garages, or any other areas for storage detached from the main house. Especially for living in the city, a home having a garage could be a deal maker, and knowing this, sellers will likely price a house more highly if it has one, and even more highly if it can fit several cars. Sheds are also useful to stuff less frequently used things and could also be valuable to purchasers.

---

## Question 5: Model Trust

Would you trust this model to predict the price of a house with 6 bedrooms, 4 bathrooms, 3000 sq ft, and 5 years old? Why or why not? (Hint: Think about the range of your training data)

**YOUR ANSWER:**
I would not trust this model to predict the price of a house with those specifications because our data does not feature any houses with more than 5 bedrooms or more than 3 bathrooms or more than 2.5k sq ft. Therefore, the model will likely be inaccurate to houses outside the range of the training data, meaning it would have to do a lot of guessing, leading to unreliable predictions.

