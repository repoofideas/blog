---
toc: true
layout: post
description: Modeling user's repetitive behavior pattern for recommendation system
categories: [Recommendation System]
title: How does Amazon recommend products to the users? 🔎
---
### Intro

Before you buy a product, a typical decision process may include comparison of similar products, browsing multiple brands, or consulting an expert(if you are lucky enough to know one). Recommendation systems are designed to simplify these convoluted process, like a personalized consultant. Since Amazon is the largest online retailer in the world, I became interested in how their website tailor personalized recommendations for enormous number of products and users. Upon research, I've found an interesting paper[^1] and patent[^2] from Rahul Bhagat, an applied scientist at Amazon, that used **repeat purchase history** and **product type** for personalized recommendations.




### 'Buy it Again' recommendaiton feature from Amazon
![bia](https://github.com/repoofideas/blog/blob/master/images/amazon/bia.png?raw=true)


<img src="https://render.githubusercontent.com/render/math?math=P_{A_{i}}\left(t_{k+1}=t \mid t_{1,}, t_{2,}, t_{3}, \ldots t_{k}\right)"> 
ok
<img src="https://render.githubusercontent.com/render/math?math=e^{i \pi} = -1" style="float:left">

### Acknowledgments
[^1]:Bhagat, R., Muralidharan, S., Lobzhanidze, A., & Vishwanath, S. (2018, July). Buy it again: Modeling repeat purchase recommendations. In Proceedings of the 24th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining (pp. 62-70).
[^2]:MuralidharanRahul, S., Bhagat, R. (2021). Personalized network content generation and redirection according to time intervals between repeated instances of behavior based on entity size (US10891678B1). U.S. Patent and Trademark Office. https://patft.uspto.gov/netacgi/nph-Parser?Sect1=PTO1&Sect2=HITOFF&d=PALL&p=1&u=%2Fnetahtml%2FPTO%2Fsrchnum.htm&r=1&f=G&l=50&s1=10,891,678.PN.&OS=PN/10,891,678&RS=PN/10,891,678

