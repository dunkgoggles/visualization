# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?

    1. I used Python for Visualization 1, specifically the pandas and matplotlib libraries, to create this data visualization. These tools allow for flexible, programmatic creation of charts, and the process is fully reproducible via the provided script.  

    2. Excel Visualization: https://docs.google.com/spreadsheets/d/19LMgMAZcGp6kbCVO7gvoZC8CvoBJDsxb/edit?usp=sharing&ouid=109009859095318812232&rtpof=true&sd=true

    I used Microsoft Excel to create a horizontal bar chart that visualizes the top contaminants contributing to fish consumption advisories in Ontario.

    > Who is your intended audience? 

    1. The intended audience includes policy-makers, environmental analysts, and members of the public concerned with fish consumption safety in Ontario. It's also suitable for students and educators exploring environmental data or health advisories

    2. The intended audience includes members of the general public, health-conscious consumers, and policy-makers interested in environmental health and food safety, especially those in Ontario.
    
    > What information or message are you trying to convey with your visualization? 

    1. This visualization communicates how advisory levels (i.e., consumption recommendations based on contaminant risks) vary by fish species. By focusing on the top 20 most commonly tested species, the visualization helps identify which species are most frequently associated with higher-risk advisories.

    2. The visualization highlights the most common chemical contaminants, such as PCBs, mercury, and dioxins—that lead to fish consumption advisories. The goal is to raise awareness of what substances most frequently pose health risks in Ontario’s lakes and rivers.
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 

    1. Initially I had intended to build an interactive map but it proved to be too difficult for me at this time. 

        Key aspects of design included:
        - A stacked horizontal bar chart for legibility of long fish species names.
        - A custom color palette progressing from cool blues to deep purples, - - - highlighting increasing advisory levels while avoiding the overuse of aggressive red hues.
        - A clean layout with clear labels, sorted species, and a legend for interpretability.
        - Careful use of proportions (not just raw counts) to show distribution of advisory levels per species.
    
    2. Key design considerations included:
        - Clarity: I used a horizontal bar chart for easy label readability.
        - Color accessibility: I applied a blue-to-indigo gradient to visually represent contaminant frequency without overwhelming color variation.
        - Minimalism: I removed non-essential elements (e.g., gridlines and borders) to keep the focus on the data.
        - Typography: Axis labels and titles were adjusted for legibility using bold and larger fonts.


    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 

    1. This piece is fully reproducable. It uses a shared dataset (Guide_to_Eating_Ontario_Fish_Advisory_Database_2024.csv). The script includes all steps from data loading and cleaning to plotting, and dependencies are standard open-source Python libraries. 

    2. The chart is based on a CSV file derived from the 2024 Ontario Fish Advisory dataset. The process involved:
        - Preprocessing data in Python to extract relevant contaminant counts.
        - Exporting a clean, summarized CSV that can easily be reloaded in Excel or Sheets.
        - Anyone with the same dataset and instructions can reproduce the chart. I also used consistent formulas and cell references in Excel, making it transparent and easy to replicate.
    
    > How did you ensure that your data visualization is accessible?  

    1. The use of color gradients was chosen for perceptual clarity, with a conscious effort to avoid red-green combinations that are difficult for people with colorblindness. The use of a horizontal layout helps support screen reader parsing and reduces label overlap, and species names and axis labels are presented in plain language, with no technical jargon.

    2.  - Chose high-contrast color schemes that are friendly to colorblind viewers.
        - Used text labels and clear titles so that the visualization can be interpreted without color alone.
        - Avoided relying on hover effects or interactivity, which may not be accessible to all users.
        - Ensured that fonts were readable and elements were spaced to avoid clutter
    
    > Who are the individuals and communities who might be impacted by your visualization?  

    1. Communities impacted may include:
        - Anglers and fish consumers in Ontario
        - Indigenous communities who may rely on fish as a key part of their diet
        - Environmental justice organizations concerned with pollution exposure
        - Public health stakeholders who communicate consumption safety
    
    2.  - Ontario residents, especially those who fish or eat locally caught fish.
        - Indigenous communities who rely on traditional fishing practices.
        - Public health agencies and environmental organizations aiming to educate the public or create policy.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 

    1. I chose to:
        - Include the Specname (fish species) and Adv Level (advisory level) columns
        - Focus on the top 20 species by frequency to keep the plot readable and relevant
        - Exclude geographic location, contaminant cause, and fish length in this visualization to avoid overcomplication and keep the message focused.

    2. I chose to focus on the “Advisory Cause” column and aggregated counts to show which contaminants are most frequently flagged. I excluded other dimensions like fish species, location, or advisory level to keep the message focused and clear for a general audience.

    
    
    > What ‘underwater labour’ contributed to your final data visualization product?

    1. This visualization involved several invisible steps:
        - Data cleaning: resolving inconsistent column names and formats
        - Exploration: assessing distributions, null values, and advisory level breakdowns
        - Trial and error: testing various chart types, sort orders, and color schemes
        - Debugging: handling CSV encoding issues, column coercion, and filtering errors
        - Design iteration: adjusting palette and layout to meet both clarity and accessibility standards

    2.  - Data cleaning and transformation in Python to extract advisory causes.
        - Manual inspection of column names, value formatting, and encoding issues.
        - Trial-and-error chart design in Excel to adjust colors, labels, and formatting.
        - Iterative feedback and troubleshooting visualization techniques across different platforms (Tableau, Python, Excel) to land on a practical and effective approach.

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
* Submission Due Date: `23:59 - 13/07/2025`
* The branch name for your repo should be: `assignment-3`
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
