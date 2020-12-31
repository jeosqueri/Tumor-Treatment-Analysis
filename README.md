# Matplotlib Assignmet- The Power of Plots

Project Overview
------
In this project, I was tasked with examining the data from an animal study where 248 mice with SCC tumor growth were treated with a variety of drug regimens. These treatments were administered for 45 days and during that time tumor development/volume was observed and measured. The results provide valuable insight into the therapuetic potential of a variety of drug regimens and their efficacy.

Observations
------

1) The correlation between mouse weight and average tumor volume for the Capomulin treatment was 0.84. This indiciates a fairly strong positive relationship between the two variables, where a greater weight was associated with a greater tumor volume. This suggests a relationship between weight and tumor voume, where heavier mice have larger tumors. This relationship should be further explored to see if this finding holds across different treatment conditions, and if weight could be a causal factor for tumor growth. 

2) Out of the four treatments of interest, the Capomulin and Ramicane regimens resulted in the lowest tumor volume at the end of treatment. These two treatments appear to be more effective than Infubinol and Ceftamin, however the Infubinol treatment condition has one outlier that experienced a signifcant decrease in tumor volume compared to the other mice in that treatment group. Before ruling out Infubinol as a potential therapuetic, that outlier should be examined to see if there is an explanation for why that mouse had a much better treatment outcome. 

3) The line chart showing the Capomulin treatment of mouse L509 shows that tumor volume decreased to it smallest amount around day 35, and then slightly increased in volume by the last day of treatment (day 45). Although Capomulin does seem to be an effective treatment and the mouse did experience significant tumor reduction, this change in tumor volume that occured during the last 10 days of treatment should be further examined. For example, it is possible that the treatment only needs to be administered for 35 days. The tumor volume vs. time point data for other mice in the Capomulin treatment group should be examined to see if this is a pattern.

Charts
------

**Summary Table** *(Using Groupby)*

<img width="829" alt="SummaryTableGroupby" src="https://user-images.githubusercontent.com/69160361/96347522-69ecdb80-105f-11eb-8955-d87b77a2f95e.png">


**Summary Table** *(Using Aggregation)*

<img width="447" alt="SummaryTableAgg" src="https://user-images.githubusercontent.com/69160361/96378571-17d4b480-114a-11eb-99c3-f24dd733a87b.png">


**Bar Chart** *(Using Pandas Plot)*

![Screen Shot 2020-12-31 at 1 03 49 PM](https://user-images.githubusercontent.com/69160361/103424326-b75dec80-4b68-11eb-9e2f-557b4bbe3a98.png)


**Bar Chart** *(Using Matplotlib PyPlot)*

![Screen Shot 2020-12-31 at 1 04 01 PM](https://user-images.githubusercontent.com/69160361/103424352-df4d5000-4b68-11eb-91ec-5b25a6f54db3.png)


**Mouse Sex Distribution Pie Chart** *(Using Pandas Plot)*

![Screen Shot 2020-12-31 at 1 09 32 PM](https://user-images.githubusercontent.com/69160361/103424451-98138f00-4b69-11eb-90b8-a14dc18ba51d.png)


**Mouse Sex Distribution Pie Chart** *(Using Matplotlib Pyplot)*

![Screen Shot 2020-12-31 at 1 09 43 PM](https://user-images.githubusercontent.com/69160361/103424460-a3ff5100-4b69-11eb-89df-60a01459f6a2.png)


**Box Plot** *Final tumor volume across four most effective regimens*

![Screen Shot 2020-12-31 at 1 09 55 PM](https://user-images.githubusercontent.com/69160361/103424486-d0b36880-4b69-11eb-9ea0-94bf1100da83.png)


**Line Plot** *Tumor volume over time for mouse L509*

![Screen Shot 2020-12-31 at 1 10 07 PM](https://user-images.githubusercontent.com/69160361/103424515-f80a3580-4b69-11eb-8ec1-ac1228a4d275.png)


**Scatter Plots** 
*Capomulin Treatment: Mouse weight vs. Tumor volume*

![Screen Shot 2020-12-31 at 1 10 18 PM](https://user-images.githubusercontent.com/69160361/103424526-09ebd880-4b6a-11eb-8f9d-4cff2aa8ec6b.png)

*Linear Regression*

![Screen Shot 2020-12-31 at 1 10 30 PM](https://user-images.githubusercontent.com/69160361/103424554-428bb200-4b6a-11eb-901f-7db5c9499149.png)


