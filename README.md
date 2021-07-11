# school_district_analysis

## Overview of Analysis

The school board has been notified that the nonth grade math and reading scores from Thomas High School Have been altered. For this analysis, we will be removing these altered grades from the data set to re-evaluate the results of the original analysis. The goal of this will be to provide any changed results after removing these grades from the district analysis.

## Results

**This analysis provides results to the following queries:**

### How is the district summary affected?

The district summary was slightly lowered when the altered grades were removed. When these grades were removed, the overall passing percentage went down by 0.3%, and the math and reading score also went down by 0.1-0.2%.

###### Original District Summary

![Image1](/Resources/District_Summary_Original.PNG)

###### Revised District Summary

![Image2](/Resources/District_Summary_Challenge.PNG)

### How is the school summary affected

The school summary chart was only changed in the row providing information regarding Thomas High School. As you can see below, their passing percentages in terms of math, reading, and overall passing fell by 0.1-0.3% in each area.

###### Original School Summary

![Image3](/Resources/School_Summary_Original.PNG)

###### Revised School Summary

![Image4](/Resources/School_Summary_Challenge.PNG)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Thomas High Schools relative performance to other schools were mostly unchanged after removing their ninth graders math and reading scores. They remained to be second in the district by overall passing percentage.

###### Original Top 5 Schools

![Image5](/Resources/Top_Schools_Original.PNG)

###### Revised Top 5 Schools

![Image6](/Resources/Top_Schools_Challenge.PNG)

### How does replacing the ninth-grade scores affect the following:

    - *Math and reading scores by grade*
    The only change here was that the 9th grade scores for Thomas High School were turned to nan due to their removal.
    
    - *Scores by school spending*
    Thomas High School is in the $630-644 spending bin, and there wasn't really any changes greater than 0.1% to any area of the chart. The change was a decrease just like the other criteria, but the decrease was far less drastic and not shown after the formatting of the chart.
    
    - *Scores by school size*
    Thomas High School is in the Medium (1000-2000) size bin, and there wasn't really any changes greater than 0.1% to any area of the chart. The change was a decrease just like the other criteria, but the decrease was far less drastic and not shown after the formatting of the chart.
    
    - *Scores by school type*
    Thomas High School is a charter school, and there wasn't really any changes greater than 0.1% to any area of the chart. The change was a decrease just like the other criteria, but the decrease was far less drastic and not shown after the formatting of the chart.

## Summary

After the district analysis was performed with the removal of the ninth graders scores from Thomas High School, it was clear that there was an overall decrease in the district scores considering the scores removed had a mean above the population mean. In the summary, the four biggest changes providing greater than a 0.1% difference in the results were:

- Average Math Score

- Percent Passing Math

- Percent Passing Reading

- Overall Passing Percentage

These changes can be seen in the district summary images in the results section.



