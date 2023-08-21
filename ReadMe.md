# ResumeSimplify
## Problem Statement
The primary goal of the "ResumeSimplify" project is to develop a robust and accurate Named Entity Recognition model that can transform unstructured resume data into a structured tabular format. This will enable recruiters, HR professionals, and decision-makers to quickly and efficiently review key information from a large number of resumes, aiding in effective decision-making and candidate evaluation.

## Dependencies
* Python (version 3.x)
* `json` module
* `random` module
* `logging` module 
* `sklearn` library 
* `spacy` library 
* `spacy.gold` module
* `spacy.scorer` module 

## Requirements
This project requires the training data to be in JSON format.

## Installation Instructions
1. Install Required Libraries:
Before running the code, you need to install the necessary libraries. You can install them using the following commands:
```
pip install spacy scikit-learn
```
2. Download spaCy Language Model:
To run the NER model, you need to download a spaCy language model. In your case, you're using the blank "en" model. You can download it using the following command:
```
python -m spacy download en
```
3. Prepare Data:
Place your training and test data files (traindata.json and testdata.json) in the appropriate file paths as mentioned in the code.

4. Run the Code