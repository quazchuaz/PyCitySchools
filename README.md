# PyCitySchools
## Analysis of school district data with Pandas

Examination of the data concerning the schools in the district has yielded some interesting results. Some of our key findings relate to the characteristics of the top 5 and bottom 5 schools in the district, the variation of passing scores for maths in particular across schools, and the impact of size and spending effects.

One key differentiating factor between the top 5 and bottom 5 schools in the district is the fact that all the top performing institutions are Charter Schools while the bottom 5 are District schools. Performance here is determined by the Overall Passing Percentage of students which accounts for both reading and maths scores. Drilling down into the data reveals that this is mostly driven by maths scores as even the lowest performing schools have relatively high percentages of their student populations passing reading, with figures of 80% to 81% of students passing. In contrast, the percentage of students passing maths in lower performing institutions is much lower at 65% to 66% relative to 93% to 95% for high performing schools. It should also be noted that the variation of student performance across grades within the same school is negligible, with differences usually within a 1% range.

Size and budget / spending effects were also examined. Surprisingly, the budget spent per student does not appear to be a predictor of success at all; as a matter of fact, the overall passing percentage of students is the highest for the lowest spending range in our dataset at 90.37%, and lowest for our highest spending range. However, school size does appear to have a marked effect on performance with small to medium sized schools significantly outperforming large institutions. The former have an overall passing rate of roughly 90% relative to large schools which have an associated overall passing percentage of approximately 58%.

In conclusion, a major difference between high and low performing schools is correlated with whether the school in question is a District or Charter School, with differences between the two being mainly driven by the percentage of students passing maths. In addition, while spending does not seem at first glance to be a predictor of success, school size does seem to have a significant impact.
