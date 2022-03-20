1. For classifying product names to categories

- What precision (P@1) were you able to achieve?

  > 0.641

- What fastText parameters did you use?
  > min product = 5 and 10
  > wordgrams = 2
  > epochs = 50

- How did you transform the product names?
  > Changing to lowercase 
  > Tokenizing
  > Snowball stemmed

- How did you prune infrequent category labels, and how did that affect your precision?

  > Limiting the categories to 10 or less, didn't get to measuring precision

- How did you prune the category tree, and how did that affect your precision?

  >  did not attempt


2.  For deriving synonyms from content:  (didn't attempt)

  - What 20 tokens did you use for evaluation?

  - What fastText parameters did you use?

  - How did you transform the product names?

  - What threshold score did you use? 

  - What synonyms did you obtain for those tokens?

3. For integrating synonyms with search:  (didn't attempt)

  - How did you transform the product names (if different than previously)?

  - What threshold score did you use?

  - Were you able to find the additional results by matching synonyms?

4. For classifying reviews: (didn't attempt)

  - What precision (P@1) were you able to achieve?

  - What fastText parameters did you use?

  - How did you transform the review content?

  - What else did you try and learn?
