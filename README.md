# party-analysis
This repository analyzes party affiliation shifts between Republican and Democrat voters in Florida using multiple snapshots of the voter file. Comparing voter registration changes over time identifies trends in partisan shifts and their potential impact on elections.


[View the Google Sheets table](https://Borism1434.github.io/party-analysis/Toplines.html)



# **2016 Florida Voter Registration by Race & Party Affiliation**

## **Overview**
This report analyzes **voter registration trends in Florida (2016)**, breaking down registration counts by **race and party affiliation**. It highlights partisan advantages and racial composition within each party.

---

## **Table Columns & Definitions**

| Column Name | Description |
|-------------|------------|
| **Race Description** | Racial or ethnic category of voters in the Florida voter file. |
| **Democrat Registration Count** | Total number of registered **Democratic voters** in each race group. |
| **Republican Registration Count** | Total number of registered **Republican voters** in each race group. |
| **Independent Registration Count** | Total number of voters registered as **No Party Affiliation (NPA)/Independent** in each race group. |
| **Democratic Advantage** | Difference between **Democratic and Republican** registrations for that race group. |
| **Share of Democrats** | Percentage of **all Democrats in Florida** who belong to this race category. |
| **Share of Republicans** | Percentage of **all Republicans in Florida** who belong to this race category. |
| **Share of Independents** | Percentage of **all Independents in Florida** who belong to this race category. |
| **Democratic Share Within Race** | Percentage of voters **within this race** who are **Democrats**. |
| **Republican Share Within Race** | Percentage of voters **within this race** who are **Republicans**. |
| **Dem -> Rep** | Number of voters registered as Democrats in 2016 and switched to the Republican Party by early 2024. |
| **Dem → Ind** | Number of voters who were registered as Democrats in 2016 and switched to No Party Affiliation (Independent) by early 2024.
| **Rep → Dem** | Number of voters who were registered as Republicans in 2016 and switched to the Democratic Party by early 2024.
| **Rep → Ind** | Number of voters who were registered as Republicans in 2016 and switched to No Party Affiliation (Independent) by early 2024.
| **Ind → Dem** | Number of voters who were registered as No Party Affiliation (Independent) in 2016 and switched to the Democratic Party by early 2024.
| **Ind → Rep** | Number of voters who were registered as No Party Affiliation (Independent) in 2016 and switched to the Republican Party by early 2024.
| **Share Dem -> Rep** | Percentage of all Democrats in Florida (as of 2016) who switched to the Republican Party and belong to this specific row category (e.g., race, county, or age group).
| **Share Dem -> Ind** | Percentage of all Democrats in Florida (as of 2016) who switched to No Party Affiliation (Independent) and belong to this specific row category (e.g., race, county, or age group).
| **Share Rep -> Dem** | Percentage of all Republicans in Florida (as of 2016) who switched to the Democratic Party and belong to this specific row category (e.g., race, county, or age group).

---

## **Understanding the 2016 Democratic Registration Edge**

## **2016 Voter Registration**
- Democratic registration advantage in 2016 relied heavily on Black voters, who made up 1,054,054 more Democrats than Hispanics, despite there being 302,144 more registered Hispanic voters overall. A closer look reveals that 650,825 Hispanic voters were registered as Independent, making up nearly the entire nonwhite Independent bloc. This positions Hispanic voters as a significant swing group with the potential to reshape electoral outcomes.
- The Republican Party’s largest and most reliable voter bloc in 2016 was White (Not Hispanic) voters, where they held a commanding registration advantage of 1,409,687 over Democrats—the only racial group where Democrats trailed significantly. While Democrats faced erosion among Hispanic voters, with 39.5% registering as Independents and only 35% as Democrats, Republicans maintained a stronghold among White voters, who registered 45.9% Republican compared to 28.9% Democrat and 26.7% Independent.

## **2024 Voter Registration**

- Despite an overall increase of 538,750 registered voters in Florida by early 2024, the Democratic Party experienced significant losses in affiliation across all major racial groups. Notably, there were 142,597 fewer Black voters registered as Democrats and 229,237 fewer Hispanic voters affiliated with the party compared to 2016. Native American voters shifted toward the Republican Party, resulting in a net Republican advantage of 3,579. While the decline in Democratic affiliation was observed across all racial categories, it was least pronounced among Black voters and most severe among Hispanic voters, signaling a substantial reshaping of Florida’s political landscape along racial lines.


## **Party Switch 2016 - 2024 By Race**			

| Voterfile Race Description           | Net Democratic Gain (or Loss) | Net Republican Gain (or Loss) | Net Independent Gain (or Loss) | Total  |
|-------------------------------------|-------------------------------|--------------------------------|--------------------------------|--------|
| American Indian or Alaskan Native   | -0.1%                         | 0.2%                           | -0.1%                          | 0.3%   |
| Asian Or Pacific Islander           | 1.2%                          | -0.5%                          | -0.7%                          | 1.8%   |
| Black; Not Hispanic                 | -6.4%                         | -1.6%                          | 8.0%                           | 9.1%   |
| Hispanic                            | -10.5%                        | 10.3%                          | 0.2%                           | 20.6%  |
| Multi-racial                        | 0.3%                          | -0.1%                          | -0.3%                          | 0.4%   |
| Other                               | -0.3%                         | -0.3%                          | 0.7%                           | 2.0%   |
| Unknown                             | 1.8%                          | -0.4%                          | -1.4%                          | 1.1%   |
| White; Not Hispanic                 | 13.8%                         | -7.5%                          | -6.3%                          | 64.7%  |
| Total                               | -12.6%                        | 17.6%                          | -5.0%                          | 100.0% |

- Hispanic voters demonstrated the sharpest partisan realignment, swinging substantially toward Republicans. With a 10.5% net loss for Democrats and a 10.3% net gain for Republicans, this shift—among a group representing over one-fifth of all switchers—underscores an alarming trend. In a state where Republicans already hold power at every level, this movement signals a deeper erosion that could reshape Florida’s political landscape for the next decade.
- The data reveals that Black (Not Hispanic) voters are increasingly aligning with no-party affiliation, posting an 8.0% net gain toward Independents and a 6.4% net loss for Democrats. While not yet a full partisan shift like among Hispanics, it suggests a growing detachment from traditional political alignments. If Black voters follow a similar path, it could dismantle one of the few remaining pillars of Democratic strength in Florida.




## **Party Switch 2016 - 2024 By Age **		

| Age Binds  | Share Dem → Rep | Share Dem → Ind | Share Rep → Dem | Share Rep → Ind | Share Ind → Dem | Share Ind → Rep | Total   |
|------------|------------------|------------------|------------------|------------------|------------------|------------------|---------|
| Age 18–24  | 0.0%             | 0.0%             | 0.0%             | 0.0%             | 0.0%             | 0.0%             | 0.0%    |
| Age 25–34  | 10.0%            | 22.3%            | 18.6%            | 19.0%            | 24.9%            | 16.1%            | 18.2%   |
| Age 35–49  | 22.7%            | 33.6%            | 19.4%            | 25.2%            | 27.4%            | 28.4%            | 26.8%   |
| Age 50–64  | 29.3%            | 24.1%            | 23.4%            | 27.5%            | 21.8%            | 28.6%            | 26.1%   |
| Age 65+    | 37.0%            | 19.5%            | 38.0%            | 27.5%            | 25.5%            | 26.1%            | 28.1%   |
| Unknown    | 1.0%             | 0.6%             | 0.6%             | 0.8%             | 0.4%             | 0.8%             | 0.7%    |
| **Total**  | **100.0%**       | **100.0%**       | **100.0%**       | **100.0%**       | **100.0%**       | **100.0%**       | **100.0%** |




## **Party Switch 2016 - 2024 By County**		


| County Code | Share Dem → Rep | Share Dem → Ind | Share Rep → Dem | Share Rep → Ind | Share Ind → Dem | Share Ind → Rep | Total   |
|-------------|------------------|------------------|------------------|------------------|------------------|------------------|---------|
| DAD         | 9.41%            | 12.47%           | 7.69%            | 8.42%            | 10.67%           | 10.57%           | 10.16%  |
| BRO         | 7.03%            | 13.18%           | 8.13%            | 7.66%            | 11.97%           | 6.53%            | 9.15%   |
| PAL         | 5.57%            | 7.63%            | 6.77%            | 6.81%            | 8.42%            | 6.42%            | 6.92%   |
| HIL         | 5.60%            | 6.97%            | 6.94%            | 6.55%            | 7.19%            | 5.71%            | 6.42%   |
| ORA         | 3.93%            | 8.02%            | 7.24%            | 6.26%            | 9.02%            | 4.55%            | 6.35%   |
| PIN         | 3.99%            | 4.06%            | 6.10%            | 5.34%            | 5.38%            | 4.66%            | 4.76%   |
| DUV         | 3.64%            | 4.37%            | 5.85%            | 5.20%            | 4.80%            | 3.70%            | 4.41%   |
| POL         | 4.13%            | 3.34%            | 2.72%            | 2.58%            | 3.10%            | 4.28%            | 3.49%   |
| BRE         | 3.21%            | 2.71%            | 3.62%            | 3.83%            | 2.75%            | 3.46%            | 3.21%   |
| VOL         | 3.25%            | 3.04%            | 2.70%            | 3.18%            | 2.81%            | 3.64%            | 3.15%   |
    



