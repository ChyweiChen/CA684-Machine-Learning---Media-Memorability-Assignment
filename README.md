# CA684-Machine-Learning---Media-Memorability-Assignment
In this project, I first used different single features for regression to obtain the memorability scores of the videos. In order to fuse multiple features,
My strategy is to evaluate the models using Spearman's correlation coefficient, and to select the three best models for the short-term_memorability target and the long-term_memorability target, and then to assign weights to each model according to its Spearman's correlation coefficient to form a multi-model.
I used four regressors as baseline models, namely support vector regression (SVR) and random forest regression (RFR), BayesianRidge (BR) and XGBoost model.In the end, the XGBoost model was abandoned because it performed too poorly.
