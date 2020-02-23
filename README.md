# MA-Thesis
Here the Analysis for My Master's thesis can be found. 
This thesis relies on Explainable Artificial Intelligence Framework. E.A.I.F is the name that is given to very operation of
turning Gradient Boosted Decision Trees (LightGMB) into white-box models by leveraging the Shapley Values from Cooperative Game Theory.
https://github.com/slundberg/shap

# Why Do We Need explainable AI in Social Sciences
Linear models, unlike algorithmic modelling, necessitates researchers to have well defined theoretical model of the given problem in their minds. If the researcher has no well defined theoretical model, or for some reason, falls short on translating the theoretical model into realm of statistics, then the obtained statistical results might be misleading.

In social sciences the common practice is building statistical models without specifying the interactions and non-linearities.  
However, this approach is problematic due to following reasons. 
**1)** Social relationships are too complex and it's a fundamentally challenging task to come up with a well-defined theoretical representation of the social reality.
**2)** There is no reason to assume linearity in social relations. In fact, social relationships mostly are of non-linear nature.

However, as I intend to show in this M.A thesis, Explainable AI can help us find plausible relationships within the data without requiring us to prespecify the interaction effects among the variables and potential non-linearities. 

# Limitations

The results that I have obtained from Explainable AI so far has no numerical stability. It's non-reproducible and we not suitable for statistical inference so far. 

The problem of numerical stability can be solved by training models on bootstrap samples with replacement and calculating Shapley values for each of them respectively. This iterative process is both time consuming and computationally expensive. 

# Explainable AI as a Grounded Theory?

An alternative way to benefit the capabilities of Explainable AI is viewing its findings as an alternative way of building a theory. The relationships that we see in the Explainable AI model can be hypothesized and tested by using linear models. Refer to the last 4 slides of the presentation.


 

