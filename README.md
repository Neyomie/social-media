## ABSTRACT 
*The increasing prevalence of social media use has increased concerns regarding its 
problematic and addictive engagement patterns, yet most existing research relies on 
correlational and regression-based methods that struggle to capture the complex, non-linear 
relationships between behavioural and psychological predictors. This study developed and 
evaluated machine learning models for predicting social media addiction risk, and applied 
explainable AI to identify the variables driving those predictions. Using a publicly available 
dataset of 258 adolescents and young adults, a binary "at-risk" target was constructed from 
the Bergen Social Media Addiction Scale (BSMAS) using a validated clinical cut-off, producing 
a severely imbalanced dataset (88.8% not-at-risk, 11.2% at-risk). Four classifiers, Logistic 
Regression, Decision Tree, Random Forest, and Support Vector Machine, were each combined 
with three imbalance-handling strategies (no rebalancing, class-weighting, and SMOTE), and 
evaluated using nested, repeated, stratified cross-validation against PR-AUC and F1. Random 
Forest achieved the highest PR-AUC (0.232), narrowly ahead of SVM with SMOTE (0.231), 
while Decision Tree achieved the highest F1 (0.215). On a held-out test set, the selected 
Random Forest model achieved a PR-AUC of 0.361 and ROC-AUC of 0.676, both well above 
the 0.115 baseline expected by chance, though recall at the default threshold remained low 
(0.167). SHAP analysis of the final model showed that psychometric variables: cognitive 
interference from smartphone use, trait and state anxiety, and self-esteem  contributed more to 
predictions than behavioural usage variables such as time spent or number of platforms used. 
These findings suggest that machine learning can meaningfully outperform chance-level 
prediction of social media addiction risk, but that reliable case-level identification remains 
constrained by small sample size and severe class imbalance. The results further suggest that 
screening and intervention efforts may benefit from incorporating psychometric indicators of 
psychological vulnerability alongside, or in place of, behavioural usage metrics. 
Recommendations for future research include larger and multi-site samples, longitudinal 
designs, and external validation across cultural contexts.*
