# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice: 

Data source: https://open.toronto.ca/dataset/toronto-raccoon-activity-index/
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
Python

    > Who is your intended audience? 
General public

    > What information or message are you trying to convey with your visualization? 
The number of raccoons spotted per ward in Toronto

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
Well, I considered design aspects that we learned in class (i.e., aesethic, substantive, perceptual, gestalt principles, cognitive load, other conventions like two-dimensional, clean layouts, and inclusion of data source at the bottom of the image). Specifically, I considered the type of data that I wanted to visually highlight, and bar chart seemed the most appropriate given that I wanted a total count of raccoon sightings per ward. After, I wanted to make sure that the highest count in the ward was visually represented by changing it to a high-contrast colour like orange, while the remainder are a purple colour. These colours were selected because they have a high contrast compliance with the white background. I then wanted to make sure that individuals can clearly see the total number of raccoons for each ward, so I added the counts to the top of the bar charts. And then I added labels to the axes, titles, and subtitles, as well as the data source information. To apply these codes, I used a combination of class notes and googling specific codes that we didn't learn but thought were important to include. 

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?
I used the open-source data file that was available on the Open Data Toronto link that we were provided in class. Therefore, anyone can use the data source to reproduce the results by specifically selecting the data points that I used (# of wards and # of raccoon observations per hour). 
    
    > How did you ensure that your data visualization is accessible?  
In terms of accessibility, I made sure that the font sizes and colours were AODA compliant (e.g., acknowleding red-green blindness and using high contrast colours)

    > Who are the individuals and communities who might be impacted by your visualization?  
 The people who live in each ward within Toronto   
 
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
Similar to my answer above, I considered which data to include and specifically what to hone in on. For example, the raccoon activity dataset had other columns that I could have included (e.g., bins compromised, incidents of raccoon and human standoff, complaints, proximity), but my goal was to objectively identify the number of raccoons per ward. To keep things simple and easy to comprehend at first glance, I focused on features that would help individuals see the number of raccoons per ward and then visually highlight which ward had the highest by using a different colour. I also made it so that the order goes highest to lowest. 

    > What ‘underwater labour’ contributed to your final data visualization product?
There was some trial and error to figure out which colour combinations made the most sense, figuring out how to best decide on ward titles and adjusting rotation angles. I also did some debugging (e.g., I had rotations twice and had to ensure that it was only the 45 degree angle and not the 90 degree angle)

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
