# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  

https://public.tableau.com/app/profile/ann.paul7865/vizzes
    python visualisation in a seperate file - assignment3.ipynb
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
    I made use of python coding in Microsoft Visual Studio and Tableau Public for this assignment.

    > Who is your intended audience? 
    Audience likely interested in healthcare
    
    > What information or message are you trying to convey with your visualization? 
    The goal of my visualization is to highlight patterns in outbreak occurrences, identify the most common causative agents, and analyze the duration of outbreaks. By presenting this information, I aim to help decision-makers and the public track trends, identify high-risk periods, and prioritize intervention strategies.


    
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
    Substantive:
    Here , I focused on data relevance by selecting key variables (Date, Causative Agent, Outbreak Duration).Used summary statistics (e.g., outbreak counts, average duration) to provide meaningful insights.
    Perceptual:
    To make things clear. I used clear, contrasting colors to differentiate categories.Aesthetic:
    To make it visually good I used consistent color palettes, applied minimalistic design to avoid clutter and adjusted axis scales and data labels for better clarity.
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    Here, in this case, i just chose a small dataset, ranging from year 2023-2025. The count of outbreaks would remain static and will not change. In real word coding, we can set seed in python code to ensure the results are reporoducible.
    
    > How did you ensure that your data visualization is accessible?  
    Ensured interactive filters in Tableau so users can customize views.
    
    > Who are the individuals and communities who might be impacted by your visualization?  
    Public health authorities & epidemiologists → Helps them monitor trends and allocate resources effectively.
    Healthcare institutions & policymakers → Guides decision-making on outbreak prevention strategies.
    General public & media → Raises awareness about outbreaks in their communities.
    Researchers & data scientists → Offers insights for further study on disease patterns.

    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    Included:
    Date columns (to analyze trends).
    Causative agents (to identify common disease-causing factors).
    Outbreak duration (to measure the impact of different outbreaks).
    Excluded:
    Institution Address (since geographic trends were not the main focus).
    ID column (not useful for analysis).
    Inactive outbreak records (to focus on ongoing and recently closed outbreaks).
    
    > What ‘underwater labour’ contributed to your final data visualization product?
    Data cleaning & preprocessing (handling missing values, correcting date formats).
    Merging multiple CSV files into a single dataset.

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
* Submission Due Date: `23:59 - 09/03/2025`
* The branch name for your repo should be: `assignment-4`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
