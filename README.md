# matplotlib_hw

Table of contents
- Project Overview
- Observation Write Up
- Charts

Project Overview

In this project, I was tasked with examining the data from an animal study where 248 mice with SCC tumor growth were treated with a variety of drug regimens. These treatments were administered for 45 days and during that time tumor development/volume was observed and measured. The results provide valuable insight into the therapuetic potential of a variety of drug regimens and their efficacy.

Observations

1) The correlation between mouse weight and average tumor volume for the Capomulin treatment was 0.84. This indiciates a fairly strong positive relationship between the two variables, where a greater weight was associated with a greater tumor volume. This suggests a relationship between weight and tumor voume, where heavier mice have larger tumors. This relationship should be further explored to see if this finding holds across different treatment conditions, and if weight could be a causal factor for tumor growth. 

2) Out of the four treatments of interest, the Capomulin and Ramicane regimens resulted in the lowest tumor volume at the end of treatment. These two treatments appear to be more effective than Infubinol and Ceftamin, however the Infubinol treatment condition has one outlier that experienced a signifcant decrease in tumor volume compared to the other mice in that treatment group. Before ruling out Infubinol as a potential therapuetic, that outlier should be examined to see if there is an explanation for why that mouse had a much better treatment outcome. 

3) The line chart showing the Capomulin treatment of mouse L509 shows that tumor volume decreased to it smallest amount around day 35, and then slightly increased in volume by the last day of treatment (day 45). Although Capomulin does seem to be an effective treatment and the mouse did experience significant tumor reduction, this change in tumor volume that occured during the last 10 days of treatment should be further examined. For example, it is possible that the treatment only needs to be administered for 35 days. The tumor volume vs. time point data for other mice in the Capomulin treatment group should be examined to see if this is a pattern.

Charts

Summary Table (Using Groupby)


<img width="829" alt="SummaryTableGroupby" src="https://user-images.githubusercontent.com/69160361/96347522-69ecdb80-105f-11eb-8955-d87b77a2f95e.png">


Summary Table (Using Aggregation)


<img width="447" alt="SummaryTableAgg" src="https://user-images.githubusercontent.com/69160361/96378571-17d4b480-114a-11eb-99c3-f24dd733a87b.png">


Bar Chart (Using Pandas)


<img width="458" alt="PANDASbargraph" src="https://user-images.githubusercontent.com/69160361/96378650-c2e56e00-114a-11eb-85ed-210fe4ae8baa.png">


Bar Chart (Using PyPlot)


<img width="437" alt="PYPLOTbargraph" src="https://user-images.githubusercontent.com/69160361/96378687-09d36380-114b-11eb-8349-99102e95a528.png">


Mouse Sex Distribution Pie Chart (Using Pandas)


<img width="296" alt="PANDASpieplot" src="https://user-images.githubusercontent.com/69160361/96378704-2079ba80-114b-11eb-8a43-3e4cb36467a3.png">


Mouse Sex Distribution Pie Chart (Using Pyplot)


<img width="287" alt="PYPLOTpieplot" src="https://user-images.githubusercontent.com/69160361/96378708-28395f00-114b-11eb-8c7b-d373808f4c41.png">


Box Plot


<img width="443" alt="Screen Shot 2020-10-18 at 3 35 47 PM" src="https://user-images.githubusercontent.com/69160361/96386369-b0256600-1157-11eb-9732-416039e9284d.png">


Line Plot 


<img width="454" alt="linechart" src="https://user-images.githubusercontent.com/69160361/96378721-38513e80-114b-11eb-8efd-169879646e70.png">


Scatter Plot


<img width="465" alt="scatterplot" src="https://user-images.githubusercontent.com/69160361/96378723-3f784c80-114b-11eb-8410-626eed88c292.png">


Scatter Plot with Correlation Coefficient and Linear Regression


<img width="654" alt="scatterplotline" src="https://user-images.githubusercontent.com/69160361/96378730-47d08780-114b-11eb-8a67-1f6e06a3da06.png">


