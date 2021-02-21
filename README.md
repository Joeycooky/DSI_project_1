# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Test Analysis

### Executive Summary


### Problem Statement

After leading the standardized test market for long times, SAT have lost its competitiveness and finally lose its position to ACT in 2012.

<h5>“ This project aims to explore trends in SAT and ACT participation across different states in the US and seeks to identify significant factors contributing to the participation rate to find appropriate strategies to regain SAT position to be the market leader again ”</h5>



### Data Dictionary

| Feature                     | Type   | Dataset    | Description                                                                             |
|-----------------------------|--------|------------|-----------------------------------------------------------------------------------------|
| state                       | object | sat_2017   | State name                                                                              |
| Abb                       | object | US Census   | State abbreviation                                                                              |
| 2017_SAT                    | float  | sat_2017   | SAT participation rate of each state in 2017                                            |
| 2018_SAT                    | float  | sat_2018   | SAT participation rate of each state in 2018                                            |
| 2019_SAT                    | float  | sat_2019   | SAT participation rate of each state in 2019                                            |
| 2017_ACT                    | float  | act_2017   | ACT participation rate of each state in 2017                                            |
| 2018_ACT                    | float  | act_2018   | ACT participation rate of each state in 2018                                            |
| 2019_ACT                    | float  | act_2019   | ACT participation rate of each state in 2019                                            |
| SAT_change_pct              | float  | calculated | %Change of SAT participation rate from 2017-2019                                        |
| ACT_change_pct              | float  | calculated | %Change of ACT participation rate from 2017-2019                                        |
| population_estimates        | float  | US Cencus  | Estimated population of each state in 2019                                              |
| under_18_pct                | float  | US Cencus  | %of population under 18 years old                                                       |
| white_pct                   | float  | US Cencus  | %of white population                                                                    |
| black_pct                   | float  | US Cencus  | %of black (African American) population                                                 |
| american_pct                | float  | US Cencus  | %of native american (Indian) population                                                 |
| asian_pct                   | float  | US Cencus  | %of Asian population                                                                    |
| owner-occupied_housing_rate | float  | US Cencus  | %of owner-occupied housing unit                                                         |
| persons_per_household       | float  | US Cencus  | number of person per household                                                          |
| living_in_same_house_1y+    | float  | US Cencus  | %of population living in same household over 1 years (can reflect the immigration rate) |
| households_with_computer    | float  | US Cencus  | %household with computer                                                                |
| households_with_internet    | float  | US Cencus  | %household with broadband internet                                                      |
| bachelor_or_higer_pct       | float  | US Cencus  | %of bachelor graduated population                                                       |
| travel_time_to_work         | float  | US Cencus  | mean time required to travel to work in minutes                                         |
| household_income            | float  | US Cencus  | median household income                                                                 |
| poverty_pct                 | float  | US Cencus  | %of poverty population                                                                  |
| employment_change_pct       | float  | US Cencus  | %of employment rate change from 2018-2019                                               |
| population_persqmile        | float  | US Cencus  | population density in term of person per squaremiles                                    |

---

### Executive Summary

img1_dominant state

Generally, students took the standardized test at the state where they lived -- the SAT is strongest on the coasts and the ACT in the Midwest and the South. Nevertheless, there are some relevant factors affecting the participation rate of SAT.

img2_significant Change

Entering into testing contracts with states education department seems to be best short-term strategy, since it can immediately boost the numbers of test taker. However it might not be a sustainable solution

img3_income
Income of the family might be the biggest barrier preventing high school graduate from taking SAT; therefore, to gain SAT popularity back, we should provide a fee waiver/ financial aids and a free subscription to preparation courses to student with financial hardship

img4_com
Presently, SAT is too conservative and still relies on paper-based test. It would be great if SAT can deploys computer-based test in the future, since majority of SAT takers were already have access to the facilities.
For lower median household income states, College Board should consider arranging a computer delivery test in addition to the regularly arranged SAT School day.



### Conclusion and Recommendation

Several factors affecting SAT participation rate was discovered and discussed. While some of them required further study, there are some quick-win strategies that could be implemented to boost the participation rate

- Establish an agreement with Department of Education of each states could be the most effective short term strategies
- Provide a fee waiver/ financial aids and/or a free subscription to preparation courses to students with financial hardship
- Develop computer delivery test to accommodate for the restriction due to COVID-19,  and increase accessibility in some states with minimal number of test center
- Arrange a computer-based test in addition to the regularly organized SAT School day
- Sponsor the scholarships to promote aspiration for higher education (either directly finance the scholarship or via partnership with other institutions)
