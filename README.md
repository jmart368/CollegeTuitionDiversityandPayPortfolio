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

<div class='tableauPlaceholder' id='viz1637527824201' style='position: relative'><noscript><a href='#'><img alt='National Tuition Averages ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Co&#47;CollegesintheUS-AnalyzingTuitionDiversityandPay&#47;NationalTuitionAverages&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='CollegesintheUS-AnalyzingTuitionDiversityandPay&#47;NationalTuitionAverages' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Co&#47;CollegesintheUS-AnalyzingTuitionDiversityandPay&#47;NationalTuitionAverages&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1637527824201');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='827px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>



Closing Remarks
------------------------

![Snip20211103_3](https://user-images.githubusercontent.com/24769002/140175367-2bb29903-54d6-4771-9aee-b1279b5cbf84.png)


References
------------------------
Kerr, E. (2019, June 17). Is college worth the cost? . US News. Retrieved November 3, 2021, from https://www.usnews.com/education/best-colleges/paying-for-college/articles/2019-06-17/is-college-worth-the-cost. 

Libassi, C. J. (2018, May 23). The Neglected College Race Gap: Racial Disparities Among College Completers. Center for American Progress. Retrieved November 2, 2021, from https://www.americanprogress.org/issues/education-postsecondary/reports/2018/05/23/451186/neglected-college-race-gap-racial-disparities-among-college-completers/. 


