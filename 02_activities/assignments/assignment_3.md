# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify:
## Visualization 1: Bar chart of Covid cases for Schools in Milton
> What software did you use to create your data visualization?
I used Python with Matplotlib to create the bar chart. 
> Who is your intended audience? 
The intended audience for this graph will be Education authorities and public health officials who are monitoring the trend to see the distribution of Covid-19 cases in schools in Milton to make decisions regarding interventions in schools. This graph will also be useful general public(esp parents of the students in these schools) to understand Covid-19 cases data in Milton area.
> What information or message are you trying to convey with your visualization? 
The goal is to communicate the distribution of COVID-19 cases among various schools in Milton, showcasing the percentage of total cases at each school. This visualization helps the viewer quickly understand which schools are most impacted by COVID-19, potentially guiding policy decisions and interventions.
> What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
 - Substantive: I focused on displaying accurate data about the percentage of cases at each school.Data integrity was preserved by using the sum of cases per school and calculating their percentage of the total.
 - Perceptual: The bar chart format was chosen because it is easy to compare categories (schools) and is great for displaying relative quantities. The Y-axis scale was adjusted to avoid large gaps, ensuring the graph does not appear empty.
 - Aesthetic: A high-contrast color scheme (black bars and white on white background) was used to make the chart accessible, especially for people with visual impairments. Font choices and label sizes were adjusted to ensure readability and clarity
> How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
The code and data processing steps are clearly outlined. Matplotlib is an open-source Python library, and the Python environment used can be replicated on any system. I commented the code as well to ensure the next person who creates the visualization understands the steps too. 
> How did you ensure that your data visualization is accessible?  
To ensure accessibility I used high contrast colors(black bars on white background) for people with visual impairments e.g. color blindness. Large font sizes were used for axis labels and titles ensure that the text is readable for people with low vision. And finally, I used clear data label placement to ensure, the graph is understand-able.
> Who are the individuals and communities who might be impacted by your visualization?  
- Families whose children are students in the various schools of Milton. The visualization provides them with insight on how Covid-19 is impacting schools in the municipality 
- Schools staff working in the each of the locations. To plan their response to these outbreaks 
- Govt & Schools boards who have to base their interventions on this data    
> How did you choose which features of your chosen dataset to include or exclude from your visualization? 
I wanted make a comparision of outbreaks in different schools. The data set is too large hence I decided to focus on one muncipality to show meaningfull information    
> What ‘underwater labour’ contributed to your final data visualization product?
I cleaned the raw data to extract meaningful insights, such as calculating the sum of cases and percentages per school. Additionally, I refined the graph for better readability, which involved some trial and error. I also thoroughly explored the data to filter it specifically for schools in Milton. 
## Visualization 2: Trendline for Covid-19 cases in all municipalities 
> What software did you use to create your data visualization?
I used PowerBI to make this visualization. I imported the csv file into Power Bi and designed this graph
> Who is your intended audience? 
The intended audience will be public health officals & policy makers in Ontario who are monitoring the trend in Covid-19 cases in schools. This is also an insightful graph for families which have children going to schools during the pandemic    
> What information or message are you trying to convey with your visualization? 
The visualization aims to show the trend of total confirmed COVID-19 cases in schools over time, specifically from September to December. It highlights the significant increase in cases, particularly between November and December. The message is to illustrate the severity and progression of the COVID-19 situation in schools during this period.    
> What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
- Substantive: The data is about Covid-19 cases across municipalities in Ontario. The line chart is easy to understand and has clear data labels for the audience
- Perceptual: The axes and data labels are clearly visible for the audience. The trend line is easy to interpret even if you are not good with data. The use of single blue color over white background provides contrast and focus
Aesthetic: The chart elements are well-balanced. Same font style has used throughout the chart. Ariel font & high contrast has been used to ensure readability for people with visual impairments  
> How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
PowerBI is more reproducible than Excel & Google sheets. It allows you to save the visualization along with the setting and data connections used. Sharing the file with others enable them to open and interact with the visuals. However, if others don't have the same permissions to access your data sources, they won't be able to refresh or fully reproduce the visualization.   
> How did you ensure that your data visualization is accessible?  
To ensure accessibility I used high contrast colors(black text and blue trendline over white background)I also chose a font which is considered readable for people with visual disabilities.  Large font sizes were used for axis labels and titles ensure that the text is readable for people with low vision. And finally, I used clear data label placement to ensure, the graph is understand-able.    
> Who are the individuals and communities who might be impacted by your visualization?  
- Families whose children are students in the various schools of Milton. The visualization provides them with insight on how Covid-19 is impacting schools in the municipality 
- Schools staff working in the each of the locations. To plan their response to these outbreaks 
- Govt & Schools boards who have to base their interventions on this data        
> How did you choose which features of your chosen dataset to include or exclude from your visualization? 
I wanted to show the trends of Covid-19 cases by month in Ontario. The trend line only need cases along with dates  
> What ‘underwater labour’ contributed to your final data visualization product?
I did data cleanup on the collected_date column to ensure the dates are plotable on the graph by removing the timestamps and just keeping the dates. To load the file onto PowerBI I had to set the columns type for certain fields to ensure right data type is selected. To create the visualization, I summarized the total_confirmed_cases column. This allowed me to aggregate the data and display the overall trend of COVID-19 cases in schools over time.

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
