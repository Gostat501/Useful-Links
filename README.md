# Useful-Links
Useful links for data science.

- [GitHub and R](https://resources.github.com/whitepapers/github-and-rstudio/)

- [How to handle missing data](https://machinelearningmastery.com/handle-missing-data-python/)

- [Encoding categorical variable](https://pbpython.com/categorical-encoding.html)

- [Ensembling/creating new features](https://www.kaggle.com/arthurtok/introduction-to-ensembling-stacking-in-python)

- [Ensemble modeling](https://www.kaggle.com/yassineghouzam/titanic-top-4-with-ensemble-modeling)

- [Data science basics](https://www.kaggle.com/startupsci/titanic-data-science-solutions)

- [Achieve 99% accuracy strategies](https://www.kaggle.com/ldfreeman3/a-data-science-framework-to-achieve-99-accuracy)

- [Metric of Machine-Learning errors](https://towardsdatascience.com/how-to-select-the-right-evaluation-metric-for-machine-learning-models-part-1-regrression-metrics-3606e25beae0)

- [How to answer bussiness marketing questions](https://blog.hubspot.com/marketing/marketing-questions-analytics)

- [6 digital marketing analytics questions](https://www.socialmediatoday.com/news/6-digital-marketing-analytics-questions-answered/539450/)

- [Intro to CNN Keras, for image processing](https://www.kaggle.com/yassineghouzam/introduction-to-cnn-keras-0-997-top-6)

- [Ensemble Modeling (ZestFinance)](https://www.zestfinance.com/blog/many-heads-are-better-than-one-making-the-case-for-ensemble-learning)

- [Jupyter Markdown Codes](https://jupyter-notebook.readthedocs.io/en/stable/examples/Notebook/Working%20With%20Markdown%20Cells.html)

- [AB Testing with Python](https://towardsdatascience.com/the-math-behind-a-b-testing-with-example-code-part-1-of-2-7be752e1d06f)

- [Power Analysis in Python](https://towardsdatascience.com/introduction-to-power-analysis-in-python-e7b748dfa26)

```{python}
# parameters for the analysis 
effect_size = 0.8 # sqrt(mu(B)-mu(A) / std(A+B))
alpha = 0.05 # significance level
power = 0.8

power_analysis = TTestIndPower()
sample_size = power_analysis.solve_power(effect_size = effect_size, 
                                         power = power, 
                                         alpha = alpha)

print('Required sample size: {0:.2f}'.format(sample_size))
```
- [LightGMB as the first machine learning model (Japanese)](https://upura.hatenablog.com/entry/2019/10/29/184617)

- [Why LightGBM is important?](https://medium.com/@pushkarmandot/https-medium-com-pushkarmandot-what-is-lightgbm-how-to-implement-it-how-to-fine-tune-the-parameters-60347819b7fc)

- [What statistical analysis should I use?](https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/?fbclid=IwAR2pyDQW57ev3wYNkFnjg_p-kBYA6Vxyd0KT58cuom2veNo0a2-hgVZXZak)

## Interview Preparation

- [What to do when you are unable to answer technical questions](https://www.quora.com/What-should-I-do-when-asked-a-technical-question-that-I-am-unable-to-answer-at-that-moment-during-a-software-internship-interview)












