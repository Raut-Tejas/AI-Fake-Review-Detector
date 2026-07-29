# AI Fake Review Detector

Final project for the Building AI course

## Summary

AI Fake Review Detector is an AI-powered system that identifies whether an online review is genuine or fake using Natural Language Processing (NLP) and Machine Learning. The goal is to improve trust in online shopping platforms by helping users recognize suspicious reviews before making purchasing decisions.

## Background

Online reviews have become one of the most important factors influencing customer purchasing decisions. Unfortunately, fake reviews are increasingly common and can mislead customers, unfairly promote products, or damage the reputation of competitors.

This project aims to help customers and businesses by automatically identifying suspicious reviews.

Problems this project addresses:

* Fake reviews that manipulate product ratings.
* Customers buying poor-quality products because of misleading reviews.
* Businesses losing trust due to dishonest competitors.
* The difficulty of manually checking thousands of online reviews.

My personal motivation comes from seeing how difficult it is to know whether online reviews can be trusted. Artificial Intelligence can assist users by analyzing review patterns much faster than humans.

## How is it used?

A user enters or uploads the text of an online review into the system.

The AI model processes the review using Natural Language Processing techniques and predicts whether it is likely to be genuine or fake. The system also provides a confidence score to indicate how certain the prediction is.

Possible users include:

* Online shoppers
* E-commerce companies
* Hotel booking websites
* Restaurant review platforms
* Marketplace administrators

Example workflow:

```
User enters a review
        │
        ▼
Text preprocessing
        │
        ▼
Feature extraction (TF-IDF)
        │
        ▼
Machine Learning model
        │
        ▼
Prediction
        │
        ▼
Fake or Genuine
```

## Data sources and AI methods

The project can be trained using publicly available review datasets.

Possible data sources include:

* Kaggle Fake Review Dataset
* Yelp Open Dataset
* Amazon Product Reviews
* Hotel Review Dataset

The AI methods used include:

* Natural Language Processing (NLP)
* Text preprocessing
* TF-IDF (Term Frequency–Inverse Document Frequency)
* Supervised Machine Learning
* Logistic Regression
* Naive Bayes
* Support Vector Machine (SVM)

The model is trained using labeled reviews where each review is marked as either **Fake** or **Genuine**.

| AI Technique | Purpose |
|---------------|---------|
| NLP | Understand review text |
| TF-IDF | Convert text into numerical features |
| Logistic Regression | Binary classification |
| Naive Bayes | Text classification |
| SVM | Alternative classifier |

## Challenges

This project has several limitations.

* AI predictions are not always correct.
* Fake reviews continuously evolve, making detection more difficult.
* Some genuine reviews may be incorrectly classified as fake.
* Large, high-quality labeled datasets are required for good performance.
* Ethical considerations should be taken into account because incorrectly labeling a genuine review as fake could negatively affect honest users or businesses.

The system should therefore assist human moderators rather than replace them completely.

## What next?

This project could be improved in many ways.

Possible future developments include:

* Support for multiple languages.
* Browser extension for shopping websites.
* Real-time fake review detection.
* Deep learning models such as BERT.
* Explainable AI to show why a review was classified as fake.
* Detection of fake reviewer accounts in addition to fake reviews.
* Mobile application for consumers.

To build a production-ready version, additional datasets, cloud deployment, and advanced deep learning knowledge would be required.

## Acknowledgments

* Building AI course by the University of Helsinki and Reaktor.
* Kaggle for publicly available datasets.
* Scikit-learn documentation.
* NLTK documentation.
* Python community for open-source machine learning tools.
