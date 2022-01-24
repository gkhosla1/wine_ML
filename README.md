# wine_ML

This was my final project for an Intro to Machine Learning class (completed in Fall 2021). The idea behind the project was to use text mining combined with various supervised learning techniques to predict how a wine reviewer would numerically score a given wine based on their written review. There is also an unsupervised task at the end of the notebook just for fun. The only necessary source file is winemag_data.csv.

Models included in notebook:
- Naive Bayes\n
      - Traditional NB
            - 1-grams
            - 1, 2-grams
            - 1, 2, 3-grams
      - Complementary NB
            - 1-grams
            - 1, 2-grams
            - 1, 2, 3-grams

- MLP (basic Neural Network)
      - architecture #1 (2 dense layers, 100 nodes each)
            - 1-grams
            - 1, 2-grams
            - 1, 2, 3-grams
      - architecture #2 (2 dense layers, 100 nodes each, 25% dropout rate each)
            - 1-grams
            - 1, 2-grams
            - 1, 2, 3-grams
      - architecture #3 (2 dense layers, 100 nodes each, 40% dropout rate each)
            - 1-grams
            - 1, 2-grams
            - 1, 2, 3-grams
      - architecture #4 (2 dense layers, 100 nodes each, l1 regularization factor of .001, l2 regularization factor of 0.001 each)
            - 1-grams
            - 1, 2-grams
            - 1, 2, 3-grams

- Random Forest
      - 100 trees, varying maximum depths (10, 20, 30, 50, 75, 100, none)
            - 1-grams
            - 1, 2-grams
      - 150 trees, varying maximum depths (10, 20, 30, 50, 75, 100, none)
            - 1-grams
            - 1, 2-grams

- Unsupervised Learning: Topic Modeling with LDA
      - 2 topics
      - 5 topics
      - 10 topics
