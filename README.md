# School District Analysis

## Overview and Purpose

The School District Analysis was a project where I extensively used Pandas library to 
organize school district data across 15 different high schools, teaching nearly 40,000 students,
in order to reveal patterns across standardized test performance. We looked at this data in many
different ways; from the angle of how budgeting may have affected scores, or school population,
or whether the school type made a difference. All of this was gathered to help Maria, a chief data 
scientist for the district, to present these findings to the school board so they could make better informed
decisions as to where to allocate resources for the upcoming year. 

The challenge portion of this module, was to re-evaluate Thomas High School's test score performance without the ninth grade
test scores, to see if there was much difference to support suspicions of academic dishonesty. In the second analysis, we 
replaced the ninth grade scores with NaN in order to remove them from the analysis.
Let's take a look at what we found...

## Results

### District Summary With and Without 9th graders

With 9th Graders
![district_summary](https://github.com/lindsera1/School_District_Analysis/blob/master/Resources/district_summary.png)

Without 9th Graders
![district_summary_minus9th](https://github.com/lindsera1/School_District_Analysis/blob/master/Resources/updated_district_without_ninth.png)

Since the district analysis covered an enormous base of students, if there was academic dishonesty, removing ninth grade scores would have very
little impact on the outcome of the district analysis. However, there was hardly any deviation between the two. No red flags to be raised here!

### School Summary With and Without 9th graders


Without 9th Graders
![per_school_summary_minus9th](https://github.com/lindsera1/School_District_Analysis/blob/master/Resources/per_school_summary_minus9th.png)

With 9th Graders
![per_school_summary](https://github.com/lindsera1/School_District_Analysis/blob/master/Resources/per_school_summary.png)

Based on both of these images, we can also see there was very little, if any, deviation in the percentage passing for math, reading, and overall, which raises no red flags as well. 



### Thomas High School Compared To Other Schools

Thomas High School was ranked #2 in both analyses; meaning regardless of whether the ninth gradres were there or not,
in terms of overall passing performance, the rankings were consitent. As a matter of fact, passing percentages for the high school
differened only by about half a percent or less. Earlier in our PyCitySchools analysis, we saw that Charter schools, and those schools
with a smaller population tend to perform at the top of the district, and the demographics of Thomas High School reflect that.

-Scores By Grade: 

  There was a consitent 84 0r 85 percent passing rate for all grade levels across Thomas High School.

-Scores By Spending

  One statistic that was interesting, was that schools which received less overall spending, actuall performed better than those
  that received more funding. One can only ponder the reasons why; whether it be that small population schools or charter schools
  just recieve less funding, or the district directs less resources to those schools that are performing well, I don't think we can say that 
  giving a school less money will make the school perform better.

-Scores By Size

  In size, we see the same trend, where larger schools tend to perform worse than schools with less students. An obvious reason could simply
  be the student to faculty ration; more one on one time with students can easily explain higher performance metrics. Another reason could
  also be competitiveness; schools with a lower population perhaps accept only higher caliber students. 

-Scores By Type

  Charter schools edge out district schools in performance metrics, with about a 30 percent higher overall passing rate for reading and math
  scores. What is also interesting, is that average reading and math scores don't differ to much; just the percent passing. This could indicate
  a large talent gap, with 50/50 high and lower performing students, whereas in charter schools we may see consistently higher performance
  across the board. 
  
 ## Summary
 
  Based on the evidence, we cannot conclude outright that any academic dishonesty occured; there's no siginicant difference in the presence
  or abscence of the ninth graders in the data set; it's vaguely affected. This is good news for the district!

