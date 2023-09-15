## Operating Expense (OpEx) Variance Analysis
* Background: The company had budgets for each operational expense (OpEx). If the actual expense for the quarter missed the budget, an accountant would leave a comment for the reason behind the
  "variance" (budget miss). I was tasked with categorizing the general reasons behind these variances.
* Result: Applied unsupervised learning algorithms (NLP) to create 10 evenly distributed categories that classified 20,000+ OpEx variance comments. This project allowed accountants and analysts
  to understand/analyze the reasons behind OpEx variances to prevent occurances in the future!
* Reduced workload by ~ 60% and achieved ~ 80% accuracy on hold-out set
* Developed a python pipeline (pandas, nltk, sentence_transformers, sklearn) that embedded sentences into vectors (BERT LLM) and utilized K-Means clustering to categorize OpEx variance comments
* Launched a local app (python: plotly and dash) to visualize the key phrases per category. This was used to help analysts summarize the content of the 20,000+ comments.
