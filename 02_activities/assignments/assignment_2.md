# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
      Your answer...

Good visualization Exemple: Life expectancy vs. GDP per capita (source: https://ourworldindata.org/grapher/life-expectancy-vs-gdp-per-capita).

Reasons why this visualization is considered good:

- Appropriate chart type for the question: A scatterplot is well-suited for showing association (life expectancy vs. income) and for spotting clusters/outliers across countries rather than implying a single “average” relationship.
- Uses strong perceptual encodings: Viewers read values primarily by position on a common scale, which is one of the most accurate ways people decode charts (better than area/volume-heavy displays).
- Supports exploration without distorting the data: OWID charts typically allow filtering and time changes (e.g., selecting countries or years), helping users build a story (development and health) while keeping the underlying scales consistent.
- Transparency and reusability: The chart is embedded in a site that clearly emphasizes data and reuse/licensing norms, which supports critical consumption (where it came from and how it can be reused).

Bad visualization exemple: Fox News “If Bush tax cuts expire” bar chart (Top Tax Rate), archived here.(Source: https://www.storytellingwithdata.com/blog/2012/09/bar-charts-must-have-zero-baseline)

Reasons why this visualization is considered bad:

- Misleading scale (non-zero baseline) for bars: Bar charts communicate magnitude through length from a baseline. Starting the y-axis at 34% exaggerates the apparent increase and is widely recognized as deceptive for bars.
- Amplifies a small change into a dramatic visual jump: The chart’s design makes a change from 35% to 39.6% look enormous; Knaflic shows that with the truncated axis it reads like ~“5× higher,” while the true relative change is about 13%.
- Chartjunk/clutter reduces signal: Heavy borders, gradients, and dense gridlines add “non-data ink,” distracting from the numbers—exactly the kind of clutter Tufte’s data-ink idea warns against.
- Weak labeling and poor interpretability: The axis treatment and styling make it easy to miss the baseline problem; the design appears optimized to persuade rather than inform.

      ```

    - How could this data visualization have been improved?  
      ```
      Your answer...

- Start the y-axis at zero (or switch away from bars). If the goal is to compare two points, a slopegraph or dot plot with clear labels would show change without baseline distortion.

- Label clearly and add context. Put the y-axis label (“Top tax rate (%)”), show the exact values prominently, and state whether the message is about percentage points (+4.6 pp) or percent increase (~13%).

- Remove chartjunk. Use a plain background, light/limited gridlines, no gradients, and no decorative framing to maximize data-ink.

- Disclose source and assumptions (what policy scenario, which bracket, which law), so viewers can evaluate the claim rather than just react to the picture.





      
      ```
- Word count should not exceed (as a maximum) 500 words for each visualization (i.e. 
300 words for your good example and 500 for your bad example)

### Why am I doing this assignment?:

- This assignment ensures active participation in the course, and assesses the learning outcomes
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:

| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 02/16/2026`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (assignment_2.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
