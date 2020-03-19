---
layout: post
title: Predicting high school dropout on Rio de Janeiro
categories: [Projects]
tags: [data science, education]
fullview: true
comments: true
---

This project aims to build a freshman dropout predictor for high schools in Rio de Janeiro state using public data.

According to a study by [Insper](http://gesta.org.br/wp-content/uploads/2017/09/Politicas-Publicas-para-reducao-do-abandono-e-evasao-escolar-de-jovens.pdf), one in every 4 young people aged 15 to 17 interrupt their studies at this stage. Several dropout recovery programs have emerged in recent years in different states and municipalities. The current public policy acts after the student leaves the educational system. My goal was to measure the likelihood of a student to dropout, creating a vulnerability indicator that could be used in a preemptive public policy. 

The data sourced from the [Brazilian School Census](http://portal.inep.gov.br/censo-escolar) (2016/2017), crossed with schools and favelas geolocation. To contemplate the grouping structure of students within schools, multilevel regression and mixed random forest models were tested. Some of the findings were that student's age played a major role in prediction - as a baseline, it had an AUC of .6 -, and also other features such as the use of public transportation had a positive effect of reducing dropout.

<a class="btn btn-secondary" href="https://github.com/fernandascovino/tcc_emap">Check out the code on GitHub!</a> 
<a class="btn btn-secondary" href="https://docs.google.com/presentation/d/1vZwOeb8y5v3Ls1A6gzKOEhrAjd5TeHD_cRXEdmYGeRk/edit?usp=sharing">Presentation from Cerveja com Dados: OpenData Day (pt-br)</a>
