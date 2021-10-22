# School District Analysis

## Overview

An analysis was performed for a school district looking at standardized testing scores for both reading and math, along with district funding metrics. The testing scores and funding metrics data was summarized by school, grade, spending ranges, school size, and school type.  Once the analysis was complete the school district suspected academic dishonesty regarding the math and reading scores for the ninth grade at Thomas High School.  The original analysis was then modified to change all reading and math scores for the Thomas High School ninth grade class to NaN's, and all summaries were recreated taking this change into account.

## Results

Due to the changes being limited to one grade at one high school, the summaries only saw slight changes, some of which, could be lost in rounding.

- On the District Summary the average math score went down by less than a whole point, and the three % passing metrics each went down by less than 1%.
  - Original District Summary:
![Original_District_Summary](https://user-images.githubusercontent.com/90863226/137644527-edd61ac4-4e98-4918-90be-51fc6bd961b2.png)

  - Updated District Summary:
![New_District_Summary](https://user-images.githubusercontent.com/90863226/137644530-712a6416-ced5-45b6-9d14-67d67cc5ff8f.png)

- Thomas High School was the only change to the School Summary
  - Original School Summary:
![Original_School_Summary](https://user-images.githubusercontent.com/90863226/137649574-d5b8f890-2320-4dc7-bc33-189ea3c5d37e.png)

  - Updated line for Thomas High School:
![New_THS_School_Summary](https://user-images.githubusercontent.com/90863226/137649646-12000e03-1f63-405b-9217-2cc4d9d31e42.png)

- Replacing the ninth grade math and reading scores did not even change Thomas High School's place in the school rankings, when sorted by the Overall Passing %. The score came down by less than a percentage which was not enough to lower them out of the 2nd highest performing school rank, as seen in the screenshots below.
  - Original Top 5 Highest Performing Schools:
![Original_Top_5_Performing_Schools](https://user-images.githubusercontent.com/90863226/137644303-c670bbec-6565-429f-88a4-46536769eb3a.png)

  - Updated Top 5 Highest Performing Schools:
![New_Top_5_Performing_Schools](https://user-images.githubusercontent.com/90863226/137644321-4279b917-7880-4547-9922-c42c2c335d2e.png)

- On the math and reading scores by grade you can see the NaN's that replaced the Thomas High School ninth grade scores
  - Math Scores by Grade:

  ![New_Math_Scores_by_Grade](https://user-images.githubusercontent.com/90863226/138485476-d3a523fe-590f-4e33-9855-82b71d668ec1.png)

  - Reading Scores by Grade:

  ![New_Reading_Scores_by_Grade](https://user-images.githubusercontent.com/90863226/138485725-babda879-b4ba-4bff-9aa1-3f383aa25639.png)

  
- The changes to the Scores by School Spending, Scores by School Size and Scores by School Type were all so miniscule that they did not change any of the analysis visualizations

![New_Scores_by_School_Spending](https://user-images.githubusercontent.com/90863226/138486518-98f0931a-d3de-4f0e-85bd-59af42263a8a.png)

![New_Scores_by_School_Size](https://user-images.githubusercontent.com/90863226/138486481-efe9b059-59a1-413b-9fdf-5a0e56459e21.png)

![New_Scores_by_School_Type](https://user-images.githubusercontent.com/90863226/138486494-24755009-50a6-48c9-b1a6-e7f1acb2a71d.png)


## Summary

Changing the ninth grade scores at Thomas High School to NaNs, did not have an overall grand impact to the school analysis that had been performed.  It was really only seen on those visualizations that included scores broken down by school and/or grade, and on the high level summaries where the decimal point was showing, as the change was less than a percent. The impact of the change was seen in the following visualizations:
1. District Summary
2. School Summary
3. Top 5 Highest Performing Schools
4. Math & Reading Scores by grade
