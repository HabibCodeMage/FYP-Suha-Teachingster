# FYP-Suha-Teachingster

## ChatBot Tarining

For chat bot tarining we have different Intents.

## Intents

The chatbot in this repository recognizes the following intents:

### Greeting

- **Tag**: greeting
- **Patterns**: "hi", "hello", "hey", "good morning", "good afternoon", "good evening", "hey there", "greetings", "nice to meet you", "howdy", "salutations", "what's up", "yo", "hi there", "hiya", "who are you?"
- **Responses**:
  - "Hi, I am a robot and my name is Suha."
  - "Hello, I am a robot and my name is Suha."

Add more intents if you want to add and customize it yourself.

## BERT

For BERT we have traned our dpr dense passage retriver which have data set of the following type.
### DBMS Question-Answer Dataset

This repository contains a dataset of questions and answers related to Database Management Systems (DBMS).

### Dataset Description

The dataset consists of a collection of question-answer pairs covering various aspects of DBMS.

### Question

"What is a database management system?"

### Answer

"A database management system (DBMS) is a software system that allows users to define, create, maintain, and control access to a database."

## Contexts

The question-answer pair is accompanied by relevant contexts that provide additional information and sources. Here are a few examples:

1. **Database Management System (DBMS) - GeeksforGeeks**
   - [Link to Source](https://www.geeksforgeeks.org/database-management-system-dbms/)
   - Score: 5 out of 5

2. **Introduction to Database Management System (DBMS)**
   - [Link to Source](https://www.studytonight.com/dbms/database-management-system.php)
   - Score: 4 out of 5

3. **What is a Database Management System (DBMS)?**
   - [Link to Source](https://searchsqlserver.techtarget.com/definition/database-management-system-DBMS)
   - Score: 3 out of 5

## Usage

You can use this dataset for various purposes, such as training question-answering models, conducting research, or enhancing your understanding of DBMS concepts.

## ROBERTA BASE SQUAD TWO

For Roberta Base Sqaud Two squad data set was used to train the model.

# SQuAD (Stanford Question Answering Dataset)

This repository contains the Stanford Question Answering Dataset (SQuAD), a collection of question-answer pairs built from Wikipedia articles.

## Dataset Description

SQuAD is a dataset for machine reading comprehension tasks. It consists of questions posed by crowdworkers on a set of Wikipedia articles, where the answer to each question is a segment of text within the corresponding article.


## Dataset Format

The dataset is provided in a JSON format and consists of multiple articles, each containing multiple paragraphs, and each paragraph containing multiple question-answer pairs.

### Example:

```
{
  "data": [
    {
      "title": "Article Title",
      "paragraphs": [
        {
          "context": "Paragraph text goes here...",
          "qas": [
            {
              "question": "Question text?",
              "answers": [
                {
                  "text": "Answer text.",
                  "answer_start": 123
                }
              ]
            }
          ]
        }
      ]
    }
  ]
}
```
## Usage

You can use this dataset for various purposes, including training and evaluating question answering models, conducting research on natural language understanding, and benchmarking performance on machine reading comprehension tasks.
