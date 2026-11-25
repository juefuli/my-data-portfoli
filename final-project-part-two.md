
---
---

<style>
.project {
  max-width: 1050px;
  margin: auto;
  font-family: Arial, sans-serif;
  color: #18334f;
  line-height: 1.75;
}
.project h1 {font-size: 34px; color: #173552;}
.project h2 {
  font-size: 26px;
  color: #173552;
  border-bottom: 2px solid #dce6ed;
  padding-bottom: 12px;
  margin-top: 55px;
}
.project h3 {font-size: 21px; color: #173552;}
.project a {color: #247a91;}
.project .nav {
  display: flex;
  gap: 15px;
  flex-wrap: wrap;
  padding: 18px 0;
  border-bottom: 1px solid #dce6ed;
  font-size: 14px;
}
.project .hero {text-align: center; margin: 35px 0;}
.project .hero img {
  width: 100%;
  border-radius: 15px;
}
.project .subtitle {color: #617487;}
.project .intro {
  font-size: 17px;
  max-width: 820px;
  margin: 25px auto;
}
.project .cards {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 14px;
  margin: 28px 0;
}
.project .card {
  background: #f0f6f9;
  padding: 22px;
  border-radius: 12px;
  border: 1px solid #dce6ed;
}
.project .card strong {
  display: block;
  font-size: 22px;
  margin-bottom: 5px;
}
.project .tag {
  color: #247a91;
  font-weight: bold;
  letter-spacing: 2px;
  font-size: 12px;
}
.project .chart {
  border: 1px solid #dce6ed;
  border-radius: 12px;
  overflow: hidden;
  margin: 25px 0;
}
.project .chart iframe {
  display: block;
  width: 100%;
  border: none;
}
.project .chartlink {
  padding: 15px 20px;
  background: #f0f6f9;
}
.project .note {
  background: #f0f6f9;
  padding: 18px 22px;
  border-left: 4px solid #4aa9ae;
  border-radius: 6px;
  margin: 22px 0;
}
.project table {
  width: 100%;
  border-collapse: collapse;
  margin: 20px 0;
}
.project th, .project td {
  padding: 13px;
  border: 1px solid #dce6ed;
  text-align: left;
  vertical-align: top;
}
.project th {background: #f0f6f9;}
.project .ending {
  background: #173552;
  color: white;
  padding: 30px;
  border-radius: 12px;
  margin: 30px 0;
}
@media(max-width:650px) {
  .project .cards {grid-template-columns:1fr;}
  .project h1 {font-size:27px;}
}
</style>

<div class="project">

<div class="nav">
  <a href="https://juefuli.github.io/my-data-portfoli/">Home</a>
  <a href="dataviz-examples.html">Data Viz Examples</a>
  <a href="critique-by-design.html">Critique by Design</a>
  <a href="final-project-part-one.html">Project I</a>
  <a href="final-project-part-two.html">Project II</a>
  <a href="final-project-part-three.html">Project III</a>
</div>

<div class="hero">
  <p class="tag">TELLING STORIES WITH DATA / FINAL PROJECT PART II</p>
  <img src="graph1.png" alt="College Cost Project Cover">
</div>

<div class="intro">
  <h2>Does Paying More Mean Earning More?</h2>
  <p>
    When students choose a university, tuition is often one of
    the first things they consider. But does paying more for
    college really mean getting better financial outcomes
    after graduation?
  </p>
  <p>
    I used College Scorecard data to compare college costs
    and graduate earnings. After receiving feedback from
    Part I, I decided to also include average net price
    because tuition alone does not show the full cost
    of attending college.
  </p>
  <p>
    My goal is to help students and their families understand
    what makes a college worth its cost.
  </p>
</div>

<div class="cards">
  <div class="card">
    <strong>30</strong>
    Selected Public Universities
  </div>
  <div class="card">
    <strong>3</strong>
    Interactive Tableau Charts
  </div>
  <div class="card">
    <strong>3</strong>
    Classmates in Critique Group
  </div>
</div>

<h2>01 / Wireframes and Storyboards</h2>

<p>
  I organized my story around three main comparisons.
  First, I look at tuition and graduate earnings.
  Then, I introduce net price to consider more college costs.
  Finally, I compare earnings across different universities.
</p>

<table>
  <tr><th>Step</th><th>Story</th><th>Main Question</th></tr>
  <tr><td>01</td><td>Introduction</td><td>Why do college costs matter?</td></tr>
  <tr><td>02</td><td>Tuition vs. Earnings</td><td>Do expensive universities have higher earnings?</td></tr>
  <tr><td>03</td><td>Net Price vs. Earnings</td><td>Does the relationship change after considering other costs?</td></tr>
  <tr><td>04</td><td>University Comparison</td><td>How do earnings differ across tuition groups?</td></tr>
  <tr><td>05</td><td>Conclusion</td><td>What should students consider?</td></tr>
</table>

<h3>01 — Tuition vs. Graduate Earnings</h3>

<p class="tag">THE STICKER PRICE</p>

<p>
  My first visualization compares in-state tuition with
  median earnings four years after completion.
  Each dot represents one university.
  I also added a trend line to explore the overall relationship.
</p>

<div class="chart">
  <iframe
    src="https://public.tableau.com/views/CollegeTuitionvsGraduateEarnings/Sheet1?:showVizHome=no&amp;:embed=yes"
    height="700"
    loading="lazy"
    title="Tuition vs Graduate Earnings">
  </iframe>
  <div class="chartlink">
    <a href="https://public.tableau.com/views/CollegeTuitionvsGraduateEarnings/Sheet1">
      Open Interactive Chart 1
    </a>
  </div>
</div>

<div class="note">
  <strong>How to Read This Chart</strong>
  <p>
    X-axis: In-State Tuition (USD)<br>
    Y-axis: Median Earnings Four Years After Completion (USD)<br>
    Each dot represents one university.
  </p>
  <p>
    The points are quite spread out, so the trend line
    should be interpreted carefully.
  </p>
</div>

<h3>02 — Looking Beyond Tuition</h3>

<p class="tag">NET PRICE AND COLLEGE AFFORDABILITY</p>

<p>
  Tuition is not the only cost students need to consider.
  Students also need to think about housing, food, books,
  and other expenses.
</p>
<p>
  Average net price considers the broader cost of attendance
  after grants and scholarships. I added this chart to see
  whether the relationship with graduate earnings changes.
</p>

<div class="cards">
  <div class="card">
    <strong>Tuition</strong>
    Published tuition and required fees.
  </div>
  <div class="card">
    <strong>Net Price</strong>
    Average cost after grants and scholarships for eligible students.
  </div>
</div>

<div class="chart">
  <iframe
    src="https://public.tableau.com/views/CollegeTuitionvsGraduateEarnings/Sheet12?:showVizHome=no&amp;:embed=yes"
    height="700"
    loading="lazy"
    title="Net Price vs Graduate Earnings">
  </iframe>
  <div class="chartlink">
    <a href="https://public.tableau.com/views/CollegeTuitionvsGraduateEarnings/Sheet12">
      Open Interactive Chart 2
    </a>
  </div>
</div>

<div class="note">
  <strong>Why This Matters</strong>
  <p>
    Two universities with similar tuition may have
    different net prices. The College Scorecard net price
    is an average for eligible students, not what every
    student personally pays.
  </p>
</div>

<h3>03 — University Comparison</h3>

<p class="tag">COMPARING GRADUATE EARNINGS</p>

<p>
  My third visualization compares graduate earnings across
  the 30 selected universities.
  The universities are sorted from the highest to lowest earnings.
</p>
<p>
  I used blue to highlight the highest tuition group and
  gray for the other groups. However, classmates thought
  this made some differences difficult to see.
</p>

<div class="chart">
  <iframe
    src="https://public.tableau.com/views/CollegeTuitionvsGraduateEarnings/Sheet2?:showVizHome=no&amp;:embed=yes"
    height="1100"
    loading="lazy"
    title="Graduate Earnings by Tuition Band">
  </iframe>
  <div class="chartlink">
    <a href="https://public.tableau.com/views/CollegeTuitionvsGraduateEarnings/Sheet2">
      Open Interactive Chart 3
    </a>
  </div>
</div>

<div class="note">
  <strong>Chart Design</strong>
  <p>
    Blue represents Q5, the highest-tuition group within
    this sample. Gray represents Q1–Q4.
    These groups are not national tuition rankings.
  </p>
</div>

<h3>04 — What Should Students Consider?</h3>

<p>
  My purpose is not to tell students which university
  they should choose. Instead, I want to show that tuition
  alone may not be enough to evaluate a college.
</p>

<div class="ending">
  <h3 style="color:white">Main Takeaway</h3>
  <p>
    Before choosing a university, students should compare
    tuition, net price, possible earnings, financial aid,
    academic major, and location.
  </p>
</div>

<p>
  My current analysis uses 30 selected universities.
  They were chosen to cover different states and tuition levels,
  not randomly selected. The results cannot represent
  all U.S. universities. The earnings measure covers an
  eligible group of graduates, and the charts show
  associations rather than cause and effect.
</p>

<h2>02 / User Research</h2>

<h3>Target Audience</h3>

<p>
  My target audience is prospective college students
  and their families. For Part II, I discussed my project
  with three classmates from Critique Group 8.
</p>
<p>
  I wanted to understand whether the charts were clear,
  whether the overall story made sense, and what I
  should improve.
</p>

<h3>Interview Script</h3>

<p>
  My main goal was to understand whether my visualizations
  were easy to understand and useful for students
  comparing universities.
</p>

<table>
  <tr><th>Goal</th><th>Question</th></tr>
  <tr>
    <td>Audience Priorities</td>
    <td>What factors are most important when choosing a university?</td>
  </tr>
  <tr>
    <td>Main Message</td>
    <td>What do you think my project is trying to show?</td>
  </tr>
  <tr>
    <td>Chart Clarity</td>
    <td>Which chart is easiest to understand? Which is confusing?</td>
  </tr>
  <tr>
    <td>College Costs</td>
    <td>Is tuition or net price more useful when comparing universities?</td>
  </tr>
  <tr>
    <td>Missing Information</td>
    <td>What other information would help you make a college decision?</td>
  </tr>
  <tr>
    <td>Design Feedback</td>
    <td>What would you change about the charts or story?</td>
  </tr>
</table>

<h3>Interview Findings</h3>

<p>
  After showing my three visualizations to classmates,
  I collected feedback about five main areas.
  I summarized the comments by topic because I did not
  record which classmate made each individual comment.
  I will keep their names private.
</p>

<table>
  <tr>
    <th>Area</th>
    <th>Feedback</th>
    <th>What I Learned</th>
  </tr>
  <tr>
    <td>University Selection</td>
    <td>Many universities were unfamiliar, and the sample selection was unclear.</td>
    <td>I need to explain my selection method.</td>
  </tr>
  <tr>
    <td>Trend Lines</td>
    <td>The points were scattered, and the straight lines did not seem to fit well.</td>
    <td>I should check the strength of the relationships.</td>
  </tr>
  <tr>
    <td>Net Price</td>
    <td>Some classmates did not understand why I added net price.</td>
    <td>I need a better explanation before the second chart.</td>
  </tr>
  <tr>
    <td>Bar Chart Colors</td>
    <td>Two colors made most universities look the same.</td>
    <td>I should make the tuition groups clearer.</td>
  </tr>
  <tr>
    <td>Historical Trends</td>
    <td>Classmates suggested showing college costs over time or comparing tuition and wage growth.</td>
    <td>Historical data might make my introduction stronger.</td>
  </tr>
</table>

<h3>Summary of User Research</h3>

<p>
  The feedback helped me realize that some problems
  are related to the data, not only the design.
</p>
<p>
  I need to explain how the universities were selected,
  check whether the trend lines are useful, and make
  the purpose of net price clearer.
</p>
<p>
  My classmates also suggested using historical data
  to explain how college costs have changed over time.
  I think this could make the beginning of the story
  more interesting.
</p>
<p>
  Overall, I learned that having more charts does not
  always make a better story. Each chart needs to have
  a clear purpose.
</p>

<h2>03 / Identified Changes for Part III</h2>

<p>
  Based on Part I feedback, I already added net price
  and changed the colors of my bar chart.
  The new feedback showed me what still needs improvement.
</p>

<table>
  <tr>
    <th>Research Synthesis</th>
    <th>Anticipated Changes for Part III</th>
  </tr>
  <tr>
    <td>The university sample is unclear.</td>
    <td>Explain the selection method and consider a larger or more systematic sample.</td>
  </tr>
  <tr>
    <td>The trend lines may be misleading.</td>
    <td>Check the fit and consider removing them.</td>
  </tr>
  <tr>
    <td>Readers do not understand net price.</td>
    <td>Add a short explanation of tuition and net price.</td>
  </tr>
  <tr>
    <td>The two-color design is too simple.</td>
    <td>Try five shades of the same color for Q1–Q5.</td>
  </tr>
  <tr>
    <td>Historical context is missing.</td>
    <td>Explore historical tuition data and consider an opening trend chart.</td>
  </tr>
  <tr>
    <td>Tuition growth vs. wage growth could be interesting.</td>
    <td>Check comparable data and decide if it fits the story.</td>
  </tr>
  <tr>
    <td>The story needs a clearer takeaway.</td>
    <td>Focus on helping students compare multiple financial factors.</td>
  </tr>
</table>

<div class="ending">
  <h3 style="color:white">Next Steps</h3>
  <p>
    For Part III, I plan to improve the data selection first,
    then the chart design and explanations.
    My goal is to make the story clearer and more useful
    for students and their families.
  </p>
</div>

<h2>04 / References</h2>

<p>
  U.S. Department of Education.
  <a href="https://collegescorecard.ed.gov/data/">
    College Scorecard
  </a>.
</p>
<p>
  U.S. Department of Education.
  <a href="https://collegescorecard.ed.gov/data/data-documentation/">
    College Scorecard Data Documentation
  </a>.
</p>
<p>
  Berinato, S. (2016).
  <i>Good Charts: The HBR Guide to Making Smarter,
  More Persuasive Data Visualizations.</i>
  Harvard Business Review Press.
</p>

<h2>05 / AI Acknowledgements</h2>

<p>
  I used ChatGPT to help me understand the Part II
  requirements, discuss feedback from Part I,
  organize my storyboard, understand Tableau operations,
  prepare interview questions, and improve my grammar.
</p>
<p>
  ChatGPT also helped with the initial selection of
  university data, creating a cover image, and arranging
  the GitHub page.
</p>
<p>
  I created the Tableau visualizations using College
  Scorecard data and reviewed them myself.
  The feedback reported in this project came from
  my classmates.
</p>

</div>
