This is the git repo for CMPE 257 Machine Learning Course.

### Resources
---
- [Project Proposal Doc](https://docs.google.com/document/d/1g0QzqaCswfreFEjupCt6V5stKHfmYMRoKg1mxsk5PwQ)
- Dataset [U.S. Patent Phrase to Phrase Matching](https://www.kaggle.com/competitions/us-patent-phrase-to-phrase-matching)

### To Do
---
1. Create Validation Set

2. Baseline LLM implementation

  - https://www.kaggle.com/code/jhoward/getting-started-with-nlp-for-absolute-beginners
  - https://www.kaggle.com/code/jhoward/iterate-like-a-grandmaster

3. Siamese Net Implementation

  - https://github.com/shahrukhx01/siamese-nn-semantic-text-similarity

4. Introduce Cross Attention
  - [Paper](https://arxiv.org/pdf/1603.07810.pdf) and [Code](https://github.com/andreasveit/conditional-similarity-networks)
  Inspired by this, we want to introduce a mask based on **context**. They have used a simple embedding layer that they are using as Mask for image features. But instead, in our case, we plan to use Cross-Attention layer for conditioning the features based on context.
