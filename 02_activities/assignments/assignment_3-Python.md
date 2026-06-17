# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
    Python and the Seaborn package.
    
    > Who is your intended audience? 
    Anyone interested in library circulation of music files.
    
    > What information or message are you trying to convey with your visualization? 
    Annual Music Downloads/Use per library, limited to libraries beginning in A or B.
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    I decided to add color to try to make the dots more obvious and in a way that reflected increasing scale. The larger values are darker, as there are fewer of them, so they are more notable. I also decided to limit the rows because otherwise there was too much data to be manageable in a static plot (and also because data cleaning in prep is outside the scope of this assignment).
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    Because they were produced in Python, anyone can download the file and run the code to make the graph. I did convert the original xlsx file from the website to csv and convert all the values to numerical, so this will not be reproducible unless I make my version of the file publicly accessible.
    
    > How did you ensure that your data visualization is accessible?  
    I tried to choose a color palette that was suitable for ordered data, as it gets darker to the right. I also increase the figure size so that the text was non-overlapping and moved the legend outside of the graph.
    
    > Who are the individuals and communities who might be impacted by your visualization?  
    Anyone who would be impacted by music use of the libraries may be impacted. For example, libraries that consistently have 0 use, may lose their music catalogue, negatively impacting all the patrons of the library and perhaps the funding of the library as well. Alternatively, the government may take this as a signal to increase music use at various libraries.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    There was a lot of data, and for the simplicity of the visualization I included only about 40 rows of this single variable. I was interested in music use in the library, and thus chose that variable. Using the entire data set would have had about 300 rows, which is too much data considering one variable was categorical with no repeats.
    
    > What ‘underwater labour’ contributed to your final data visualization product?
    This data is about libraries, which is a location full of underwater labour as it provides all kinds of services to community members for free. In terms of the data visualization labour, the data had to be collected and aggregated for each library, as well as put into a table and hosted online for public access. This likely included many layers of bureaucracy to approve what kinds of data could be released for open access. I also did a bit of data prep before moving to visualization, and the creation of this visualization also depends on the Python packages that people have created and maintained.

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
