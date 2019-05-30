---
layout: post
title: US arms sales are not a good immediate predictor of election results
subtitle: 
tags: [regression]
comments: true
---

An attempt an multiple linear regression for US presidential election results by arms sales from the [SIPRI](https://www.sipri.org/databases/armstransfers) 
database using scikit-learn and leave-one-out cross validation had the following results:<br/><br/>
Mean absolute error: 4.203%<br/>
Mean squared error: 26.183%<br/>
RMS error: 4.99%<br/>
R2: 0.084<br/><br/>
So there may be some minor predictive effect, but not good enough for predicting the outcomes of elections, which are usually close. 
Below is a graph of the best-fit plane of US sales of military aircraft and armored vehicles versus the incumbent vote percentage for 1950-2018.<br/>

![arms](https://raw.githubusercontent.com/dzkha/dzkha.github.io/master/img/arms.png)
