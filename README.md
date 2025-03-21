Emotion Detection using Twitter Dataset and SpaCy Algorithm

Implemented an NLP-based emotion detection system to detect emotions in tweets based on supervised learning methods and lexical-resource-based approach. The project utilized the AIT-2018 dataset and utilized WordNet-Affect and EmoSenticNet as feature extraction sources along with SpaCy for text pre-processing.

Key Contributions & Methodology:

Data Preprocessing: Preprocessed tweet text by cleaning and tokenizing it using SpaCy, processing stopwords, punctuation, and stemming.

Feature Extraction: Used WordNet-Affect and EmoSenticNet to find features related to emotions in tweets.

Feature Vector Conversion: Transformed feature-extracted values to numerical formats for model training.

Supervised Classification: Used machine learning classifiers to classify emotions from text data.

System Design & Implementation: Developed system architecture through UML diagrams and executed it using Python, maintaining modularity and scalability.

Evaluation & Testing: Measured model performance using precision, recall, and F1-score metrics, with issues like language vagueness and multi-emotion text.

Technologies Used:

NLP Libraries: SpaCy, NLTK

Lexical Resources: WordNet-Affect, EmoSenticNet

Machine Learning: Scikit-learn (SVM, Decision Tree, Random Forest)

Development Environment: Python

Outcome & Future Scope:

Registered considerable accuracy for emotion categorization, but struggle persisted with tackling imprecise language and multiple-emotion paragraphs. Enhancements for the future include the application of deep models (LSTMs, transformer) to enable better contextual identification and emotion tagging.
