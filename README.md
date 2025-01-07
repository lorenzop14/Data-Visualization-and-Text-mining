# Data-Visualization-and-Text-mining
This project focuses on analyzing medical text using Named Entity Recognition (NER) tags in the IOB format. The goal is to predict the appropriate tags for each word in the text based on the provided annotations.

The project includes:

    Data exploratory analysis of the dataset for token classification in the anatomical domain.
    
            Key Steps: Data loading, missing values analysis,Label mapping for NER tags to unify classes (e.g., merging "B-" and
            "I-"), Statistical analyses of sentence length, token frequency, and POS (Part-of-Speech) distribution, Visualization
            through   word clouds and topic modeling using LDA.
            
    Application of some Neural Network approaches to evaluate sequential models (LinearSVC, LSTM, BiLSTM, GRU) for token
    classification
    
            Key Steps: Data preparation, rebalancing, and one-hot encoding of labels, Evaluation of LinearSVC;
            
            Neural network implementation:LSTM, BiLSTM, GRU;
            
            Use of metrics (accuracy, F1-score, recall) and class-weighted loss.
            
    Implementation of a Named Entity Recognition (NER) model using BioBERT (useful for medical texts).
    
            Key Steps: Dataset preparation: Balancing, mapping labels, and preparing data for the Hugging Face framework;
            
            BioBERT fine-tuning: Token alignment and model configuration for token classification, Training using a data collator
            and monitoring metrics (precision, recall, F1-score), evaluation with metrics, confusion matrix, and qualitative
            analysis of predictions.

For all the three main parts of the project interactive dashborads that show the main results are implemented.
