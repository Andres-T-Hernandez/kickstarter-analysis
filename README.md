
# kickstarter-analysis
Performing analysis on kickstarter data to uncover trends# Kickstarting with Excel

## Overview of Project
### Purpose
The purpose of this analysis is to gain insights on Kickstarter success.  In particular, we will use a provided data on Kickstarters to analyze the success of the theatre and play categories based on their launch date as well as their financial goals. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The first analysis used excel to analyze outcomes based on launch date.   First using the provided dataset, a new sheet was made to create a pivot table.  Then a pivot table was made isomg information on Kickstarter play's launch date and outcome and filtering by category.  The pivot table was filtered by the Theatre category, and a pivot chart was created to analyze success by month.
![enter image description here](https://raw.githubusercontent.com/Andres-T-Hernandez/kickstarter-analysis/main/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
The second analysis used excel to compare the success rate of different Kickstarter goal ranges.  In an empty excel sheet, a range of Kickstarter goals were used to compare against each other roughly $5,000 apart.  The excel function "countif" was then used to count the number of successful plays for a given goal.  This was repeated for failed and canceled Kickstarter campaigns.  The percent of Kickstarters that succeeded, failed, and were canceled were then calculated.  Finally, a graph was made to compare each category.
![enter image description here](https://raw.githubusercontent.com/Andres-T-Hernandez/kickstarter-analysis/main/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
There were no technical difficulties, though there were limitations on the dataset described later.  The greatest issue perhaps came from the horizontal axis for outcomes based on goals, with font needing to be exceptionally small to match the given graph format.  In the future I would find a way to make this more compact.

## Results

- *What are two conclusions you can draw about the Outcomes based on Launch Date?*
The clearest insight from the outcomes based on launch is the steady increase of successful campaigns at the start of summer, followed by their steady decrease into winter.  However an additional insight is that the number if failed campaigns holds relatively steady throughout the year, so at least part of the increase in successes is due to more campaigns.  Still, it is likely worthwhile to consider starting a campaign around this time.

- *What can you conclude about the Outcomes based on Goals?*
Looking at the graph, there doesn't seem to be much difference between Kickstarter goals between $5,000 and $20,000.  Given Louisa's campaign is near $10,000, I do not think she needs to worry about making an adjustment.  However it does seem to be more or less a coinflip, I would then try to consider the launch date to try to improve campaign success.

- *What are some limitations of this dataset?*
Two important limitations come to mind.  The first is the filtered data essentially makes the canceled campaigns meaningless or even non-existent, they may as well not exist in the analysis besides noting they don't exist.  Secondly, while there is interesting information on larger campaign goals, the sample size is extremely small and I would strongly hesitate to draw conclusions from it.  In general, the filtration leads to some limitations on how far we can take certain analysis.

- *What are some other possible tables and/or graphs that we could create?*
I think comparing the size of the goals and the amount of backers could be useful, and in general trying to get a sense for whether to shoot for a large amount of small campaign donors or a few large donors.
