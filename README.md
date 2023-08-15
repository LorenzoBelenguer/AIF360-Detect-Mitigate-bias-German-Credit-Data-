# AIF360-Detect-Mitigate-bias-German-Credit-Data-
AIF360 Detect/Mitigate bias in the German Credit Dataset
This dataset classifies people described by a set of attributes as good or bad credit risks. File used is german.data consisting of 1000 instances and 20 features. Detailed description of the dataset is provided in german.doc. https://archive.ics.uci.edu/ml/datasets/Statlog+%28German+Credit+Data%29

The AI Fairness 360 toolkit is an extensible open-source library containing techniques developed by the research community to help detect and mitigate bias in machine learning models throughout the AI application lifecycle. AI Fairness 360 package is available in both Python and R.

The AI Fairness 360 package, AIF360, includes a comprehensive set of metrics for datasets and models to test for biases, explanations for these metrics, and algorithms to mitigate bias in datasets and models. It is designed to translate algorithmic research from the lab into the actual practice of domains as wide-ranging as finance, human capital management, healthcare, and education.

In order to check a dataset to detect and mitigate bias in AI systems using a package such as AIF360, we need at least one protected characteristic. In this example, I will be testing bias based on age.

Patterns that are found may not be desirable or may even be illegal. For example, this credit score model may determine that age plays a significant role in the prediction of repayment because the training dataset happened to have better repayment for one age group than for another. This raises two problems: 1) the training dataset may not be representative of the true population of people of all age groups, and 2) even if it is representative, it is illegal to base any decision on a applicant's age, regardless of whether this is a good prediction based on historical data.

If that is the case, there is a need to correct the model to reduce bias. AI360 is designed to help address this problem with fairness metrics and bias mitigators. Fairness metrics can be used to check for bias in machine learning workflows. Bias mitigators can be used to overcome bias in the workflow to produce a more fair outcome.
