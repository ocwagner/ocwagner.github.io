---
layout: post
title: Project 2 post.
---
For our second ST 558 project we were asked to develop models predicting "shares" based on a data set of 61 attributes and 39,644 observations. In total I developed 6 models:

1) A simple linear model incorporating all predictive variables.
2) A linear model incorporating select variables that are correlated with "shares" 
3) A bagged tree model without cross validation
4) A bagged tree model with cross validation
5) A boosted tree model with all variables, and;
6) A boosted tree model with just the select variables used in model "2".

Models were trained on a scaled, test dataset specific to each day of the week and tested on a seperate data set also specific to the day in question. Predictiveness was evaluated using RMSE. Relatively little difference was observed in terms of predictiveness across models, which suggests that the relationship between "shares" and independent variables is farily linear in nature. 

[The GitHub Markdown for that project lives here.](https://github.com/ocwagner/Project_2/blob/master/README.md)

### A few takeaways and questions from this project:

1) With computationally simpler assignments, you could make mistakes, redo work and troubleshoot without too much penalty. But, once you start asking developing ensemble models it seems more important to be methodical upfront, lest you waste a fair amount of time rerunning your models.
2) In past assignments I have been more comfortable working in the R script and transfering that work to R Markdown. But in the same vein as above, I began to confront the inefficiences of this approach with this project. 
3) I have a strong appreciation for the caret package automating model training and prediction for us. But, with so much automation and relatively little training in statistical theory how confident can I be that my models are sound?
4) What applications can we use to help use select appropriate variables upfront, making our models easier to interpret?
