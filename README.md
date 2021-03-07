# kickstarter-analysis

## Overview 

### Purpose

Louise started a project called _Fever_ and launched it on Kickstarter help gain funds. She almost reached her goal within a short duration, but fell short. She wants to know how did other plays that launched on Kickstarter fared. This report is to help her gain a better understanding on fundraising projects based on launch dates and their funding goals.

### Background

The data used was taken from Kickstarter, having projects launched as early as 2009 and as recent as 2017. The file itself is named **Kickstarter_Challenge.xlsx**, with the data being located in the *Kickstarter* sheet. Each project contaiins the following information:

* Blurb
* Primary and secondary categories
* Pledge goal and amount pledged
* Country of origin and currency
* Launch and deadline dates
* Staff pick and spotlight
* Number of backers and the average amount pledged

## Analysis & Challenges

### Analysis

#### Outcomes Based on Launch Date

A PivotTable was created to get the relevant information based on launch date. In **Kickstarter_Challenge.xlsx**, the first column contains all the months of the year, while the next columns are counts of "successful", "failed", and "canceled", within the *Kickstarter* sheet, with the final column being a total count of all projects within the month. The table has been filtered to theaters as the parent category, with an optional filter to compare the years. A line graph was used to visualize the given table, given (here)[./resources/Theater_Outcomes_vs_Launch.png].

In the image, the line graph shows that more projects are launched during May and June, and it also shows that the success rate is higher during those months, in terms of quantity and in percentage. On the other hand, the projects launched in December have similar success and failure rates.

#### Outcomes Based on Pledge Goals

A count was done based on conditions (outcomes, filtered to plays, and pledge goals), resulting in the sheet named _Outcomes Based on Goals_. Percentages were taken, based on success, failure, and cancellations, for each goal pledge range. A visual representation of the sheet is shown on a line graph, in the image file **Outcomes_vs_Goals.png**.

In **Outcomes_vs_Goals.png**, the success rate is more than the failure rate when the pledge goal is at most $15,000.00, with both rates being equal at the $15,000.00-$19,999.99 range. The success rate is also more than the failure rate when the pledge goal is within $35,000.00-$44999.99, but otherwise the failure rate is at a higher percentage when the pledge goal is at least $20,000.00.

## Conclusion

If Louise was interested in launching a new project on Kickstarter, more specifically another play, she should consider launching the project in May or June. If neither of those months are possible, then it would be in her best interest to avoid trying to launch the project in December. If she wants to make a pledge goal, it would be more realistic to have a pledge goal of at most $20,000.00. There aren't as many projects launched with pledge goals above $15,000.00, which leads to misleading information, such as the success rate of projects with a pledge goal in the $35,000.00-$45,000.00 range.
