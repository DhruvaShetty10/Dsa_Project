# SMS Spam Detection using Machine Learning

## Overview
This project focuses on building a machine learning model to classify SMS messages as either spam or non-spam (ham). By leveraging Natural Language Processing (NLP) techniques and supervised learning algorithms, the project aims to filter out fraudulent and unsolicited messages effectively.

## Features
- Text preprocessing including cleaning, normalization, and stopword removal
- Feature extraction using CountVectorizer and TF-IDF Vectorization
- Implementation of multiple machine learning models:
  - Logistic Regression
  - Multinomial Naive Bayes
  - Support Vector Machines (SVM)
  - Random Forest
- Performance evaluation using metrics such as accuracy, precision, recall, and F1-score

## Dataset
The dataset used contains labeled SMS messages categorized as spam or ham. It includes a balanced distribution of messages to ensure fair training and evaluation.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/SMS-Spam-Detection.git
   ```
2. Navigate to the project directory:
   ```bash
   cd SMS-Spam-Detection
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the main script to preprocess data and train models:
   ```bash
   python main.py
   ```
2. View model performance metrics and results.

## Results
The Support Vector Machine (SVM) and Random Forest models achieved the highest accuracy, with SVM reaching an accuracy of **98.27%**. Random Forest also demonstrated robust performance with balanced precision and recall.

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests for improvements and bug fixes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

