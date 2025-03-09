# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
Python:Please see the Assignment_3_Python code for details.
Excel: 
Please see Assignment_3_excel for details.

- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?

    > Who is your intended audience? 
    
    > What information or message are you trying to convey with your visualization? 
    
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    
    > How did you ensure that your data visualization is accessible?  
    
    > Who are the individuals and communities who might be impacted by your visualization?  
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    
    > What ‘underwater labour’ contributed to your final data visualization product?

    Python:
    I used Python with libraries: Pandas, Matplotlib and seaborn.
    My intended audience are city planners, policymakers and also parents and caregivers.
    This aim to show how many EarlyON centres exist in each ward of toronto. It helps to identifying which wards have more centres and thus better accessibility.
    Design Priciples：Substantive: using a bar chart as it's the most effective way to compare discrete wards.
                      Perceptual: Consistent color scheme to help differentiate values. labeled axes and title clearly to avoid misinterpretation. sorted bars in descending order to make it easy to compare wards.
                      Aesthetic: use seaborn's color palette to create a professional and visually appealing plot.
    The code is fully scripted in Python, so others can run and reproduce the visualization with the same dataset.
    By using large, legible labels for axes and titles to make the text clarity. 
    Families and caregivers can see which wards have better access to EarlyON centres.
    By including only Ward Name and Count, but excluded the centre addresses and service hours or types to ensure the visualization remains focused and easy to interpret.
    By using Pandas to group the data, Fixing errors, choosing the best way to present the data clearly and runing the code multiple times to confirm the outout is correct, it ensures the final visualization is accurate, clear and meaningful.
    Excel：
    I used Excel to create the deographic distribution of EarlyON centres. I was planed to show some more readable information, like Major-intersection, but it is not worked as I planed. 
    So the intended audience are city planners or researchers who will examine the geographic distribution of services, explore areas with low access and the need for more services, and inform dicisions regarding future resource allocation.
    Design Priciples：Substantive: It directly visualizes the geographic locations of EarlyON centres.
                      Perceptual: Axis labels are clearly marked as Latitude and Longitude to make the coordinates easily understandable.
                      Aesthetic: By using clear markers for each EarlyON centre, it ensure the map is eas to read and aesthetically appealing.
    The visualization is created by EXCEL, so anyone with access to the dataset can replicate the process by following the same steps.
    The city planners or researchers who will examine the geographic distribution of services, explore areas with low access and the need for more services, and inform dicisions regarding future resource allocation.
    Only included Latitude and Longitude.
    

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
