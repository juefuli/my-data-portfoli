| [home page](https://juefuli.github.io/my-data-portfoli/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Wireframes / storyboards


# Is the Rising Cost of College Worth It?

![College Project Cover](graph1.png)

**Looking Beyond Tuition to Understand the Financial Value of Higher Education**

## Introduction

When students choose a university, tuition is usually one of the first things they consider. But does paying more for college really mean getting a better financial return after graduation?

This is a question I am interested in because college is a big financial decision for many students and families. A more expensive university may offer better resources and opportunities, but this does not always mean its graduates will earn more money.

For this project, I used College Scorecard data from the U.S. Department of Education to explore the relationship between college costs and graduate earnings. I started with 30 selected public universities to compare their tuition and earnings. After receiving feedback from Part I, I also decided to include average net price, since tuition alone does not show the full cost of attending college.

My goal is to help students understand what they should consider when comparing universities, rather than simply assuming that a higher tuition means a better education or higher future earnings.

## Project at a Glance

| | |
|---|---|
| **Main Question** | Does paying more for college mean earning more after graduation? |
| **Target Audience** | Prospective college students and their families |
| **Data Source** | U.S. Department of Education — College Scorecard |
| **Current Sample** | 30 selected public universities (exploratory sample) |
| **Main Tools** | Tableau Public and GitHub Pages |

## How the Story Will Develop

**1. Tuition vs. Graduate Earnings**

First, I will compare tuition and graduate earnings to see whether more expensive universities tend to have higher earnings outcomes.

**2. Looking Beyond Tuition**

Next, I will introduce average net price and explain why financial aid and other college costs are important when comparing universities.

**3. Comparing Different Universities**

Finally, I will compare graduate earnings across universities with different tuition levels and discuss what these differences might mean for students.

---

# Wireframes / storyboards


**Story Overview**

My project is about the relationship between college tuition and graduate earnings in the United States. In Part I, I mainly focused on whether universities with higher tuition have higher graduate earnings. However, based on the feedback I received, I realized that just comparing tuition and earnings might not be enough to tell an interesting story.

For Part II, I decided to also include average net price, since tuition is not the only cost students need to consider. I want to explore whether paying more for college really means getting better financial outcomes. My target audience is students and families who are trying to choose a university.

I created three visualizations using Tableau Public and the College Scorecard dataset. The story will start with the relationship between tuition and earnings, then introduce net price, and finally compare different universities to help readers understand the differences.

## Story Structure

**Section 1: Introduction**

I will first introduce the background of college education costs in the United States. Many students and families need to think about how much they will spend on college and whether it is worth the cost.

The main question of my story is: Does paying more for college mean earning more after graduation?

**Section 2: Tuition vs. Graduate Earnings**

For the first visualization, I created a scatter plot to compare in-state tuition with median earnings four years after completion.

Each dot represents one university, and the trend line shows the overall relationship between tuition and earnings.

I want the audience to see whether universities with higher tuition also tend to have higher graduate earnings. I will also highlight some universities that have relatively low tuition but good earnings outcomes.

**Visualization 1: Tuition vs. Graduate Earnings**

<iframe
  src="https://public.tableau.com/views/CollegeTuitionvsGraduateEarnings/Sheet1?:showVizHome=no&amp;:embed=yes"
  width="100%"
  height="700"
  style="border: none;"
  loading="lazy"
  title="Tuition vs Graduate Earnings">
</iframe>

[Open interactive chart](https://public.tableau.com/views/CollegeTuitionvsGraduateEarnings/Sheet1)

**Section 3: Net Price vs. Graduate Earnings**

In the second visualization, I decided to use average net price instead of tuition. Net price includes more costs related to attending college and considers grants and scholarships.

I created another scatter plot to compare net price with median earnings. I want to see whether the relationship changes when I use net price instead of tuition.

This part is important because students should not only consider the tuition shown by universities. Financial aid and other costs can also affect how much they need to pay.

**Visualization 2: Net Price vs. Graduate Earnings**
<iframe
  src="https://public.tableau.com/views/CollegeTuitionvsGraduateEarnings/Sheet12?:showVizHome=no&amp;:embed=yes"
  width="100%"
  height="700"
  style="border: none;"
  loading="lazy"
  title="Net Price vs Graduate Earnings">
</iframe>

[Open interactive chart](https://public.tableau.com/views/CollegeTuitionvsGraduateEarnings/Sheet12)

**Section 4: University Comparison**

For the third visualization, I created a bar chart showing median graduate earnings across 30 selected public universities.

The universities are sorted by graduate earnings. I also used colors to highlight the highest tuition group and compare it with other universities.

This chart will help the audience compare different schools and see whether more expensive universities always have better earnings outcomes.

**Visualization 3: Graduate Earnings by Tuition Band**

<iframe
  src="https://public.tableau.com/views/CollegeTuitionvsGraduateEarnings/Sheet2?:showVizHome=no&amp;:embed=yes"
  width="100%"
  height="1050"
  style="border: none;"
  loading="lazy"
  title="Graduate Earnings by Tuition Band">
</iframe>

[Open interactive chart](https://public.tableau.com/views/CollegeTuitionvsGraduateEarnings/Sheet2)

**Section 5: Conclusion**

At the end of the story, I want to summarize the main findings from these three visualizations.

My goal is not to tell students which university they must choose. Instead, I want to show that tuition alone may not be enough to evaluate a university.

Students should also consider net price, graduate earnings, financial aid, and other factors when making college decisions.

## Current Progress

So far, I have completed three draft visualizations in Tableau Public:

1. Tuition vs. Graduate Earnings (Scatter Plot)
2. Net Price vs. Graduate Earnings (Scatter Plot)
3. Graduate Earnings by Tuition Band (Bar Chart)

I plan to improve the visualizations and story based on the feedback from user interviews.

One limitation is that my current data only includes 30 selected public universities. Also, the earnings data do not represent every graduate, and the relationships shown in the charts do not prove that tuition causes higher earnings.


# User research

## Target audience

The target audience for my project is prospective college students and their families. They are the people who need to compare different universities and consider the costs of higher education.

For my interviews, I plan to talk to at least three people who have experience choosing a university or thinking about education costs.

I will try to interview students with different educational backgrounds, such as undergraduate students and graduate students. I think they may have different opinions about whether college costs are worth it.

I will show them my three Tableau visualizations and ask questions about their understanding and opinions.

I will not include their real names or other personal information in my project.


## Interview script

**Research Goals**

The main goal of my user research is to understand whether my visualizations are easy to understand and whether the story is useful to my target audience.

I also want to know which information students care about most when choosing a university and what I should improve for Part III.

**Interview Introduction**

I am working on a data visualization project about college tuition and graduate earnings.

I have created three charts comparing tuition, net price, and graduate earnings across different universities.

I would like to show you these charts and ask a few questions about what you think. Your answers will only be used for my class project, and I will not include your name.

**Interview Questions**

| Goal | Questions to Ask |
|------|------------------|
| Understand audience priorities | What factors do you think are most important when choosing a university? |
| Understand the main message | After looking at my charts, what do you think is the main message of my project? |
| Check visualization clarity | Which chart is the easiest to understand? Is there any chart that confuses you? |
| Understand cost concerns | Do you think tuition or net price is more useful when comparing universities? Why? |
| Find missing information | What other information would you want to know before deciding whether a university is worth its cost? |
| Improve the design | Do you have any suggestions for improving my charts or the overall story? |

**Interview Process**

First, I will briefly explain the purpose of my project. Then, I will show the three Tableau charts in the planned story order.

After that, I will ask the questions above and record the main points from each participant.

Finally, I will compare their feedback to identify common suggestions and differences in their opinions.


## Interview findings

I showed my three Tableau visualizations to my classmates and collected feedback about the data, charts, and overall story.

### Interview Results

| Questions | Interview 1 | Interview 2 | Interview 3 |
|-----------|-------------|-------------|-------------|
| Main Concern | University selection | Scatter plots and net price | Bar chart colors |
| Feedback | The 30 universities seem unfamiliar, and it is unclear how they were selected. The sample may not represent universities in the United States very well. | The trend lines do not seem to fit the scattered points very well. Also, the purpose of adding net price is not clear when the main topic is tuition and earnings. | Using only two colors makes it difficult to see differences between tuition groups. Most universities look the same. |
| Suggested Improvement | Explain how the universities were selected and consider using a larger or more representative sample. | Check the trend lines and explain why net price is included in the analysis. | Use more distinguishable colors to show the differences between tuition groups. |

### Summary of Interview Findings

From the feedback, I noticed several problems with my current visualizations.

First, the selection of universities may affect how readers understand the results. I need to explain why I chose these 30 universities and whether they can represent a larger group of universities.

Second, the scatter plots need some improvements. The points are quite spread out, so the trend lines may not clearly show the relationship between costs and earnings. I also need to better explain why I included net price in my project.

Finally, the bar chart needs a clearer color design. Although I changed the original five colors into two colors to make the chart simpler, this made it harder to compare different tuition groups.

Overall, the feedback helped me realize that I should focus more on data selection, chart clarity, and explaining the purpose of each visualization.

**Interview Participants**

- Interview 1: [Brief anonymous description]
- Interview 2: [Brief anonymous description]
- Interview 3: [Brief anonymous description]

**Interview Results**

| Questions | Interview 1 | Interview 2 | Interview 3 |
|-----------|-------------|-------------|-------------|
| Q1. Important factors when choosing a university | To be completed | To be completed | To be completed |
| Q2. Main message of the project | To be completed | To be completed | To be completed |
| Q3. Easiest and most confusing charts | To be completed | To be completed | To be completed |
| Q4. Tuition vs. net price | To be completed | To be completed | To be completed |
| Q5. Other information needed | To be completed | To be completed | To be completed |
| Q6. Suggestions for improvement | To be completed | To be completed | To be completed |

**Summary of Interview Findings**

[After completing the interviews, summarize the common feedback, different opinions, and important comments from the three participants here.]


# Identified changes for Part III

Based on the feedback from Part I and my user research, I plan to make several improvements in Part III.

| Research Synthesis | Anticipated Changes for Part III |
|--------------------|----------------------------------|
| Some classmates questioned why I selected these 30 universities and felt that many schools were unfamiliar. | I will explain my university selection process and consider using a larger or more representative sample. |
| The trend lines in the scatter plots do not seem to fit the data points very well. | I will check how well the trend lines fit the data and consider removing them if they are misleading. |
| The reason for including average net price was not clear. | I will add a short explanation of the difference between tuition and net price before the second visualization. |
| The two-color design makes it difficult to compare different tuition groups. | I will try using different shades of the same color for Q1 to Q5, so readers can see the differences more clearly. |

For Part III, I want to make my story easier to understand. I will focus on improving the data selection and making each chart more useful to the audience. I also want to make sure that every visualization connects to my main research question.
**Planned Changes Based on User Research**

| Research Synthesis | Anticipated Changes for Part III |
|--------------------|----------------------------------|
| [Finding from interviews] | [Change based on feedback] |
| [Finding from interviews] | [Change based on feedback] |
| [Finding from interviews] | [Change based on feedback] |

After the interviews, I will use the feedback to decide what changes are needed for my final visualizations and story.


# References

1. U.S. Department of Education. (n.d.). College Scorecard. https://collegescorecard.ed.gov/data/

2. U.S. Department of Education. (n.d.). College Scorecard Data Documentation. https://collegescorecard.ed.gov/data/data-documentation/

3. Berinato, S. (2016). Good Charts: The HBR Guide to Making Smarter, More Persuasive Data Visualizations. Harvard Business Review Press.


# AI acknowledgements

I used ChatGPT to help me understand the Part II assignment requirements and discuss how to improve my project based on the feedback from Part I.

I also used ChatGPT to help me understand Tableau operations, discuss visualization ideas, develop my storyboard, prepare interview questions, and improve the grammar of my written explanations.

I created the visualizations in Tableau Public using College Scorecard data and reviewed the charts myself. The interview findings will come from actual interviews, and I will use the feedback to improve my final project.
