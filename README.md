# Credit Card Fraud Detection

## Project Overview

This project develops a robust fraud detection model for credit card transactions using advanced machine learning techniques. The primary goal is to enhance the detection of fraudulent activities while minimizing false positives, ultimately protecting the financial interests of customers and the company.

## Key Features

- Comprehensive analysis of 97,852 credit card transactions
- Advanced data cleaning and feature engineering (3,200+ variables created)
- Evaluation of multiple machine learning models
- Implementation of LightGBM (LGBM) as the final model
- Financial analysis and cutoff recommendation for optimal fraud detection

## Project Structure

1. Data Description
2. Data Cleaning
3. Variable Creation
4. Feature Selection
5. Preliminary Model Exploration
6. Final Model Performance
7. Financial Curves and Recommended Cutoff
8. Summary

## Technologies Used

- Python
- Pandas
- Scikit-learn
- LightGBM
- Matplotlib
- Seaborn

## Key Findings

- The LightGBM model demonstrated robust performance with scores of 0.793 on the training set, 0.785 on the testing set, and 0.593 on the out-of-time set.
- A financial analysis recommended setting the cutoff at 4% to maximize savings while effectively detecting fraud.
- The model is projected to yield significant savings, with a gain of $400 for every correctly identified fraudulent transaction and a loss of $20 for each false positive.

## Future Work

- Explore deep learning models for potentially improved performance
- Implement real-time fraud detection capabilities
- Investigate the possibility of incorporating additional data sources for enhanced accuracy

## Author

Reuben Chatterjee

## Acknowledgments

Include any acknowledgments for data sources, inspirations, or collaborators.
