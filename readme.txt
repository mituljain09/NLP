Instructions for Running Sentiment Analysis Models

This project contains implementations of sentiment analysis models using logistic regression with Bag-of-Words (BoW) representation and BERT (Bidirectional Encoder Representations from Transformers). Follow the instructions below to run the models:

1. Requirements:
   - Python 3.6 or later
   - Libraries:
     - numpy==1.19.5
     - pandas==1.3.3
     - torch==1.9.0
     - transformers==4.9.2
     - scikit-learn==0.24.2
     - matplotlib==3.4.3
     - wordcloud==1.8.1

2. Installation:
   - Install Python 3.6 or later from https://www.python.org/.
   - Install the required libraries using pip:
     ```
     pip install numpy==1.19.5 pandas==1.3.3 torch==1.9.0 transformers==4.9.2 scikit-learn==0.24.2 matplotlib==3.4.3 wordcloud==1.8.1
     ```

3. Running the Models:
   - Run logistic regression with BoW:
     ```
     python logistic_regression_bow.py
     ```
   - Run BERT model:
     ```
     python bert_model.py
     ```

4. Additional Notes:
   - Ensure that you have the Rotten Tomatoes dataset in the appropriate directory. Dataset link: https://huggingface.co/datasets/rotten_tomatoes
   - Modify the file paths and hyperparameters in the code as needed.
   - For any issues or questions, please contact [Your Name] at [Your Email].
