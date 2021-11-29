# College, Tuition, Diversity, and Pay Project

![Snip20211103_4](https://user-images.githubusercontent.com/24769002/140181364-c7af523f-3287-40bd-91e6-b321aa2c6201.png)

Purpose
------------------------

In an analysis conducted by the Center of American Progress, federal data showed that “Black and Hispanic graduates also generally have attended institutions that have less money to spend on offering a quality education. And they are significantly underrepresented in important fields such as engineering and education, mathematics and statistics, and the physical sciences” (Libassi 2018).The purpose of this project is to examine several data sets from different colleges and universities that involve tuition, diversity, and pay. This project aims to highlight a social and economic issue that plays a role in the educational disparity in the United States. Policy makers, inbound college students, parents, and school administrators, and advocates interested in promoting diversit would benefit from this insight as it aims to uncover the adress an overall issue of pursuing a higher education in the United States. 

Datasets
------------------------
We are given and used the following datasets to explore.

* **tuition_cost.csv** - Tuition and fees by college/university for 2018-2019, along with school type, degree length, state, in-state vs out-of-state.
* **salary_potential.csv** - Salary potential data from each school.
* **diversity_school.csv** - Diversity by college/university along with school type, degree length, state, in-state vs out-of-state.

Feature Definitions
------------------------
* **name** - School name
* **total_enrollment** - Total enrollment of students
* **state_name** - State name
* **state_code** - State abbreviation
* **category** - Group/Racial/Gender category
* **enrollment** - enrollment number by category
* **rank** - Potential salary rank for each school per state
* **early_career_pay** - Estimated early career pay in USD
* **mid_career_pay** - Estimated mid career pay in USD
* **make_world_better_percent** - Percent of alumni who think they are making the world a better place
* **stem_percent** - Percent of student body in STEM
* **type** - Public, private, for-profit
* **degree_length** - 4 year or 2 year degree
* **room_and_board** - Room and board cost in USD
* **in_state_tuition** - Tuition for in-state residents in USD
* **in_state_total** - Total cost for in-state residents in USD (sum of room and board + in-state tuition)
* **out_of_state_tuition** - Tuition for out-of-state residents in USD
* **out_of_state_total** - Total cost for out-of-state residents in USD (sum of room and board + out-of_state tuition)


Exploring our Data
------------------------

In order to understand what the bigger picture of colleges/universities looks like in the United States, we need to look at the overall scope of our data. Using SQL to clean, structure, and combine our data sets, we want to extract several visualizations that will give us an idea on where the most diverse colleges are located, which state has the highest/lowest salary, and which states have the most expensive tuition rates including room and board.

### Colleges in the US

![Snip20211121_8](https://user-images.githubusercontent.com/24769002/142779596-031a6e56-ee6c-4ee7-b8bc-9ce94de55f2c.png)

When we compare all 50 states, we can see that the state of Hawaii has the most diverse student pupolation enrolled at 63.59%. This means that out of all the schools in the state of Hawaii which can either be public, private, or for profit, Hawaii would have the most diverse percentage enrollment in student population throughout all of it's schools. This would inlude all African Americans, Natives, Hispanics, Asians, and Women and exclude international students. The total diversity percentage was calculated by taking the diversity_school enrollment divided by the diversity_school total_enrollment multiplied by 100 which would render us as the total percentage of enrolled minority students. Per our data, Hawaii seemed to be most diverse in comparison to the rest of the 49 states.

![Snip20211121_9](https://user-images.githubusercontent.com/24769002/142779627-32ba1607-b412-4602-bc43-43c1d359e0d1.png)

When we look at median salary, there are two factors that we need observe: Early Career Pay and Mid Career Pay. For salary, using the median would be an appropriate measure of statistic instead of using the mean. Since we have outliers in our data, using the mean would allow our outliers to dominate the data and therefore giving us an inaccurate early or mid career pay. Therefore the Median was used as an indication of which state has the highest early and mid career salary. For both entry level and mid career pay, the state of New York would dominate with an entry level median salary of $64,000 and a mid-career salary of $125,700. New York would also have the highest percentage of students enrolled in a STEM related field but yet the state wouls still have one the lowest enrollment populations of diverse students at a total of 34.15%. This in comparison to Hawaii shows that New York is not as diverse for enrolled students. However, attending one do their schools would allow graduates to earn the most. 

![Snip20211121_10](https://user-images.githubusercontent.com/24769002/142779637-dfa3e4e6-73d9-459c-93b1-142f4770559f.png)

Overall we can see that the 3 most expensive states to enroll in a college or university are Rhode Island, Vermont, Massachusetts.

![Snip20211121_12](https://user-images.githubusercontent.com/24769002/142779662-f0924a2a-ad5b-4ef2-a032-337d26450e0b.png)

### Colleges in the Massachusetts

|avg_room_and_board|avg_in_state_tuition|avg_out_state_tuition|
|---|---|---|
|5697.48|8964.69|17725.45|

![Snip20211121_13](https://user-images.githubusercontent.com/24769002/142779685-d3862de8-ea74-4ed0-81aa-0b67522bfdbc.png)

![Snip20211121_14](https://user-images.githubusercontent.com/24769002/142779703-279353aa-6e16-4dc0-9edd-123fbf575d19.png)


Closing Remarks
------------------------

![Snip20211103_3](https://user-images.githubusercontent.com/24769002/140175367-2bb29903-54d6-4771-9aee-b1279b5cbf84.png)


References
------------------------
https://public.tableau.com/views/CollegesintheUS-AnalyzingTuitionDiversityandPay/TopCollegesinMassachusetts?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link


Libassi, C. J. (2018, May 23). The Neglected College Race Gap: Racial Disparities Among College Completers. Center for American Progress. Retrieved November 2, 2021, from https://www.americanprogress.org/issues/education-postsecondary/reports/2018/05/23/451186/neglected-college-race-gap-racial-disparities-among-college-completers/. 


