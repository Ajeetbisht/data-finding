# Communicate-Data-Findings

### The "Why"
Data visualization is an important skill that is used in many parts of the data analysis process. 

Exploratory* data visualization generally occurs during and after the data wrangling process, and is the main method that you will use to understand the patterns and relationships present in your data. This understanding will help you approach any statistical analyses and will help you build conclusions and findings. This process might also illuminate additional data cleaning tasks to be performed. 


### Project Details

1. Dataset: [Ford GoBike](https://www.fordgobike.com/system-data)
2. Explore the data: Feel free to explore the jupyter notebook where the dataset is visually, and programatically explored. 
3. Document the story: organized findings convey a story to present to an audience.
4. Communicate the findings - a slide deck with my findings is prepared for a curious audience.

### Project Findings
This project is of ford bike share data.

- Environmentally friendly, budget friendly, and lifetsyle friendly.
- Subscribers (i.e. daily commuters).
- Customers (i.e. tourists, students, etc).

There are two types of clients using the system: Subscribers and Customers. Subscribers are primarily daily commuters, having short trips to and from work, who rent a bike on weekdays at 8-9am and 5-6pm. Customers are usually tourists or occassional riders who use the system mainly on weekends to explore the Bay Area. Age is also a factor within user type. Subscribers who fall in the age group between 26-35 years old are the most common age group to use the bike sharing system.


### Files
- readme.md - This Markdown file contains sections that you should fill out as you select your dataset, complete your exploration, and plan your explanatory analysis. 

- exploration_template.ipynb - This Jupyter Notebook contains section templates to help you organize your exploration, starting from loading in the data, working through univariate visualizations, and ending with bivariate and multivariate exploration. 

- slide_deck_template.ipynb - This Jupyter Notebook contains starter cells to help you organize your slide deck deliverable. These cells provide an example of how the slide deck should be organized, including pre-set slideshow settings.

To view the slide deck, you will need to use the expression (all one line):
jupyter nbconvert Example_Project_Diamonds_Part2.ipynb --to slides --post serve --template output_toggle

- output_toggle.tpl - This template file can be used with nbconvert to export your slide deck. This adds extra functionality to the slide deck by hiding the code to start, only making it visible if the reader clicks on the output (which should mostly be visualizations in the case of this project). 
