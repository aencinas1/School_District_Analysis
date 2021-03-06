# An Analysis of School District Data: Determination of Scores, Budgets, and Outcomes
Upon working with Maria on the provided school district data, she was informed that the math and reading scores of ninth graders from Thomas High School were entered inaccurately. As a result of the discovery, we needed to exclude ninth graders from Thomas High School from our analysis as to not influence data accuracy. After they are successfully removed, we re-ran all calculations to get an analysis that was not wrongly influenced.

## The Results
![](Resources/district_before.PNG)
![](Resources/district_after.PNG)
![](Resources/ths_before.PNG)
![](Resources/ths_after.PNG)

The removal of the false data certainly impacted district results, but the impact is also noticable on THS data as a whole.
- The Budget and the Total Students of THS and the district did not change.
- The district numbers were influenced by the false data. From the first picture (before the exclusion) you can see that the Average Math score was 0.1 higher than when the false data was removed. % Passing Math was also 0.2 higher than it should have been. The % Passing Reading was 0.3 higher than it should have been, and % Overall Passing was 0.1 higher than it should have been. Clearly, district data was influenced by incorrect data, giving higher than realistic scores.
- Thomas High School data was also influenced. From the third picture (before exclustion), Average Math scores were 0.068 higher than they should have been; Average Reading scores were 0.048 lower than they should have been; % Passing Math was 0.087 higher than is should have been; % Passing Reading was 0.29 higher than it should have been; % Overall Passing was 0.318 higher than it should have been.
- Overall, the impact is not significant enough to catapult THS into the top performing school spot, but it does impact the district data as a whole.
- Replacing the ninth graders:
  - Did not impact other grade math and reading scores, although it did impact ninth grade scores since many were excluded.
  - With the ninth graders removed, school spending went up per student. It is not realistic to think this is actually the case, but if they were hypothetically removed from school budget, spending would increase (see picture three and four)
  - Score by school size (THS is medium) went down by 0.1
  - Score by school type saw the "charter" type score drop by .04

## The Summary
In summary, with THS ninth grader's scores adjusted to NaN, four distinct changed occured at a district level:
- Average Math Score dropped by 0.1
- % Passing Math Score dropped by 0.2
- % Passing Reading Score dropped by 0.3
- % Overall Passing Score dropped by .01

Overall, the district made the right call to exclude the false data, but preserve all other data to get the most accurate analysis for both THS and the district. While these percentages may look small, they will play a big part in the continued support in ensuring student success across the district.


