# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
    Excel and its basic functions.
    
    > Who is your intended audience? 
    Anyone interested in library circulation of all resources.
    
    > What information or message are you trying to convey with your visualization? 
    Yearly resource usage of each library, to see how many resources each Library is circulating and compare the types of resources within a library but also across libraries.
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    Here I decide on totally different colours to denote the categorical nature of the bars, so rather than one colour getting darker or more saturated, each category is a distinct colour. I also made the decision to limit the y-axis to 1000000 even though there were a few bars greater than that, because the majority of the data was much lower and it would have been hard to see comparisons at a lower level (though it is still difficult).
    Like with the Python graph, I also decided to limit the rows because otherwise there was too much data to be manageable in a static plot (and also because data cleaning in prep is outside the scope of this assignment).
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    This is not entirely reproducible unless I create some kind of readme file documenting my steps. The first sheet is the raw data from the website, but on Sheet 2 "Graph" I kept only a certain amount of rows. It is somewhat reproducible if people have the excel file, because they can use the built-in functions in excel to see the raw data, what the data range for the graph is, etc. The lack of total transparency may impact the credibility of the visualization, unless I created a documented readme file.

    
    > How did you ensure that your data visualization is accessible?  
    As mentioned, I tried to choose a color palette that was suitable for categorical data, such that each category is a unique colour. I also increased the figure size so that the text was non-overlapping and moved the legend outside of the graph. Additionally, I changed the y-axis so that the bars were more appropraitely sized.
    
    > Who are the individuals and communities who might be impacted by your visualization?  
    Anyone who would be impacted by circulation of the library resource may be impacted. For example, libraries that consistently have 0 use in a category, may lose some of their catalogue, negatively impacting all the patrons of the library and perhaps the funding of the library as well. Alternatively, the government may take this as a signal to increase music use at various libraries.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    There was a lot of data, and for the simplicity of the visualization I included only about 40 rows. However this time I wanted to compare the circulation of all resources, not just music as in the other graph. Because there was more than 1 outcome per library, I opted for a clustered bar graph. However using the entire data set would have had about 300 rows, which is too much data considering one variable was still categorical with no repeats.
    
    > What ‘underwater labour’ contributed to your final data visualization product?
    This data is about libraries, which is a location full of underwater labour as it provides all kinds of services to community members for free. In terms of the data visualization labour, the data had to be collected and aggregated for each library, as well as put into a table and hosted online for public access. This likely included many layers of bureaucracy to approve what kinds of data could be released for open access. I also did a bit of data prep before moving to visualization, and the creation of this visualization also depends on the functions of Excel, which Microsoft had to create and maintain.

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
