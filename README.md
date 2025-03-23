# Phishing_Email_Detection

## Overview
This project implements a machine learning-based solution for detecting phishing emails. Using natural language processing techniques, the system analyzes email content to classify messages as either legitimate (safe) or phishing attempts.

## Features
- Text-based email classification
- Vector representation of email content using SpaCy
- Balanced dataset handling 
- Binary classification (Safe/Phishing)

## Dataset
The project uses a dataset containing:
- Over 18,000 labeled emails
- Balance of phishing (7,328) and safe (11,322) emails
- Text content and corresponding classification labels

## Models Used
- Naive Bayes
- K Nearest Neighbor

## Requirements
- Python 3.7+
- pandas
- spaCy
- scikit-learn
- SpaCy English language model (`en_core_web_sm`)
