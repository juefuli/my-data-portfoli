
| [home page](https://juefuli.github.io/my-data-portfoli/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Is Paying More for College Really Worth It?

**Final Project — Part II**

*Comparing Tuition, Net Price, and Graduate Earnings*

![College Project Cover](graph1.png)

> **Does paying more for college actually mean earning more after graduation?**

When students choose a university, tuition is usually one of the first things they consider. However, does paying more for college really mean getting better financial outcomes after graduation?

This is a question I am interested in because college is a big financial decision for many students and families. A more expensive university may offer better resources and opportunities, but it does not necessarily mean its graduates will earn more money.

For this project, I used College Scorecard data from the U.S. Department of Education to compare college costs and graduate earnings. In Part I, I mainly focused on tuition and earnings. After receiving feedback, I decided to also include average net price because tuition alone does not show the full cost of attending college.

My goal is to help students and their families understand what they should consider when comparing universities, instead of just assuming that a higher tuition means a better financial return.

## Project at a Glance

| Category | Description |
|---|---|
| **Research Question** | Is paying more for college associated with higher graduate earnings? |
| **Target Audience** | Prospective college students and their families |
| **Data Source** | U.S. Department of Education — College Scorecard |
| **Current Sample** | 30 selected public four-year universities |
| **Tools** | Tableau Public and GitHub Pages |
| **Part II Focus** | Draft visualizations, story structure, and user feedback |

---

# 1. Wireframes / Storyboards

## Story Overview

In Part I, I mainly focused on the relationship between college tuition and graduate earnings. However, based on the feedback I received, I realized that simply comparing these two variables might not be enough to tell an interesting story.

For Part II, I decided to look at college costs from another perspective by adding average net price. I also started thinking more about how students can use this information when choosing a university.

I created three visualizations using Tableau Public. The story will first compare tuition and graduate earnings, then introduce net price, and finally compare different universities.

## Story Structure

| Step | Section | Main Question |
|---|---|---|
| 1 | Introduction | Why should students care about college costs? |
| 2 | Tuition vs. Graduate Earnings | Do more expensive universities have higher earnings? |
| 3 | Net Price vs. Graduate Earnings | Does the relationship change when using net price? |
| 4 | University Comparison | How do earnings differ across tuition groups? |
| 5 | Conclusion | What should students consider when choosing a university? |

The following three Tableau charts are the current draft visualizations for my project.

---

## 01 — Tuition vs. Graduate Earnings

### Does Higher Tuition Mean Higher Graduate Earnings?

For my first visualization, I created a scatter plot comparing in-state tuition with median earnings four years after completion.

Each dot represents one university. I also added a trend line to show the overall relationship between tuition and earnings.

I want readers to see whether universities with higher tuition also tend to have higher graduate earnings. I also want to highlight some universities that have relatively low tuition but good earnings outcomes.

<iframe src="https://public.tableau.com/views/CollegeTuitionvsGraduateEarnings/Sheet1?:showVizHome=no&amp;:embed=yes" width="100%" height="700" style="border: none;" loading="lazy" title="Tuition vs Graduate Earnings"></iframe>

[Open Interactive Chart 1 in Tableau Public](https://public.tableau.com/views/CollegeTuitionvsGraduateEarnings/Sheet1)

**How to Read This Chart**

- X-axis: In-State Tuition (USD)
- Y-axis: Median Earnings Four Years After Completion (USD)
- Each dot represents one university.
- The trend line shows the overall direction of the relationship.

One thing I noticed is that most of the points are quite spread out, and some universities have much higher earnings than others. This means I need to be careful when interpreting the trend line.

---

## 02 — Looking Beyond Tuition

### Does a Higher Net Price Mean Higher Graduate Earnings?

Tuition is not the only cost students need to consider when choosing a university.

Students also need to think about housing, food, books, and other expenses. Average net price considers the broader cost of attendance after grants and scholarships.

I decided to include net price because I wanted to see whether using a different cost measure would change the relationship with graduate earnings.

<iframe src="https://public.tableau.com/views/CollegeTuitionvsGraduateEarnings/Sheet12?:showVizHome=no&amp;:embed=yes" width="100%" height="700" style="border: none;" loading="lazy" title="Net Price vs Graduate Earnings"></iframe>

[Open Interactive Chart 2 in Tableau Public](https://public.tableau.com/views/CollegeTuitionvsGraduateEarnings/Sheet12)

**How to Read This Chart**

- X-axis: Average Net Price (USD)
- Y-axis: Median Earnings Four Years After Completion (USD)
- Each dot represents one university.
- The trend line shows the overall relationship.

This visualization helps readers understand why tuition and net price are not the same thing.

However, net price in the College Scorecard dataset is an average for a specific group of students, so it does not represent exactly what every student will pay.

---

## 03 — University Comparison

### Graduate Earnings Across Universities by Tuition Band

For my third visualization, I created a horizontal bar chart showing graduate earnings across 30 selected public universities.

The universities are sorted from the highest to the lowest earnings.

I originally divided the universities into five tuition groups, from Q1 to Q5. Later, I changed the colors to highlight the highest tuition group because I wanted a simpler design.

<iframe src="https://public.tableau.com/views/CollegeTuitionvsGraduateEarnings/Sheet2?:showVizHome=no&amp;:embed=yes" width="100%" height="1050" style="border: none;" loading="lazy" title="Graduate Earnings by Tuition Band"></iframe>

[Open Interactive Chart 3 in Tableau Public](https://public.tableau.com/views/CollegeTuitionvsGraduateEarnings/Sheet2)

**How to Read This Chart**

- Each bar represents one university.
- Bar length represents median graduate earnings.
- Blue highlights the highest tuition group.
- Gray represents the other universities.

The tuition groups were created using the 30 selected universities, so they do not represent national tuition rankings.

This chart helps readers compare universities more directly. However, I received feedback that using only two colors makes it difficult to see differences between the other tuition groups.

I plan to improve this in Part III.

---

## 04 — Conclusion and Main Takeaway

The main purpose of this project is not to tell students which university they should choose. Instead, I want to show that tuition alone may not be enough to evaluate the financial value of a college.

Students should also consider average net price, graduate earnings, financial aid, academic major, and location.

My main research question is whether paying more for college is associated with better financial outcomes. I hope these visualizations can help readers think about this question from different perspectives.

### Current Data Limitations

There are several limitations in my current analysis.

First, I used 30 selected public universities. These universities were chosen to cover different tuition levels and states, but they were not randomly selected. Therefore, this sample cannot represent all universities in the United States.

Second, the earnings data only represent a specific group of eligible graduates, not every graduate.

Third, the relationships shown in my visualizations do not prove that higher tuition causes higher earnings.

Finally, I still need to check some unusual data values and consider using a larger sample in Part III.

---

# 2. User Research

## Target Audience

The target audience for my project is prospective college students and their families. These are the people who need to compare different universities and consider the costs of higher education.

For my user research, I discussed my project with three classmates from Part II Critique Group 8.

I wanted to understand whether my charts were easy to read, whether the overall story was clear, and what other information students would want to see.

The three classmates reviewed my current Tableau visualizations and provided feedback about the data selection, trend lines, net price, chart colors, and possible additional visualizations.

I will use anonymous participant descriptions in this project to protect their privacy.

## Research Participants

My critique group included three other students. For this report, I refer to them as Participant A, Participant B, and Participant C.

| Participant | Description |
|---|---|
| Participant A | Classmate from Part II Critique Group 8 |
| Participant B | Classmate from Part II Critique Group 8 |
| Participant C | Classmate from Part II Critique Group 8 |

The feedback below is summarized by topic because I did not record the exact person who made each individual comment.

---

## Research Goals

My user research has three main goals:

1. Understand whether my visualizations are clear and easy to understand.
2. Find out whether the three charts connect to one meaningful story.
3. Collect suggestions for improving the data, charts, and overall project.

## Interview Script

**Interview Introduction**

I am working on a data visualization project about college tuition and graduate earnings.

I created three charts comparing tuition, net price, and earnings across different universities.

I would like to show you these charts and ask a few questions about what you think. Your feedback will only be used for my class project, and I will not include your name.

**Interview Questions**

| Goal | Questions to Ask |
|---|---|
| Understand audience priorities | What factors do you think are most important when choosing a university? |
| Understand the main message | After looking at my charts, what do you think is the main message of my project? |
| Check visualization clarity | Which chart is the easiest to understand? Is there any chart that confuses you? |
| Understand cost concerns | Do you think tuition or net price is more useful when comparing universities? Why? |
| Identify missing information | What other information would you want to know before deciding whether a university is worth its cost? |
| Improve the design | Do you have any suggestions for improving my charts or the overall story? |

**Research Process**

First, I introduced the main idea of my project and showed my three Tableau visualizations.

Then, I discussed the charts with my classmates and collected their comments about the data and design.

After that, I reviewed the feedback and identified several problems that I should address in Part III.

---

## Interview Findings

### Main Feedback

After showing my visualizations to my classmates, I received feedback about five main areas.

| Area | Feedback | What I Learned |
|---|---|---|
| University Selection | Some classmates questioned why I selected these 30 universities. Many of the schools were unfamiliar to them. | I need to explain the sample selection and consider using more universities. |
| Trend Lines | Some classmates thought the straight lines in my scatter plots did not represent the scattered points very well. | I need to check how well the trend lines fit the data. |
| Net Price | Some classmates did not understand why I introduced net price when my original topic focused on tuition and earnings. | I need to explain why net price is useful for understanding college costs. |
| Bar Chart Colors | Some classmates thought the two-color design made it difficult to see differences among the tuition groups. | I need to improve the color design. |
| Historical Trends | Some classmates suggested adding historical college cost data or comparing tuition growth with wage growth. | Adding a historical chart could provide more background and make the story more interesting. |

### 1. University Selection

One of the main concerns was about the 30 universities I selected.

Some classmates thought many of the universities were not very well-known. They also questioned whether the sample could represent universities in the United States.

This made me realize that I need to explain how I selected the universities and why I used this sample.

I also think using a larger sample could make the analysis more useful.

### 2. Trend Lines in the Scatter Plots

Some classmates thought the trend lines in my first two charts did not represent the data very well.

The points were quite spread out, but the straight lines made it look like there was a clearer relationship between costs and earnings.

I realized that I need to check the strength of the relationships instead of only relying on the trend lines.

For Part III, I plan to check the trend line results and consider removing them if they are misleading.

### 3. Why I Included Net Price

Another concern was about the second scatter plot.

Some classmates asked why I added average net price when the original research question focused on tuition and graduate earnings.

I included net price because I wanted to consider other college costs and financial aid, but I did not explain this clearly enough.

For Part III, I plan to add a short explanation before the second chart to show why tuition and net price are different.

### 4. Bar Chart Colors

Some classmates also commented on the colors of my third visualization.

Originally, I used five different colors for tuition groups. Later, I changed them into two colors because I thought the original chart looked too complicated.

However, the feedback showed that using only two colors made most universities look the same.

I think a better solution may be to use different shades of the same color for the five tuition groups. This could make the differences easier to see without making the chart too colorful.

### 5. Suggestions for Additional Historical Visualizations

Some classmates also suggested adding another visualization to show how college costs have changed over time.

They showed me two examples.

The first example was a bar chart comparing average college costs across different years.

The second example was a line chart comparing university tuition growth with wage growth over time.

They thought these types of charts could make my introduction more interesting and help readers understand the background of rising college costs.

I think this is a useful suggestion because my current visualizations only compare universities at one point in time.

For Part III, I plan to explore historical tuition data and consider adding a simple line chart or bar chart showing how college costs have changed over time.

I will also look into whether comparable wage data is available, although wage growth and graduate earnings are not exactly the same thing.

---

## Summary of User Research

After reviewing the feedback, I realized that there are some problems with both my data and the way I present the story.

The first problem is data selection. I need to make sure the universities I include are appropriate for my research question.

The second problem is chart design. The trend lines and colors may not always help readers understand the data.

The third problem is story structure. I need to explain why I included net price and why each visualization matters.

Finally, some classmates suggested using historical data to provide more background about college costs.

Overall, this feedback helped me understand that having more charts does not automatically make a better data story. I need to make sure that the data is appropriate and the visualizations connect clearly to my main question.

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
| The trend lines may not fit the scattered data very well. | I will check the relationship strength and consider removing the trend lines if they are misleading. |
| Some readers do not understand why net price is included. | I will add a short explanation of tuition and net price before the second visualization. |
| The two-color bar chart makes it difficult to compare tuition groups. | I will try different shades of the same color for Q1 to Q5. |
| Some classmates suggested adding historical college cost data. | I will look for historical tuition data and consider adding a line chart or bar chart showing changes over time. |
| Some classmates suggested comparing tuition growth with wage growth. | I will explore whether suitable wage data is available and decide whether this comparison fits my main story. |
| The overall story needs a clearer purpose. | I will focus more on helping students understand what information they should consider when choosing a university. |

For Part III, I want to make my story easier to understand and more useful to my target audience.

I will focus on improving the data selection first, then the visualizations and explanations.

I also want to make sure that each chart has a clear purpose and connects to my main research question.

---

# 4. References

1. U.S. Department of Education. (n.d.). *College Scorecard*. https://collegescorecard.ed.gov/data/

2. U.S. Department of Education. (n.d.). *College Scorecard Data Documentation*. https://collegescorecard.ed.gov/data/data-documentation/

3. Berinato, S. (2016). *Good Charts: The HBR Guide to Making Smarter, More Persuasive Data Visualizations*. Harvard Business Review Press.

---

# 5. AI Acknowledgements

I used ChatGPT to help me understand the Part II assignment requirements, discuss feedback from Part I, and organize my story.

I also used ChatGPT to help me understand Tableau operations, discuss visualization ideas, prepare interview questions, create a cover image, and improve the grammar of my written explanations. ChatGPT also helped with the initial selection of university data and organizing the feedback from my classmates.

I created the Tableau visualizations using College Scorecard data and reviewed the charts myself. The feedback reported in this project came from my classmates, and I plan to use it to improve my project for Part III.
