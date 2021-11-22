# College, Tuition, Diversity, and Pay Project

![Snip20211103_4](https://user-images.githubusercontent.com/24769002/140181364-c7af523f-3287-40bd-91e6-b321aa2c6201.png)

Purpose
------------------------
The cost of pursuing a higher education in the United States is a contested topic of discussion. In a survey conducted by the University of California - Los Angeles, around 85% of newly enrolled freshman believed that enrolling in college would lead to obtaining a better job opportunity and about 72% cited that pursuing a higher education would lead to making more money (Kerr 2019). Whether we agree or disagree with these freshmen that pursuing a higher education is worth the cost, one thing that isn't disputed is the rising cost of attending these schools. Furthermore, to exacerbate the rising cost, there is also a diversity gap dilemma for minority students whom pursue a lesser quality of education which leads to a gap in career pay. In an analysis conducted by the Center of American Progress, federal data showed that “Black and Hispanic graduates also generally have attended institutions that have less money to spend on offering a quality education. And they are significantly underrepresented in important fields such as engineering and education, mathematics and statistics, and the physical sciences” (Libassi 2018). This leads us to further question and analyze college cost as whole whether it is worth paying more money for a good quality education. 

The purpose of this project is to examine several data sets from different colleges and universities that involve tuition, diversity, and pay. This project aims to highlight a social and economic issue that plays a role in the educational disparity in the United States. Using Postgresql and Tableau we will have an overlook view on tuition, diversity, and pay on the national. We will then narrow our focus on the state of Massachusetts and compare the tuition, diversity, and pay to the national level.

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

![Snip20211121_8](https://user-images.githubusercontent.com/24769002/142779596-031a6e56-ee6c-4ee7-b8bc-9ce94de55f2c.png)

![Snip20211121_9](https://user-images.githubusercontent.com/24769002/142779627-32ba1607-b412-4602-bc43-43c1d359e0d1.png)

![Snip20211121_10](https://user-images.githubusercontent.com/24769002/142779637-dfa3e4e6-73d9-459c-93b1-142f4770559f.png)

![Snip20211121_12](https://user-images.githubusercontent.com/24769002/142779662-f0924a2a-ad5b-4ef2-a032-337d26450e0b.png)

![Snip20211121_13](https://user-images.githubusercontent.com/24769002/142779685-d3862de8-ea74-4ed0-81aa-0b67522bfdbc.png)

![Snip20211121_14](https://user-images.githubusercontent.com/24769002/142779703-279353aa-6e16-4dc0-9edd-123fbf575d19.png)


Closing Remarks
------------------------

![Snip20211103_3](https://user-images.githubusercontent.com/24769002/140175367-2bb29903-54d6-4771-9aee-b1279b5cbf84.png)


References
------------------------
https://public.tableau.com/views/CollegesintheUS-AnalyzingTuitionDiversityandPay/TopCollegesinMassachusetts?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

Kerr, E. (2019, June 17). Is college worth the cost? . US News. Retrieved November 3, 2021, from https://www.usnews.com/education/best-colleges/paying-for-college/articles/2019-06-17/is-college-worth-the-cost. 

Libassi, C. J. (2018, May 23). The Neglected College Race Gap: Racial Disparities Among College Completers. Center for American Progress. Retrieved November 2, 2021, from https://www.americanprogress.org/issues/education-postsecondary/reports/2018/05/23/451186/neglected-college-race-gap-racial-disparities-among-college-completers/. 


