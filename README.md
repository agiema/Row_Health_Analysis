# Row Health Marketing Insights - Project Overview
## The goal of this project is to investigate the performance of marketing campaigns at Row Health in order to surface recommendations on marketing budget allocation across future campaign categories.
**Founded in 2016, Row Health is a medical insurance company serving over thousands of customers throughout the United States. In 2019, they launched a new set of marketing campaign categories** spanning topics like wellness tips, the affordability of their plans, and preventative care. Their customers can sign up for 4 different plans - bronze, silver, gold, and platinum - each with different premiums and claim coverage rates.

Now that they've hired a new data team and are strategizing their marketing budget for the year, the company would like to build more understanding of the effectiveness of these campaign categories and how they relate to signups and subsequent patient claims. The budget is allocated to drive two primary objectives: 1) to increase the number of customer signups, and 2) to increase exposure of Row Health's brand Across the country.

## Dataset Structure
The dataset consisted of three tables, including information about campaigns, signups and user demographics, as well as claims filed by customers and related claim information.

<img src="https://github.com/user-attachments/assets/5f6c4513-c9f1-4e58-a551-4e8db50ac6fd" alt="image" width="600" />

## Insights Summary
**The following North Star metrics were used to evaluate campaign performance:**
- **Signup Rate:** The percent of successful sign ups after a lead sees a campaign for a Row Health Plan
- **Cost per Signup:** The average dollar amount spent on each successful sign up from a campaign
- **Click Through Rate:** The percent of people who click on an affiliated link when they see a campaign

**Signup Rate**

- **Health For All campaigns had the best-performing signup rate (2.9%)** and second-highest number in signups (3.5K) across all campaigns.
- **High signup rate was mainly driven by the Health Awareness campaign type**, which had the highest signup rate across all campaign types (3.72%).
- **\#HealthyLiving - had comparably low signup rate of 0.3%** despite being the category with the highest number of signups.

**Click-Through Rate**

- **Health for All and Benefit Updates performed nearly 3-4x better** than the average CTR at 36% and 22%, respectively.
- **product-promotions based campaigns had relatively low CTR (0% and 7%)** within the top two categories by CTR.
- **Preventive Care News and #HealthyLiving performs the best in Clicks count** despite lower CTR.
- **Family coverage plan had high impressions but no clicks** - this needs to be investigated and could be due to missing data or issues with the campaign.

**Cost per Signup**

- **Golden year Security had the highest cost per signups ($124) compared to an average of $2.2, and has the lowest number of signups (23)** across campaign categories.
- **info-based campaign types (like offers and policy info) drive high costs per signup** within the two campaign categories with highest cost per signup.
- Several **COVID-based campaigns also had abnormally high CACs at $1.2k - $1.3k.**


## Recommendations

- **Health for All:** Reallocate budget from Golden Years Security, which has high cost per acquisition, to Health for All campaigns. Health for All campaigns outperform across all key metrics with only a low amount invested ($2031)
- **Health Awareness:** Within Health for All campaigns, focus on health awareness-type marketing rather than product-promotion type campaigns, which had low signup rate and CTR.
- **Covid Campaigns:** Investigate the cause of abnormally high cost per signup for COVID-based campaigns, which had 2 signups that costed over $1k, compared to an average signup cost of $2.2. Consider removing all these campaigns altogether.
- **\#HealthyLiving:** Decrease investment in this campaign category, which has the highest spend ($4k)

## Dashboard

The dashboard can be found in Tableau Public [here](http://public.tableau.com/views/RowHealthDashboard_17339846457110/CampaignCategoryDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link "here"). This dashboard enables users to filter by plan, campaign type, and state, and focuses on trends and values in marketing metrics, signup metrics, and claim metrics.

<img src="https://github.com/user-attachments/assets/593c21c4-3d3c-4aa7-af63-bb916af589f6" alt="image" width="1000" />

## Presentation Sample

The presentation created for the marketing team walks through the insights and recommendations above and can be found [here](https://docs.google.com/presentation/d/1rskf6xORlWtJLpmHAGgL_Jv-wRPi5TuyKffFnxjQGBw/edit?usp=sharing "here"). Some extracts are presented below for easy viewing.

<img src="https://github.com/user-attachments/assets/b2bf1a16-8172-439b-bc8d-a49ea87dda82" alt="image" width="700" />
<img src="https://github.com/user-attachments/assets/15583c6a-b5ec-4624-abd3-fa923cb4b638" alt="image" width="700" />
<img src="https://github.com/user-attachments/assets/3b78cfda-fb93-4d1e-b7c6-7d90ea6b8e81" alt="image" width="700" />
