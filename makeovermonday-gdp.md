
---
---

# MakeoverMonday - Global GDP Rankings Redesign

[Back to Home](./)

## Step 1: Original Visualization

**Original Visualization:** [Global GDP Ranks - Statistics of the World](https://statisticsoftheworld.com/gdp-by-country)

**Dataset:** MakeoverMonday 2026 Week 34 - Global GDP Ranks

**Data Source:** International Monetary Fund (IMF)

I chose this visualization because I am interested in the global economy and the GDP differences between countries. The original visualization shows the GDP rankings, values, and percentages of world GDP in a table.

I think this is an interesting topic because it allows viewers to understand which countries have the largest economies. However, I also wanted to see if a different chart type could make the GDP differences easier to compare.

## Step 2: Critique

I used Stephen Few's Data Visualization Effectiveness Profile to evaluate the original visualization.

I think the original table is useful because it clearly shows the GDP rankings and specific values of different countries. Viewers can quickly find the largest economies and their share of world GDP.

However, I think it is difficult to compare GDP differences directly because the visualization mainly shows numbers. Although the table is clear and easy to understand, it is not very visually engaging.

I think the primary audience is the general public and people interested in the global economy. The table is useful for finding specific information, but a chart could make the differences easier to understand.

This critique helped me decide to use a horizontal bar chart for my redesign.

## Step 3: Sketch a Solution

For my redesign, my initial idea was to use a horizontal bar chart instead of a table.

I wanted to show the countries in descending order by GDP so viewers could directly compare their economic sizes. I also planned to include GDP values next to each bar and use different colors to make the visualization more interesting.

My main goal was to improve clarity, readability, and comparison.

**Initial Sketch / Wireframe:**

<img width="2050" height="1128" alt="image" src="https://github.com/user-attachments/assets/6d5eb21a-b47f-4818-b5c1-6deea78e5140" />


## Step 4: Test the Solution

I prepared several questions to collect feedback on my proposed design:

1. What do you think this visualization is showing?
2. Is anything confusing or unclear?
3. Is it easy to compare the countries?
4. What would you change about this design?

### User Feedback

[Add the actual feedback you received from classmates here. Do not include their names or personal information.]

### Changes Based on Feedback

[Explain what you learned from the feedback and which changes you made to your final visualization.]

## Step 5: Final Redesign

### Top 12 Economies by GDP in 2026

For my final redesign, I used Tableau to create a horizontal bar chart showing the top 12 economies ranked by GDP.

I included the GDP values in trillion USD and the percentage of world GDP next to each bar. I also used different shades of blue to show the GDP rankings, with darker colors representing higher-ranked countries.

Compared with the original table, I think my redesign makes it easier to see the GDP differences between countries. For example, viewers can quickly notice the large difference between the United States, China, and other economies.

I wanted to keep the chart simple while making the information more visually appealing and easier to understand.

### Final Tableau Visualization

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Global GDP Rankings Redesign</title>

  <style>
    body {
      font-family: Arial, sans-serif;
      max-width: 1100px;
      margin: 40px auto;
      padding: 0 24px;
      line-height: 1.7;
      color: #222;
    }
    h1, h2 { margin-top: 32px; }
    a { color: #2468a0; }
  </style>

  <script type="module"
    src="https://public.tableau.com/javascripts/api/tableau.embedding.3.latest.min.js">
  </script>
</head>

<body>

<a href="./">Back to Home</a>

<h1>MakeoverMonday - Global GDP Rankings Redesign</h1>

<h2>Step 1: Original Visualization</h2>

<p>
Original Visualization:
<a href="https://statisticsoftheworld.com/gdp-by-country">
Global GDP Ranks - Statistics of the World
</a>
</p>

<p>
I chose this visualization because I am interested in the
global economy and the GDP differences between countries.
The original visualization shows the GDP rankings, values,
and percentages of world GDP in a table.
</p>

<p>
I think this is an interesting topic because it allows
viewers to understand which countries have the largest
economies. However, I wanted to see if a different chart
type could make the GDP differences easier to compare.
</p>

<h2>Step 2: Critique</h2>

<p>
I used Stephen Few's Data Visualization Effectiveness
Profile to evaluate the original visualization.
</p>

<p>
The original table clearly shows the GDP rankings and
specific values. However, it is difficult to compare
GDP differences directly because it mainly shows numbers.
I think a bar chart could make the comparison more clear
and visually engaging.
</p>

<h2>Step 3: Sketch a Solution</h2>

<p>
My initial idea was to use a horizontal bar chart
to show the GDP rankings. I wanted to arrange countries
from highest to lowest GDP and include the values next
to each bar.
</p>

<p>[Add your actual sketch image here]</p>

<h2>Step 4: User Feedback</h2>

<p>[Add the actual feedback from your classmates here]</p>

<p>[Explain what you changed based on their feedback]</p>

<h2>Step 5: Final Redesign</h2>

<p>
For my final redesign, I used Tableau to create a
horizontal bar chart showing the top 12 economies
ranked by GDP.
</p>

<p>
I included GDP values in trillion USD and the percentage
of world GDP next to each bar. Different shades of blue
show the rankings, with darker colors representing
higher-ranked countries.
</p>

<h3>Top 12 Economies by GDP in 2026</h3>

<tableau-viz
  src="https://public.tableau.com/views/GlobalGDPRankings2026-Redesign/Sheet1"
  width="100%"
  height="750px"
  toolbar="bottom">
</tableau-viz>

<p>
<a href="https://public.tableau.com/views/GlobalGDPRankings2026-Redesign/Sheet1">
View on Tableau Public
</a>
</p>

<h2>Reflection</h2>

<p>
Through this assignment, I learned that choosing
the right chart type can make a big difference
in how people understand data. The horizontal bar
chart makes GDP comparisons easier than the original table.
</p>

<h2>References</h2>

<p>
<a href="https://statisticsoftheworld.com/gdp-by-country">
Statistics of the World
</a>
</p>

<p>
<a href="https://makeovermonday.co.uk/data/">
MakeoverMonday
</a>
</p>

<p>Data Source: International Monetary Fund (IMF)</p>

<h2>AI Usage</h2>

<p>
I used ChatGPT to help understand the assignment,
discuss redesign ideas, learn Tableau operations,
and draft and edit my written explanations.
I created the visualization using Tableau.
</p>

</body>
</html>


[View My Final Tableau Visualization](https://public.tableau.com/views/GlobalGDPRankings2026-Redesign/Sheet1)

<script type="module" src="https://public.tableau.com/javascripts/api/tableau.embedding.3.latest.min.js"></script>

<tableau-viz src="https://public.tableau.com/views/GlobalGDPRankings2026-Redesign/Sheet1" width="100%" height="750px" toolbar="bottom"></tableau-viz>

## Reflection

Through this assignment, I learned that choosing the right chart type can make a big difference in how people understand data. The original table provides useful information, but the horizontal bar chart makes comparisons easier.

I also learned that adding labels, colors, and clear units can improve the readability of a visualization.

## References

- [Statistics of the World - GDP by Country](https://statisticsoftheworld.com/gdp-by-country)
- [MakeoverMonday Data](https://makeovermonday.co.uk/data/)
- [International Monetary Fund](https://www.imf.org/en/Data)
- Tableau Public

## AI Usage

I used ChatGPT to help understand the assignment instructions, discuss possible redesign ideas, learn Tableau operations, and draft and edit parts of my written explanations. I created the visualization in Tableau and reviewed the design choices myself.
