"# cuny_data698_capstone" 

## CUNY DATA698
### Topic Modeling for Forensics Analysis of Text-Based Conversations
#### Michael Ippolito
#### May 2024

This is part of a series of Python Jupyter notebooks in support of my master's capstone project. The aim of the project is to study various methods of preprocessing, topic modeling, and postprocessing text-based conversation data often extracted from electronic devices recovered during criminal or cybersecurity investigations.

The Jupyter notebooks used in this project are as follows:

| Module | Purpose |
|--------|---------|
| eda1.ipynb | Exploratory data analysis of the four datasets used in the study. |
| modeling1.ipynb | Loads and preprocesses the datasets, performs various topic models, postprocesses the topic representations. |
| survey1.ipynb | Generates conversation text and topic representations to submit to Mechanical Turk. It later parses the results and incorporates them into my own hand-labeled results. |
| survey2.ipynb | Loads Mechanical Turk survey results and evaluates them for quality based on reading speed and attention questinos. |
| eval1.ipynb | Evaluates the topic modeling and survey results based on topic coherence, semantic quality, and topic relevance. |

The study uses the following four datasets:

1. Chitchat (download from https://pypi.org/project/chitchat-dataset/)
2. Topical Chat (download from https://github.com/alexa/Topical-Chat)
3. Ubuntu Dialogue (download from https://www.kaggle.com/datasets/rtatman/ubuntu-dialogue-corpus)
4. Enron Email (download from https://www.loc.gov/item/2018487913/)

For further details and attribution, see my paper in this github repo.
