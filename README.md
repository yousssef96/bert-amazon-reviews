# Amazon Review Sentiment Classification

Use machine learning to classify Amazon customer reviews as positive or negative.



## Description

### Goal of the Project
In this project, you’ll build a model to classify Amazon customer reviews into **negative** (1-2 star) or **positive** (4-5 star) sentiment. The dataset is large enough to reflect real-world business scenarios.



## Context
Understanding customer sentiment is crucial for businesses. Accurate sentiment analysis can help companies:

- Identify products that consistently receive negative feedback.  
- Improve customer satisfaction by addressing recurring complaints.  
- Automate review moderation and insights extraction from millions of reviews.  

Most reviews in this dataset are in **English**, but a small portion may be in other languages like Spanish. Neutral (3-star) reviews were excluded, simplifying the problem to a **binary classification task**.



## Potential Impact
If successful, this model can be deployed to:

- Analyze customer sentiment at scale.  
- Provide actionable insights to product teams and marketing departments.  
- Reduce the need for manual review labeling, saving time and resources.  

This demonstrates practical NLP skills applied to **real business data**.


## Dataset

The data format follows the **fastText supervised learning tutorial**:

Where:

- `__label__1` = 1-2 star reviews (negative)  
- `__label__2` = 4-5 star reviews (positive)  
- The text includes the review title prepended to the content, separated by `": "`  
- Neutral (3-star) reviews are not included  

### Files

- `train.ft.txt`: Training set  
- `test.ft.txt`: Test set  
- Each file contains text reviews with labels as described above



## Evaluation

- The main evaluation metric is **accuracy** (percentage of correct predictions).  
- The model is trained on a **training split**, tuned on a **validation split**, and evaluated on a **test split**.

