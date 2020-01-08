# VISION 2020: an SAT data analysis

### Problem Statement

A new format for the SAT was released in March 2016. The College Board - the organization that administers the SAT - seeks reccomendations on where money is best spent to improve SAT participation rates. Using data from 2017-18 SAT and ACT datasets I propose a two pronged approach for increasing participation by capitlizing on the existing participation trends and using data to dispell negative press.

##### Project of Andrew Artz

This project was completed for General Assembly in June of 2019.

-------


### Project Files

Here are the project files, which may be found in the project one folder:

- [Work Book](http://localhost:8888/notebooks/code/project_one_submission.ipynb)
- [Presentation](https://git.generalassemb.ly/Andy4GA/project_1/blob/master/project_one_presentation.pdf)


---------


### Executive Summary

The methodlogy used for this project began with an inventory of all tools and datasets available. Four datasets were identified as well as the websites of the College Board and ACT Inc. The work of several thought-leaders in higher education were also bookmarked. Jupyter notebook was used to clean and document the data analysis of four .CSV files before merging them into one final workbook. The notebook was then supplemented with addition demographic data from the US Census Bureau's 5 Year American Community Survey. Visualizations were generated in Tableau and using Seaborn.

Provided by the College Board were four datasets. All data sets contained information on standardized tests used for undergraduate college admissions. These datasets were mostly complete with minor errors. All data frames contained information on statewide participation and total scores. It seemed likely that such datsets may provide the College Board with business intellengence and analytics that may increase national SAT participation.


### Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|string|All datasets|States were used as the key to merge all datasets in this project|
|a17_participation|float|ACT 2017|Percent participation in the 2017 ACT|
|a17_english|float|ACT 2017|Subject area scores for the 2017 ACT|
|a17_math|float|ACT 2017|Subject area scores for the 2017 ACT|
|a17_reading|float|ACT 2017|Subject area scores for the 2017 ACT|
|a17_science|float|ACT 2017|Subject area scores for the 2017 ACT|
|a17_composite|float|ACT 2017|The composite score provided as the mean of each subject area scores for the 2017 ACT|
|a18_participation|float|ACT 2018|Percent participation in the 2018 ACT|
|a18_english|float|ACT 2018|Subject area scores for the 2018 ACT|
|a18_math|float|ACT 2018|Subject area scores for the 2018 ACT|
|a18_reading|float|ACT 2018|Subject area scores for the 2018 ACT|
|a18_science|float|ACT 2018|Subject area scores for the 2018 ACT|
|a18_composite|float|ACT 2018|The composite score provided as the mean of each subject area scores for the 2018 ACT|
|s17_participation|float|SAT 2017|Percent participation in the 2017 SAT|
|s17_reading_writing|integer|SAT 2017|Subject area scores for the 2017 SAT|
|s17_math|integer|SAT 2017|Subject area scores for the 2017 SAT|
|s17_total|integer|SAT 2017|The sum total score of the math and evidence based reading and writing subject area scores for the 2017 SAT|
|s18_participation|float|SAT 2018|Percent participation in the 2018 SAT|
|s18_reading_writing|integer|SAT 2018|Subject area scores for the 2017 SAT|
|s18_math|integer|SAT 2018|Subject area scores for the 2018 SAT|
|s18_total|integer|SAT 2018|The sum total score of the math and evidence based reading and writing subject area scores for the 2018 SAT|


### Conclusions and Recommendations

This analysis concludes that while there is a negative association with higher statewide SAT participation percentage and lower statewide SAT scores, the degree of variation within the model indicates no strong association. Yet in spite of negative press, and misleading rhetoric linking higher statewide SAT participation with lower statewide SAT scores, participation in the SAT increased nationally from 2017-2018. In order to continue this growth, I propose that the College Board strengthen existing relationships while advancing into new markets, so that national participation in the SAT does not fall behind that of its rival the ACT.

These recommendations are supported by the growth of SAT participation in Illinois and Colorado. These states saw a sharp rise in SAT participation along with a decline in ACT participation. In other parts of the United States SAT participation remained mostly the same, with only a small decrease in most declining states. 

Participation percentage alone is not enough to determine the growth of the SAT. Full participation in very large states may be more valuable than full participation in several small states, but this does not mean that the College Board should write off smaller states. In places like Washington DC there may be an induced effect from market saturation. SAT participation in 2017 was at 100% in Washington DC but only 91% in 2018. Immediate action to reverse this decline may help to sustain the momentum the College Board is building in other parts of the country. 

Broadly speaking, the SAT appears to have constant growth across the United States with deep market penetration in some places, while the ACT has full participation in a greater number of states but less growth overall. This stagnation in ACT momentum may be leveraged as ACT Inc becomes complacent. My recommendations are that the College Board continue to develop a mindset for growth and publicize the participation of states like Illinois and Colorado, while investing new resources into Washington DC and similar states.

### Considerations for Future Analysis

The datasets used in this analysis included only data for the United States. Future analysis may seek to include the scores and participation percentages from students taking the SAT outside of the United States. More granular data on county and regional scores may also help to provide greater insight to the College Board as they look to increase participation. This is signifigant as the resources required to advertise in major metropolitan areas may be signifigantly different from that of rural or suburban areas.

### Source Documentation

- [About the College Board]()
- [Information on the SAT]()
- [Information on the ACT]()
- [SAT Score Adjustment]()