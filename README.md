# Tableau-Dashboard "C:\Users\hello\Desktop\data projects\Tableau\Graduate rate analytics.twb"
#Understanding College Graduation Outcomes Tableau Dashboard Prepared by Hildegarde Mukonyora  |  Prepared 19 August 2026 This dashboard examines what shapes how long students take to graduate and how well they perform once there. Across 1,000 students, college GPA is most strongly tied to admissions readiness.

Executive Summary
The Graduation Rate Analysis dashboard tracks student time-to-degree, parental background, income bracket, and academic performance across the surveyed cohort. Overall, on-time graduation stands at 43.9%, with an average of 4.98 years to graduate — indicating that a majority of students take longer than the standard four-year timeline. The dashboard's two strongest drivers of variation are household income bracket and parental level of education, both of which show a clear, consistent gradient against graduation outcomes.
Key Performance Indicators
ON-TIME GRAD RATE 43.9% of student cohort	
AVG YEARS TO GRADUATE 4.98 years	
AVG PARENTAL INCOME $67,378 USD, cohort avg	
AVG COLLEGE GPA 3,377 as reported*
Avg College GPA is displayed as reported by the dashboard's default aggregation (3,377); this figure should be reviewed against the underlying field, as it falls outside a typical 0-4.0 GPA scale and may reflect a SUM rather than AVG aggregation.
Findings by Dimension
Parental Education	Students whose parents completed 'some college' or 'high school' account for the largest share of years-to-graduate volume; the total falls steadily through associate's, bachelor's, and master's degree, where it is lowest.
Income Bracket	On-time graduation rate rises consistently with household income - from roughly 5% for Under $40K, to ~45% for $40K-70K, ~52% for $70K-100K, and ~62% for Over $100K.
SAT vs College GPA	The scatter view (filtered to two highlighted points) shows one case near an SAT total of ~1,100K-scale units with a higher GPA marker, and one lower-scoring case - too sparse on its own to establish a trend; a fuller unfiltered view is recommended. 
Detailed Analysis
1. Years to Graduate by Parental Education
The bar chart shows a clear downward gradient in time-to-graduate volume as parental education rises:
●	Some college and high school backgrounds show the highest years-to-graduate totals (~1,050-1,080).
●	Some high school and associate's degree fall in the middle band (~830-900).
●	Bachelor's degree and master's degree backgrounds show the lowest totals (~420-620), suggesting students from more highly educated households progress toward graduation faster on average.
2. On-Time Graduation Rate by Income Bracket
This is the dashboard's most pronounced trend. On-time graduation rate increases steadily with income bracket:
●	Under $40K: approximately 5% on-time rate — the lowest of any group.
●	$40K-70K: rises sharply to approximately 45%.
●	$70K-100K: approximately 52%.
●	Over $100K: the highest rate, at approximately 62%.
The gap between the lowest and highest income brackets (roughly 57 percentage points) is the single largest disparity visible on the dashboard, and points to income-linked barriers — financial aid gaps, work obligations, or resource access — as a priority area for intervention.
3. SAT Score vs College GPA
The scatter plot currently displays only two highlighted data points against SAT total score and College GPA axes. With so few points visible, no reliable correlation can be drawn from this view alone. Recommend confirming the filter/highlight state and reviewing the full unfiltered point cloud to assess the actual SAT-to-GPA relationship.
Recommendations
●	Prioritize on-time-completion support (financial aid, flexible scheduling, emergency funds) for students in the Under $40K and $40K-70K income brackets, where the largest gains are available.
●	Investigate the Avg College GPA aggregation to confirm whether the KPI is summing rather than averaging, and correct the calculated field if needed.
●	Clear or review active filters/highlights on the SAT vs College GPA scatter plot to restore a full view of the relationship between test performance and academic outcomes.
●	Consider a parental-education-by-income crosstab as a follow-up view, since both dimensions independently correlate with graduation timelines and may be compounding factors.
