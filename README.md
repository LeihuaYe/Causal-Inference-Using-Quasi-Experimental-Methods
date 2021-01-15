# Project Summary

With the rise of Machine Learning and Big Data, Causal Inference still possesses its unique position in the family of Data Science. By choosing an appropriate research design, it is possible to establish a causal relationship between IVs and DV. In this repository, I introduce the most adopted quasi-experimental models for Causal Inference, along with their R implementations. In addition, I've linked the methods to the original technical posts. The combination of R code with the original post may give you a better understanding of each technique. 

This is an on-going project, and I'll add more experimental designs as time goes by. 

One final caveat: there is no one-fits-all solution; Instead, we shall understand the question well, what is available, what are the tradeoffs of different methods. 

## Quasi-experimental Methods
0. A General Read on The Business Application of Causal Inference, https://towardsdatascience.com/the-turf-war-between-causality-and-correlation-in-data-science-which-one-is-more-important-9256f609ab92 

1. Regression Discontinuity Design: The Crown Jewel of Causal Inference, https://towardsdatascience.com/the-crown-jewel-of-causal-inference-regression-discontinuity-design-rdd-bad37a68e786
- pro: relatively strong in terms of causal strength; less strict statistical assumptions.
- con: local treatment effect; not generalizable

2. A Practitioner's Guide To Interrupted Time Series, https://towardsdatascience.com/what-is-the-strongest-quasi-experimental-method-interrupted-time-series-period-f59fe5b00b31
- pro: strong in causal power
- con: strict requirement of time points 

3. A Practitioner's Guide To Difference-In-Differences Approach: Wage Goes Up, Employment Goes Down?, https://towardsdatascience.com/does-minimum-wage-decrease-employment-a-difference-in-differences-approach-cb208ed07327
- pro: easy to use
- con: not as strong as others; need to combine with other methods such as pairing

4. Causal Inference Using Synthetic Control: The Ultimate Guide, https://towardsdatascience.com/causal-inference-using-synthetic-control-the-ultimate-guide-a622ad5cf827
- pro: usable when there is only one treatment case
- con: strict data assumptions

## About the Author

Leihua Ye is a Ph.D. Researcher at the UC, Santa Barbara. He has received extensive training in Causal Inference, Research Design, Machine Learning, Big Data, and Machine Learning. 

He receives his B.A. and M.A. from the University of Nottingham. 

## Contact

Email: yeleihua@gmail.com

LinkedIn: www.linkedin.com/in/leihuaye

Tech Blog: https://leihua-ye.medium.com
