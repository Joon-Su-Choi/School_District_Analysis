# School District Analysis

## Table of Contents

#### 1. Overview of the School District Analysis
- Purpose
#### 2. Results
- How is the district summary affected?
- How is the school summary affected?
- How does replacing the ninth graders' math and reading scores affect Thomas High School's Performance relative to the other schools?
- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
  - Scores by school spending
  - Scores by school size
  - Scores by school type
#### 3. Summary
- Four changes in the updated school district

#### 1. Overview of the School District Analysis

 Purpose

  The school board notified Maria and her supervisor that there is evidence of academic dishonesty amongst the ninth graders in Thomas High School in regards to their reading and math grades being altered. Our goal is to replace their grades with NaNs while keeping the rest of the data intact and to run this modified data again to see how these changes affected the overall analysis.
  
#### 2. Results

How is the district summary affected?

  We see through our code that there is a total of 39,170 students amongst the district and there were 461 students from the ninth grade who attend Thomas High School that we will omit from the analysis, which leaves us with 38,709 students. Even with the omitted students, the amount of students in the district is still quite large so there was little change to average in their math and reading grade analysis.
![district_summary](https://user-images.githubusercontent.com/95505596/150656582-b03dead4-0ef2-438c-bb43-757b6ac0ef4a.png)

How is the school summary affected?

  As opposed to the district summary, there is a stark difference in the school summary due to there being a smaller sample size. There is originally 1,635 students who attend Thomas High School and now we are taking away 461 of them out of the analysis. This caused a much bigger discrepancy as we can see by the % passing math, % passing reading, and % overall passing.
![overall_thomas_grades](https://user-images.githubusercontent.com/95505596/150657376-331ecfe4-95b4-44e0-aaf3-de409b799475.png) (Grade 9 to 12 shown above)
![updated_overall_thomas_grades](https://user-images.githubusercontent.com/95505596/150657431-1592753c-b721-4a58-9d79-6f9e5ed16b13.png) (Grade 10 to 12 shown above)

How does replacing the ninth graders' math and reading scores affect Thomas High School's Performance relative to the other schools?

  As we replace the Thomas High School ninth graders' math and reading scores with NaNs we can see that the % passing math, % passing reading, and % overall passing are much higher. Thomas High School in comparison to the other schools was hovering over the bottom in terms of performance but now they have the second highest overall passing percentage.
![high_performing_schools](https://user-images.githubusercontent.com/95505596/150657874-3ea94656-2f1c-4bdd-a62e-a118efc29c9a.png)

How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade
  - Only the ninth grade math and rearding scores were affected. The average scores for ninth graders in Thomas High School were 83.728850 for reading and 83.590022 for math. The average of all the ninth grade scores went down since we are omitting the scores from the Thomas High School ninth graders.
  - First image is the Math Scores. Second image is the Reading Scores.

![overall_math_grades](https://user-images.githubusercontent.com/95505596/150659394-dd4e295c-32be-4218-86e0-9a337044f4ba.png)

![overall_reading_scores](https://user-images.githubusercontent.com/95505596/150659424-96540d55-4d29-4909-a407-8f5ffd4e6483.png)

- Scores by spending range
  - As we can see from the pictures below there is a slight change in the scores in the $630-644 range. This change was not visible when we rounded the numbers because of it's slight change.
  - First image includes the ninth graders in Thomas High School. The second image does not.

![spending_summary_before](https://user-images.githubusercontent.com/95505596/150659644-354900ac-8339-4ae9-825b-a93b4568352c.png)
  
![spending_summary_after](https://user-images.githubusercontent.com/95505596/150659610-6b19a26c-4421-4a54-a2dd-0b24d2c60f3a.png)

- Scores by school size
  - As we can see from the pictures below there is a slight change in the scores in the Medium school size range. This change was not visible when we rounded the numbers because of it's slight change.
  - First image includes the ninth graders in Thomas High School. The second image does not.
  
![school_size_before](https://user-images.githubusercontent.com/95505596/150659908-c61e72e8-5294-40f6-9234-c7cd0545f509.png) 

![school_size_after](https://user-images.githubusercontent.com/95505596/150659938-9b64e753-87a1-461b-b89b-eeece18b0cb2.png) 

- Scores by school type
  - As we can see from the pictures below there is a slight change in the scores under the charter category. This change was not visible when we rounded the numbers because of it's slight change.
  - First image includes the ninth graders in Thomas High School. The second image does not.

![school_type_before](https://user-images.githubusercontent.com/95505596/150660185-9d55eb65-8bce-4482-b3e9-6beb41a72be4.png)

![school_type_after](https://user-images.githubusercontent.com/95505596/150660213-cab79b1d-3c32-4707-a8aa-ba9bb18b6491.png)

#### 3. Summary

Four changes in the updated school district

- When we took out the ninth graders scores in Thomas High School we noticed a couple of changes. Within Thomas High School, the percentage of students that passed math, reading, and overall were all incresed significantly. This brought Thomas High School to the second highest overall passing percentage in the whole district.
- Thomas High School also affected the average in scores to ninth graders across the district. Their score average in math and reading were on the higher end across the ninth graders in the district so when omitting their scores the average scores of the ninth graders in the district has dropped.
- Thomas High School was in the category of student spending range of $630-644 and a medium school size. In the updated school district analysis we see the percentage of students passing math, reading, and overall has dropped by a small percentage. We initially formatted the data to a more rounded number but this made it harder to see the difference in the analysis so we went back to see the changes.
- If we were comparing the types of schools then district schools' average was not affected. However, Thomas High School is a charter type school so it did have an affect on those. The passing percentage of students who attended charter schools has decreased slightly.
