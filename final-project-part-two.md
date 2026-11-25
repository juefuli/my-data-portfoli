
| [home page](https://juefuli.github.io/my-data-portfoli/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Is Paying More for College Really Worth It?

**Final Project — Part II**

*Comparing Tuition, Net Price, and Graduate Earnings*

![College Project Cover](graph1.png)

> **Does paying more for college actually mean earning more after graduation?**

Choosing a university is a big financial decision for students and their families. Tuition is often the first number people look at, but it does not tell the whole story. A university can have higher tuition without necessarily having higher earnings outcomes for its graduates.

For this project, I used College Scorecard data from the U.S. Department of Education to compare college costs and graduate earnings. In Part I, I focused on tuition and earnings. After receiving feedback, I added average net price to look at the cost of attending college from another angle.

My goal is to help students think about what makes a college worth its cost, rather than just comparing prices or assuming that an expensive university must be better.

## Project at a Glance

| | |
|---|---|
| **Research Question** | Is paying more for college associated with higher graduate earnings? |
| **Target Audience** | Prospective college students and their families |
| **Data Source** | U.S. Department of Education — College Scorecard |
| **Current Sample** | 30 selected public four-year universities |
| **Tools** | Tableau Public and GitHub Pages |
| **Part II Focus** | Draft visualizations, story structure, and user feedback |

---

# 1. Wireframes / Storyboards

## How the Story Works

I organized my story around three main questions. First, I compare tuition with graduate earnings. Second, I introduce net price, which considers more of the costs of attending college and financial aid. Finally, I compare different universities to see how their earnings outcomes differ.

| Step | Story Section | Main Question |
|---|---|---|
| 01 | Tuition vs. Earnings | Do more expensive universities have higher earnings? |
| 02 | Looking Beyond Tuition | Does the relationship change when using net price? |
| 03 | University Comparison | How different are earnings across tuition groups? |
| 04 | Conclusion | What should students consider when choosing a university? |

These three visualizations are my current draft for the final project. I plan to use them in the same order in my final interactive story.

---

## 01 — Tuition vs. Graduate Earnings

### Does Higher Tuition Mean Higher Graduate Earnings?

I started with a scatter plot comparing in-state tuition and median earnings four years after completion. Each dot represents one university.

I also added a trend line to show the overall relationship between tuition and earnings. However, the points are quite spread out, so the line may not fully explain the differences between universities.

<iframe
  src="https://public.tableau.com/views/CollegeTuitionvsGraduateEarnings/Sheet1?:showVizHome=no&amp;:embed=yes"
  width="100%"
  height="700"
  style="border: none;"
  loading="lazy"
  title="Tuition vs Graduate Earnings">
</iframe>

[Open Interactive Chart 1 in Tableau Public](https://public.tableau.com/views/CollegeTuitionvsGraduateEarnings/Sheet1)

**How to Read This Chart**

- X-axis: In-State Tuition (USD)
- Y-axis: Median Earnings Four Years After Completion (USD)
- Each dot represents one university.
- The trend line shows the overall direction of the relationship.

The purpose of this chart is to explore whether universities with higher tuition also tend to have higher graduate earnings.

---

## 02 — Looking Beyond Tuition

### Does a Higher Net Price Mean Higher Graduate Earnings?

Tuition is not the only cost students need to consider. Students also need to pay for housing, food, books, and other expenses.

Average net price considers the broader cost of attending college after grants and scholarships. I decided to include it because tuition alone does not show the full financial burden students may face.

In this visualization, I compare average net price with median earnings to see whether the relationship looks different from the first chart.

<iframe
  src="https://public.tableau.com/views/CollegeTuitionvsGraduateEarnings/Sheet12?:showVizHome=no&amp;:embed=yes"
  width="100%"
  height="700"
  style="border: none;"
  loading="lazy"
  title="Net Price vs Graduate Earnings">
</iframe>

[Open Interactive Chart 2 in Tableau Public](https://public.tableau.com/views/CollegeTuitionvsGraduateEarnings/Sheet12)

**How to Read This Chart**

- X-axis: Average Net Price (USD)
- Y-axis: Median Earnings Four Years After Completion (USD)
- Each dot represents one university.
- The trend line shows the overall relationship.

I want readers to understand that a university's tuition price and its average net price are not the same. Financial aid and other costs can make a difference when students compare schools.

The net price in this dataset is an average for an eligible group of students, so it does not represent the exact amount every student will pay.

---

## 03 — Comparing Different Universities

### Graduate Earnings Across Universities by Tuition Band

For the third visualization, I created a horizontal bar chart showing graduate earnings across 30 selected public universities.

The universities are sorted by earnings, from highest to lowest. I also used colors to highlight the highest tuition group and compare it with other universities.

<iframe
  src="https://public.tableau.com/views/CollegeTuitionvsGraduateEarnings/Sheet2?:showVizHome=no&amp;:embed=yes"
  width="100%"
  height="1050"
  style="border: none;"
  loading="lazy"
  title="Graduate Earnings by Tuition Band">
</iframe>

[Open Interactive Chart 3 in Tableau Public](https://public.tableau.com/views/CollegeTuitionvsGraduateEarnings/Sheet2)

**How to Read This Chart**

- Each bar represents one university.
- Bar length represents median earnings.
- Blue highlights the highest tuition group.
- Gray represents the other tuition groups.

This chart helps readers compare different universities more directly.

However, after receiving feedback, I realized that using only two colors also makes it difficult to see differences among the other tuition groups. I plan to improve this in Part III.

---

## 04 — What Should Students Consider?

The main purpose of my project is not to tell students which university they should choose. Instead, I want to show that tuition alone may not be enough to evaluate the financial value of a college.

Students should also consider average net price, potential earnings, financial aid, academic major, and location.

My main question is whether paying more for college is actually associated with better financial outcomes. I hope the visualizations can help readers think about this question from different perspectives.

### Data Limitations

There are also some limitations in my current analysis.

First, I used 30 selected public universities. These universities were chosen to cover different tuition levels and states, but they were not randomly selected. Therefore, this sample cannot represent all universities in the United States.

Second, the earnings data only cover an eligible group of graduates, not every graduate.

Finally, the charts show relationships between college costs and earnings, but they cannot prove that higher tuition causes higher earnings.

I plan to improve the data selection and check unusual values in Part III.

---

# 2. User Research

## Target Audience

The target audience for my project is prospective college students and their families. These are the people who need to compare different universities and consider the costs of higher education.

For my user research, I shared my three Tableau visualizations with classmates who have experience choosing a university or thinking about college costs.

I wanted to understand whether they could easily understand my charts and whether my story was useful to them.

I also wanted to know which information they cared about most and what I should improve for Part III.

I will keep the interview findings anonymous and will not include personal information.

## Research Goals

My user research has three main goals:

1. Understand whether my visualizations are clear and easy to read.
2. Find out whether the three charts connect to one meaningful story.
3. Collect suggestions for improving my data and visualizations.

## Interview Script

**Interview Introduction**

I am working on a data visualization project about college tuition and graduate earnings.

I created three charts comparing tuition, net price, and graduate earnings across different universities.

I would like to show you these charts and ask a few questions about what you think. I will not include your name in my project.

**Interview Questions**

| Goal | Questions to Ask |
|---|---|
| Understand audience priorities | What factors do you think are most important when choosing a university? |
| Understand the main message | After looking at my charts, what do you think is the main message of my project? |
| Check visualization clarity | Which chart is the easiest to understand? Is there any chart that confuses you? |
| Understand cost concerns | Do you think tuition or net price is more useful when comparing universities? Why? |
| Identify missing information | What other information would you want to know before deciding whether a university is worth its cost? |
| Improve the design | Do you have any suggestions for improving my charts or the overall story? |

**Interview Process**

First, I introduced the purpose of my project and showed the three Tableau charts in order.

Then, I asked questions about the charts and collected feedback about the data, colors, and overall story.

Finally, I reviewed the comments to identify common problems and possible improvements.

---

## Interview Findings

### Main Feedback

After showing my visualizations to classmates, I received several comments about the data selection, trend lines, net price, and chart colors.

| Area | Feedback | What I Learned |
|---|---|---|
| University Selection | Some classmates thought the 30 universities were not very well-known and questioned how they were selected. | I need to explain my data selection process and consider a larger sample. |
| Trend Lines | The points in both scatter plots were quite spread out, so the trend lines did not seem to represent the data very well. | I should check how well the trend lines fit the data. |
| Net Price | Some classmates did not understand why I included net price when my original research question focused on tuition and earnings. | I need to better explain why net price is important. |
| Bar Chart Colors | Using only two colors made it difficult to see differences between tuition groups. | I need to improve the color design without making the chart too complicated. |

### Summary of Interview Findings

From the feedback, I realized that some problems were related to the data itself, not just the visual design.

**First, the university selection needs improvement.**

Some classmates questioned why I selected these 30 universities. Many of the schools were unfamiliar to them, and they were not sure whether the sample could represent universities in the United States.

I think this is an important issue because the selection of universities may affect the results.

**Second, the trend lines may be confusing.**

In the two scatter plots, the points are quite spread out. Some classmates felt that the straight lines did not represent the points very well.

This made me realize that I should check the strength of the relationships instead of only relying on the trend lines.

**Third, I need to explain net price more clearly.**

Some classmates asked why I added net price when the original topic was about tuition and graduate earnings.

I included net price because it represents a broader view of college costs, but I did not explain this clearly enough before showing the second chart.

**Finally, the colors in the bar chart need improvement.**

I originally used five colors for the tuition groups, but I thought it looked too complicated. I changed the design to two colors.

However, some classmates felt that this made most universities look the same, making it harder to compare the different tuition groups.

Overall, the feedback helped me understand that having more charts does not automatically make the story better. I need to make the data selection more reasonable and make sure readers understand the purpose of each visualization.

### Interview Participants

The feedback above summarizes comments I collected from classmates.

The following information should be completed using the actual participants' anonymous descriptions and feedback.

| Participant | Anonymous Description | Specific Feedback |
|---|---|---|
| Interview 1 | [Add actual description] | [Add this participant's actual feedback] |
| Interview 2 | [Add actual description] | [Add this participant's actual feedback] |
| Interview 3 | [Add actual description] | [Add this participant's actual feedback] |

---

# 3. Identified Changes for Part III

## Changes Already Made in Part II

Based on the feedback from Part I, I already made some changes to my project.

First, I added average net price because tuition alone does not fully represent the cost of attending college.

Second, I adjusted my story to focus more on how students can use financial information when comparing universities.

Third, I changed the colors of my bar chart from five colors to two colors because I wanted a simpler design.

However, the new feedback showed that there are still several things I need to improve.

## Planned Changes for Part III

| Research Synthesis | Anticipated Changes for Part III |
|---|---|
| The selection of 30 universities is unclear and may not be representative. | I will explain the selection process and consider using a larger or more systematic sample from College Scorecard. |
| The trend lines may not fit the scattered data very well. | I will check the strength of the relationships and consider removing the trend lines if they are misleading. |
| Some readers do not understand why net price is included. | I will add a short explanation of tuition and net price before the second visualization. |
| The two-color bar chart makes it difficult to compare tuition groups. | I will try different shades of the same color for Q1 to Q5. |
| The overall story needs a clearer purpose. | I will focus more on how students can use the information when making college decisions. |

For Part III, I want to make my story easier to understand and more useful to my audience.

I will focus on improving the data first, then the visualizations and explanations. I also want to make sure every chart connects clearly to my main research question.

---

# 4. References

1. U.S. Department of Education. (n.d.). *College Scorecard*. https://collegescorecard.ed.gov/data/

2. U.S. Department of Education. (n.d.). *College Scorecard Data Documentation*. https://collegescorecard.ed.gov/data/data-documentation/

3. Berinato, S. (2016). *Good Charts: The HBR Guide to Making Smarter, More Persuasive Data Visualizations*. Harvard Business Review Press.

---

# 5. AI Acknowledgements

I used ChatGPT to help me understand the Part II assignment requirements, discuss the feedback from Part I, and organize my story.

I also used ChatGPT to help me understand Tableau operations, discuss visualization ideas, prepare interview questions, create a cover image, and improve the grammar of my written explanations. ChatGPT also helped with the initial selection of university data.

I created the Tableau visualizations using College Scorecard data and reviewed the charts myself. The feedback I reported came from classmates, and I will use it to improve my project for Part III.
