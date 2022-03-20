**For query classification:**

- How many unique categories did you see in your rolled up training data when you set the minimum number of queries per category to 100? To 1000?
  > 879 & 387

- What values did you achieve for P@1, R@3, and R@5? You should have tried at least a few different models, varying the minimum number of queries 
per category as well as trying different fastText parameters or query normalization. Report at least 3 of your runs.

min_queries 100 epoch 25
- P@1	0.484
- R@3	0.621
- R@5	0.634

minqueries 100 epoch 25 wordNgrams 2
- P@1	0.531
- R@3	0.734
- R@5	0.731

minqueries 1000 epoch 25
- P@1	0.501
- R@3	0.658
- R@5	0.742

**For integrating query classification with search:** 
(didn't get to this yet)

- Give 2 or 3 examples of queries where you saw a dramatic positive change in the results because of filtering. Make sure to include the classifier output for those queries.
- Given 2 or 3 examples of queries where filtering hurt the results, either because the classifier was wrong or for some other reason. Again, include the classifier output for those queries.
