# Learning-Data-Science
Find out resources, tools, and most importantly the steps you will have to take to kickstart your data science journey. This resource is primarily made for this interested in data science for data analysis

**Note**: _This repo documents resources that can help you better understand data science particularly for data analytics. It contains my experience as a participant of the [atomcamp's](https://www.atomcamp.com/dsbootcamp/) data science bootcamp and from the open world of the internet_

## Data Life Cycle ##
Working with data can be messy and complicated so in order to avoid any "foreseen" issues, it's important to pursue data with a systems/structural approach. This is where the term Data Life Cycle Life comes in. As the name denotes, it provides a framework to illustrate how data flows from one step to another, and depending the task at hand, which step you could initiate your work from.

Depending on your niche, and the kind of project you're working on, the Data Life Cycle can have 6 to 8 steps.

1. Data Generation
2. Data Collection
3. Data Cleaning or Processing
4. Data Analysis
5. Data Visualization & Interpretation
6. Data Storage
7. Data Management
8. Data Destruction

The 2 extra steps are Data Generation and Data Destruction (the beginning and the end, quite literally) which th rest of the 6 are sandwiched in. Here we're going to leave the bread and focus on the 6 layers inside.

_Note: You may come across the same steps with different names or stacked together, but essentially they fulfill the same purpose._

### Data Collection ###

### Cleaning or Processing ###
Be it cooking or working with data, the first thing you need to do is clean!
Data gathered from different sources is often messy/dirty. There maybe (will be) errors, inconsistencies, duplicates, irrelevant data, or missing values. These issues can provide inaccurate analysis results and misleading insights. Data cleaning is the process of fixing or removing incorrect, corrupted, incorrectly formatted, duplicate, or incomplete data within a dataset. [1](https://www.tableau.com/learn/articles/what-is-data-cleaning)

When you have to cook something, you sort out your ingredients and dishes, you either take them to the sink or grab a cleaning paper (or luckely you find out that it's already cleaned). Similarly when you start working with dataset, the data inside it might need a different levels of cleaning. Now if there are 1000s of rows and 10s of columns (maybe more) you can't just start cleaning each cell (that's crazy!). Instead, you can implement a series of steps and use features that can help you clean your data in bulk. 

_Note: These steps are based on Excel, I'll add more (PowerBi, Tableau, SQL) later._

1. **Remove duplicate or irrelevant observations:**

_Conditional Formatting for Duplicates:_ Highlight duplicate values using conditional formatting. This can be found in the "Home" tab. It doesn't remove duplicates but makes them visually noticeable.

_Advanced Filter:_ Use the "Advanced Filter" option in the "Data" tab to filter unique records or copy them to another location.

2. **Fix structural errors:**

_Flash Fill:_ Excel's Flash Fill feature (available in the "Data" tab) can automatically fill values based on patterns it recognizes. This is particularly useful for cleaning and formatting data quickly.
_Named Ranges:_ Organize your data using named ranges, which can simplify formulas and make your data structure more robust.
Filter unwanted outliers:

_Sorting:_ Sort data in ascending or descending order to identify outliers easily. This can be done in the "Data" tab.

3. **Handle missing data:**
 
_PivotTables:_ Create PivotTables to summarize and handle missing data more efficiently. Excel automatically excludes empty cells from calculations in PivotTables.

_IFERROR Function:_ Use the IFERROR function to replace errors, including #DIV/0! or #VALUE!, with a specified value or an alternative calculation.

4. **Validate and QA:**

_Data Validation with Dropdown Lists:_ Create dropdown lists using data validation to ensure that data entered meets predefined criteria.

_Cell Comments:_ Add comments to cells to provide additional information or instructions, enhancing data documentation.
