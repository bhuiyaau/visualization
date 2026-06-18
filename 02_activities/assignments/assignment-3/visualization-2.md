# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.

- For each visualization, describe and justify: 
Data source: https://open.toronto.ca/dataset/toronto-raccoon-activity-index/
    > What software did you use to create your data visualization?
Excel
    > Who is your intended audience? 
Ward councillors, animal control   
    > What information or message are you trying to convey with your visualization?
Average number of sightings of raccoons per hour by ward. Specifically, it shows a heat map of the highest averages by the hour. Parkdale-High Park and University-Rosedale are the hottest wards, and hours 0–3 (midnight to 3am) are consistently the busiest across all wards

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots?
Similar to the other visual, I considered design aspects that we learned in class (i.e., aesethic, substantive, perceptual, gestalt principles, cognitive load, other conventions like two-dimensional, clean layouts, and inclusion of data source at the bottom of the image). Specifically, I wanted to show a heatmap to highlight which hours were the busiest activity/number of raccoons based on the wards. So it used a two-dimensional, clean layout, and inclusion of the key data points. While it still looks like a data table, I can foresee those who have more experience with Tableau, they could overlay this heatmap to an actual map of Toronto and the actual wards, and then be able to change with a sliding toggle to go hour by hour. But unfortunately, I do not have that skillset nor the capacity to develop this in a timely manner. Therefore, this could be seen as an 'exploratory' and prototype version that could be translated by a skilled team member. Furthermore, I wanted to make sure this was substantive. I can see it being some cognitive load with the numbers.
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
While this was completed on Excel, individuals have access to the open-data source to verify the results. But Excel is inherently less reproducible than code like Python because there is no script that documents every code and formatting decisions. Instead, I would have to log every step of what I did (e.g., creating a pivot table, colour scale type, filters added). Therefore, individuals would have to manually reconstruct and therefore introduce minor differences in formatting 

    > How did you ensure that your data visualization is accessible?
I used a colour gradient that is accessible for those who are colour blind (e.g., purple colour instead of red-green). I also included the numbers so that the screen readers can still access the information if they cannot see. The font size, contrast between ward name text and background were high enough/
    
    > Who are the individuals and communities who might be impacted by your visualization?  
Ward councillors, animal control, and local residents. For example, for animal contral, they could schedule protective interventions. For local residents, this information could help folks understand when it is a good time to leave out garbage cans for garbage collection days, and which hours to avoid. 

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
Similar to my answer above, I considered which data to include and specifically what to hone in on. For example, the raccoon activity dataset had other columns that I could have included (e.g., bins compromised, incidents of raccoon and human standoff, complaints, proximity), but my goal was to objectively identify the average number of sightings of raccoons per hour by ward. Specifically, it shows a heat map of the highest averages by the hour.Other variables would have created noise and reduce clarity of the heat map. To keep things simple and easy to comprehend at first glance, I focused on features that would help individuals see the average number of raccoons per ward and then visually highlight which hours had the highest averagers by colour. I also made it so that the order goes highest to lowest by ward.

    > What ‘underwater labour’ contributed to your final data visualization product?
The 'underwater labour' is more invisible in Excel than Python. For example, formatting and resolving conflicting code parameters, iterative colour and layout changes only show the final decision. The final chart represents a culmination of decisions through trial and error and revision, none of which is visible in the final output.

- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 -  2026-06-16`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * Two distinct data visualizations (for example, PNGs, PDFs, or screenshots)
        * Two Markdown files answering all questions for each visualization (including a link to your dataset in both files)
        * One Python file contains the complete code and visualization, and another file (with or without code) contains the visualization.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
