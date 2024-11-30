# Data Visualization

## Assignment 3: Data Visualization Ethics

### Requirements:
- Let’s return to the data visualizations we evaluated for Assignment 2.  
- For each visualization: 
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) whether or not you think this data visualization is accessible, reproducible, and equitable. 

        - GOOD example: The proportional tree chart is relatively accessible because its clean, minimalistic design reduces cognitive load. The use of side-by-side squares with contrasting colors enables quick comparisons, making it user-friendly for most audiences, including those with color vision deficiencies, if appropriate color scales are used  It is reproducible because the format is straightforward and can be generated using standard visualization libraries like matplotlib or ggplot.  In terms of equity, this chart effectively avoids overrepresentation or underrepresentation of categories. However, the lack of labels or context might disproportionately exclude audiences who are less familiar with the data domain.

        - BAD example: The multi-level donut chart is not particularly accessible due to its complexity. The concentric rings require viewers to decipher multiple hierarchies simultaneously, which can overwhelm users and make small segments difficult to interpret. This is particularly problematic for individuals with visual impairments or those unfamiliar with advanced visualizations. It is moderately reproducible, as most visualization libraries (e.g., D3.js, Tableau) can generate this format; however, achieving clarity requires significant effort. In terms of equity, this chart can marginalize data segments of smaller size, making it difficult to communicate their importance, especially when segments are visually compressed into narrow slices.

    - How could this data visualization have been improved (in terms of accessibility, reproducibility, equity)?  
    
        - GOOD example: To enhance accessibility, the addition of text labels within or adjacent to the squares would make the chart understandable for a wider audience. Including a legend and ensuring high-contrast color schemes would further improve usability for individuals with visual impairments. Reproducibility could be bolstered by using open-source tools and providing code snippets to enable replication. To address equity, interactivity could allow users to delve deeper into categories, reducing reliance on prior knowledge while still maintaining simplicity.

        - BAD example: To improve accessibility, replacing the multi-level donut chart with a treemap or a sunburst chart would offer a more linear and intuitive representation of hierarchical data. These formats reduce visual clutter and allow audiences to follow the data’s flow naturally. High-contrast colors and accessible legends could also aid interpretation. For reproducibility, guidelines and annotated code samples for creating an alternative visualization (e.g., treemaps) should be shared. Finally, ensuring equity requires presenting all data segments proportionally and incorporating interactivity to reveal details about smaller segments, empowering viewers to understand the dataset comprehensively without bias.


- Word count should not exceed (as a maximum) 300 words for each visualization. 

### Why am I doing this assignment?:
- This ongoing assignment ensures active participation in the course, and assesses learning outcomes 2 and 3:  
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
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * This markdown file (assignment_3.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
