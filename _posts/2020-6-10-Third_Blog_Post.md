---
layout: post
title: Third blog post.
---
For our first project for ST 558 we were asked to access data from the NHL API and generate a series of summary tables, contingency and diagrams. Two of the five calls returned data for the league as a whole. For these calls I generated a timeline diagram for the years in which active and inactive NHL teams have been in existence. Additionally, I generated a histogram showing average penalty minutes per games for all active teams grouped by conference. It turns out that the Metropolitan conference is home to the league's most egregious scofflaws!

The last three of the five calls for the project were franchise specific and in my case, I looked into data for the Pittsburgh Penguins. The first visual was a pair of ineractive tables, delineating team records. Next, I created a bar chart comparing game outcomes by Pittsburgh goalies over the years. Finally, I created a scatterplot comparing penalty minutes logged and years played by position - Left Wingers and Centers accumulate penalty minutes the quickest while Right Wingers accumulate them the most slowly.

##A few takeaways from this project:##

1) Accessing the data from the API was quick painless.

2) Flattening the data resulted in tables that looked deceptively good, however in most cases data was actually formatted as a list. I struggled for a while to appreciate the importance of this format and the need to call just the first element of the list (the data frame) in order to perform subsequent analysis. 

3) I struggled with how to apply a name to the first column of a table. Prior knowledge of rowname_to_column would have saved me a few hours of heartache. 

4) More prior experience with repositories and "pushed" code would have been helpful.

5) The biggest takeaway for me, from this project, however, was just how much data can be moved quickly across an API.


