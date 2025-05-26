# emoji-prediction

This project presents the development of an end-to-end Natural Language Processing (NLP) pipeline aimed at performing fine-grained emotion classification and contextual emoji prediction from textual input.
 The system combines the strengths of both traditional machine learning algorithms and state-of-the-art deep learning models to deliver accurate and interpretable results.
The classification task spans 28 nuanced emotional categories, drawing from the GoEmotions dataset. Initially, the text is preprocessed using standard techniques (tokenization, stopword removal, etc.) and then vectorized using TF-IDF. Classical machine learning algorithms such as Logistic Regression, Support Vector Machine (SVM), and Random Forest are trained and evaluated to establish baseline performance.
To push the boundaries of accuracy and contextual understanding, a BERT-based deep learning model (specifically, j-hartmann/emotion-english-distilroberta-base) is fine-tuned using the Hugging Face Transformers library. The system also incorporates a context-aware emoji prediction module, further enhancing digital expression by mapping emotions to appropriate emojis. 
