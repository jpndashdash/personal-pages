---
title: "Computational methods for estimating multinomial, nested, and cross-nested logit models that account for semi-aggregate data"
collection: publications
permalink: /publication/2018-computational-methods
excerpt: 'We present a summary of important computational issues and opportunities that arise from the use of semi-aggregate data (where the explanatory data for choice scenarios are not necessarily unique for each decision-maker) in discrete choice models.'
date: 2018-03-01
venue: 'Journal of Choice Modelling'
paperurl: 'https://www.sciencedirect.com/science/article/abs/pii/S1755534517300179'
citation: 'Newman, J. P., Lurkin, V., & Garrow, L. A. (2018). &quot;Computational methods for estimating multinomial, nested, and cross-nested logit models that account for semi-aggregate data.&quot; <i>Journal of choice modelling</i>, 26, 28-40.'
---
We present a summary of important computational issues and opportunities that arise from 
the use of semi-aggregate data (where the explanatory data for choice scenarios are not 
necessarily unique for each decision-maker) in discrete choice models. These data are 
encountered with large transactional databases that have limited consumer information, a 
common feature in some transportation planning applications, such as airline itinerary 
choice modeling. We developed a freeware software package called Larch, written in Python 
and C++, to take advantage of these kind of data to greatly speed the estimation of 
discrete choice model parameters. Benchmarking experiments against Stata (a commonly 
used commercial package), Biogeme (a commonly used freeware package), and ALOGIT (a 
highly specialized commercial package for discrete choice modeling) based on an industry 
dataset for airline itinerary choice modeling applications shows that the size of the 
input estimation files are 50–100 times larger in Stata and Biogeme, respectively. 
Estimation times are also much faster in ALOGIT and Larch; e.g., for a small itinerary 
choice problem, a multinomial logit model estimated in ALOGIT or Larch converged in less 
than one second whereas the same model took almost 15 seconds in Stata and more than 
three minutes in Biogeme.


