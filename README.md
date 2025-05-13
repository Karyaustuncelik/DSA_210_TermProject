My Personal Weight Loss Journey 

Why I Decided to Do This

Over the past few months, I noticed I had gained around 15 kilograms, and honestly, it started to affect how I felt both physically and mentally. Rather than jumping into a random diet or blindly cutting calories, I wanted to actually understand what works for me — not just what works in general.

I also thought: “If I’m going through this, maybe others are too.” That’s when I decided to turn this into a small data science project. By tracking my daily habits and weight changes, I figured I could not only help myself but maybe even someone else who's struggling with the same thing.

What I've Been Tracking

To keep everything measurable, I’ve been logging:
- My daily calorie intake, including protein, carbs, and fat
- How much time I spend exercising (mainly gym and walking)
- My weight every morning
- And recently, also things like sleep hours, water intake, step count, and total minutes of movement or activity

The more consistent I am with tracking, the more accurate the insights I can get — so I try not to skip days.

How I Looked Into the Data

Using Python and tools like `pandas`, `matplotlib`, and `seaborn`, I explored the patterns in my daily habits. I didn’t want to just guess what worked — I wanted to visualize it.

Here’s what I included in my analysis:
- Basic descriptive statistics
- Correlation heatmaps to see what variables are connected
- Pairplots to spot trends
- Line charts to track weight change over time
- Boxplots and histograms to understand the spread of my nutrition and activity data

Questions I Wanted to Answer

There were a few things I was especially curious about:

1. Does eating at a 500+ calorie deficit really lead to faster weight loss?
2. Is eating high amounts of protein (1.6g/kg or more) actually helpful?
3. Does going to the gym regularly actually show up in the scale numbers?
4. What happens when I reduce carbs — does it affect my progress?

What I Found Out So Far

- Being in a consistent calorie deficit seems to matter the most.
- Protein does help — I feel fuller, and my weight seems more stable when I focus on it.
- Gym workouts are great for my mood and energy, but they don’t always lead to instant weight loss (which is totally fine).
- I can still enjoy food I love occasionally — the key is being consistent overall.

Machine Learning: Can I Predict My Weight?

Just for fun (and curiosity), I wanted to see if I could predict tomorrow’s weight based on today’s habits.

So I built a simple Linear Regression model that uses:
- Daily calories, protein, fat, and carbs
- How much I slept
- Water I drank
- Step count and exercise time

The model gives me an idea of how much today’s choices could influence the scale the next day. I evaluated it using metrics like Mean Squared Error and R² Score, just to see how well it works (spoiler: it’s not perfect, but it’s interesting!).

What I Still Want to Work On

There are a few limitations to this project:
- It’s just based on me — one person, one set of habits
- Sometimes I forget to log things or estimate meals
- The dataset isn’t huge, so more advanced models won’t work well yet

That said, I’d love to:
- Add more people’s data one day 
- Use a fitness tracker to automate some of the data collection
- Keep doing this long-term to see trends over time



Final Thoughts

This started out as a way to understand my own habits but now it feels like a personal experiment in building healthy routines through data. If it ends up helping someone else too, then even better.
