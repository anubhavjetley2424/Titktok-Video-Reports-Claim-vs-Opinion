# TikTok Video Classification: Claim vs. Opinion
## Task Description
The task at hand involves classifying TikTok videos into two categories: "Claim" and "Opinion." A successful machine learning model will be capable of automatically identifying whether a given video makes a factual claim or merely expresses an opinion. This distinction is crucial for TikTok's content moderation efforts and can significantly enhance the overall user experience on the platform.

## Methodology
- Random Forest Algorithm: I utilize the Random Forest algorithm due to its ability to handle high-dimensional data, maintain low bias, and offer good generalization performance. The ensemble approach of Random Forest helps in enhancing predictive accuracy and mitigating overfitting.

- GridSearch for Hyperparameter Estimation: GridSearch is used to systematically explore various hyperparameter combinations and identify the optimal set of hyperparameters for the Random Forest model. This process helps fine-tune the model and achieve better performance.

- Tokenize Text Technique: In order to transform textual information within the videos into numerical features, I employ the Tokenize Text technique. By converting the text data into a suitable format for machine learning algorithms, I can effectively include textual information in the model training process.
