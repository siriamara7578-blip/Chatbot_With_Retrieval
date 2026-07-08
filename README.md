# Chatbot_With_Retrieval
# Chatbot with Retrieval

## Project Overview

This project implements a simple Retrieval-Based Chatbot using Python and Machine Learning. Instead of generating new responses, the chatbot retrieves the most relevant answer from a predefined knowledge base by comparing the user's question with stored questions using TF-IDF vectorization and Cosine Similarity.

This project demonstrates the fundamentals of Natural Language Processing (NLP) and information retrieval.

---

## Objective

The objective of this project is to build a chatbot that can:

* Accept user questions.
* Search a knowledge base for the most relevant information.
* Return the best matching answer.
* Demonstrate a simple Retrieval-Augmented approach.

---

## Features

* Retrieval-based chatbot
* Predefined knowledge base
* TF-IDF text vectorization
* Cosine Similarity for matching questions
* Interactive chatbot interface
* Simple and easy to understand implementation

---

## Technologies Used

* Python
* Google Colab / Jupyter Notebook
* Pandas
* Scikit-learn

---

## Project Structure

```text
Chatbot_With_Retrieval/
│── Chatbot_With_Retrieval.ipynb
│── README.md
│── chatbot_model.pkl (Optional)
```

---

## Dataset

The chatbot uses a small knowledge base containing questions and their corresponding answers related to Artificial Intelligence and Computer Science topics.

Example topics include:

* Artificial Intelligence
* Machine Learning
* Deep Learning
* Python
* Data Science
* Natural Language Processing
* Computer Vision
* Cloud Computing
* Cyber Security
* SQL

---

## Workflow

1. Import the required libraries.
2. Create the knowledge base.
3. Convert all questions into TF-IDF vectors.
4. Accept a user query.
5. Calculate Cosine Similarity between the query and stored questions.
6. Retrieve the most similar question.
7. Display the corresponding answer.

---

## Machine Learning Technique

### TF-IDF (Term Frequency–Inverse Document Frequency)

TF-IDF converts text into numerical vectors by measuring the importance of words within a collection of documents.

### Cosine Similarity

Cosine Similarity measures the similarity between the user's question and the stored questions. The chatbot returns the answer with the highest similarity score.

---

## Example Interaction

**User:**

```
What is Machine Learning?
```

**Chatbot:**

```
Machine Learning is a subset of AI that learns from data.
```

---

**User:**

```
Explain Python.
```

**Chatbot:**

```
Python is a popular programming language used in AI and data science.
```

---

## How to Run the Project

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Install the required libraries.
3. Run all cells in order.
4. Enter a question when prompted.
5. Type `exit` to end the chatbot session.

---

## Future Enhancements

* Add a larger knowledge base.
* Support PDF and document retrieval.
* Integrate Large Language Models (LLMs).
* Develop a web interface using Flask or Streamlit.
* Improve retrieval using sentence embeddings.

---

## Conclusion

This project demonstrates the implementation of a Retrieval-Based Chatbot using TF-IDF vectorization and Cosine Similarity. It provides a simple introduction to Natural Language Processing and information retrieval while showcasing how chatbots can answer user queries using an existing knowledge base.

---

## Author

**Name:** Siri Amara

**Project:** Chatbot with Retrieval

**Internship:** ScholarX Internship
