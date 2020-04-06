# Sentiment-Analysis-with-scikit-learn-and-nltk
Uses voting from NaiveBayes, LinearSVC, MultinomialBinary, BernoulliNB, Logistic Regression for final result


## External Python Dependencies

- python7.7.7
- Scikit Learn@0.22.2
- nltk@3.5b1

## Installing

- Run the jupter notebook **Sentiment_Analysis_Notebook.ipynb**. It will fill the pickled_files directory with saved models.
- Once done you can import sentiment_analysis.py module

## Example Usage

- While inside the directory containing the sentiment_analysis.py file and the pickled_files folder

```python
import sentiment_analysis as s

print(s.sentiment("The movies was very bad. They acting was horrible. Very bad experience! 0/10!"))
```
