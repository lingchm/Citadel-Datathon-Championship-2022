# Citadel Data Open Championship 

The Citadel Data Open is a global competition series for data scientists. This year, over 30,000 students from more than a dozen countries took part in 11 regional events, the winners of each regional event were invited to participate in the Data Open Championship. 21 teams made it to the final event. 

This repo is our submission for the 2022 Data Open Championship. We were given `26 longitudinal datasets` about U.S. postsecondary education, collected by National Center for Education Statistics (NCES) and offered through [IPEDS](https://nces.ed.gov/ipeds/use-the-data). We were given `four days` to pose a novel research question and answer it using statistical analysis. 

When reading about postsecondary education, we came across some stunning statistics ([ref](https://www.forbes.com/sites/markkantrowitz/2021/11/18/shocking-statistics-about-college-graduation-rates/?sh=5cd1b5b62b69)):

> "39 million Americans hold some postsecondary education or training without completion.

> "About one out of three students drop out from college in the US, and two out of five were due to financial issues". 

> "Students who drop-out of college are almost 100 times more likely to default on their student loans, end up with debt and no degree"

Given the relevance of this problem, we decided to look into how financials impact completion. We propose the following questions:

* What are recent trends in institutional expenses and attendance costs?

* How have the changes in institutional financials and attendance costs impacted
post-secondary education completion, especially the underrepresented communities?


Our full report is summarized in `report.pdf`. In Part I, we analyzed the annual trends of institutional expenses, cost of attendance, and financial aid over 2015-2021 across all degree-offering post-secondary institutions in the United States, and compare these trends for public vs private for-profit vs private non-profit institutions. In Part II, we identified which institutional expenses and costs have statistically significant impact on degree completion for different student subpopulations. In Part III, we use machine learning to model the complex interrelationships of different datasets and to predict completion, and identify key predictors. We hope this analysis reveals some short-term impacts of institutions' cost allocation on completion rates and provide insights for future allocation.
