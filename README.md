# My Personal Weight Loss Journey & Analysis

## Why I Started This Project

Over the last six months, I've gained about 15kg, and honestly, it's been frustrating. I'm determined to lose this weight, but I wanted to be smart about it. I figured that since so many people struggle with weight loss, I could turn my personal journey into something that might help others too.

Rather than jumping on some crazy diet trend, I decided to take a data-driven approach. By tracking what I eat, how much I exercise, and how my weight changes, I'm hoping to figure out what actually works for me. My gut feeling is that if I collect enough data, I'll discover a balanced approach that lets me lose weight without feeling like I'm constantly depriving myself.

Obesity is such a huge problem these days, and if what I learn helps even one other person, I'll consider this project a success. At the end of the day, I just want to get healthier and maybe help others do the same.

## What I'm Tracking

I'm keeping track of:
- Everything I eat and the calories (plus protein, fat, and carbs)
- How long I spend at the gym and roughly how many calories I burn
- My weight each morning
- How much weight I've lost (or gained) over time

I'm trying to be really consistent with logging all this info so I can trust the data when I analyze it later.

## How I'm Analyzing the Data

I'm using Python (pandas, matplotlib, and seaborn) to organize and visualize everything. Once I have enough data, I plan to:
1. Look for patterns in how my eating and exercise habits affect my weight
2. Run some basic statistical tests to see if certain approaches actually make a difference
3. Try to build a simple model that might predict my weight changes

## Questions I'm Trying to Answer

I've got a few specific things I'm curious about:

1. Does creating a bigger calorie deficit (eating at least 500 calories below what I burn) actually result in more weight loss?

2. Does eating lots of protein (more than 1.6g per kg of body weight) help me lose weight faster?

3. Do I lose more weight on days when I go to the gym compared to days when I don't?

4. Does eating fewer carbs (less than 40% of my total calories) speed up weight loss?

## What I've Found So Far

- Being in a calorie deficit consistently seems to be the most important factor
- Eating more protein definitely helps me feel fuller and seems to help with weight management
- Having the occasional treat doesn't seem to ruin my progress as long as I'm consistent overall
- Surprisingly, just going to the gym doesn't automatically translate to weight loss (though it has other benefits)

## My Machine Learning Approach

I'm trying to predict next week's weight change based on my habits. I'm looking at:
- Daily calories
- Protein, fat, and carb intake
- Time spent at the gym
- Averages over the past 3 and 7 days

I'm comparing a few different models:
1. Linear Regression (simple but might work)
2. Random Forest (better for capturing complex patterns)
3. Support Vector Regression (good for smaller datasets)

I'm splitting my data into training and testing sets to make sure the model works on new data.

## Limitations & Future Plans

The biggest limitation is obviously that this is just data from one person (me!), so what works for me might not work for everyone. Also, I might mess up on tracking sometimes, and I haven't been collecting data for very long yet.

In the future, I'd love to:
- Get more people involved to see patterns across different body types
- Use data from fitness trackers to get more accurate information
- Automate more of the data collection to make it easier to maintain

If this project helps me successfully lose weight and keep it off, I might turn it into something bigger that could help more people develop healthier lifestyles.
