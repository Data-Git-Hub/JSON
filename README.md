# P4: Employ Requests, JSON, NLP & Engage

[P4: Employ Requests, JSON, NLP & Engage](https://github.com/Data-Git-Hub/JSON)

## Introduction
In this project, I explore how to interact with web APIs, process JSON responses, and perform sentiment analysis using natural language processing (NLP) techniques in Python. By leveraging tools such as requests, json, and the spaCy library with the spacytextblob extension, I demonstrate how to fetch text data—such as song lyrics or poems—from online sources, analyze sentiment, and store results in structured JSON files. This project highlights essential data analytics skills including API interaction, text processing, and writing reusable functions. All work is conducted within a Jupyter Notebook and version-controlled using GitHub, with final outputs exported to HTML to ensure accessibility and reproducibility.

### Tasks
Perform the tasks described in the Markdown cells below.  When you have completed the assignment make sure your code cells have all been run (and have output beneath them) and ensure you have committed and pushed ALL of your changes to your assignment repository.  Make sure you have [installed spaCy and its pipeline](https://spacy.io/usage#quickstart) and [spaCyTextBlob](https://spacy.io/universe/project/spacy-textblob)  Every question that requires you to write code will have a code cell underneath it; you may either write your entire solution in that cell or write it in a python file (`.py`), then import and run the appropriate code to answer the question.  This assignment requires that you write additional files (either JSON or pickle files); make sure to submit those files in your repository as well.

---

## Windows Setup Instructions

Open a PowerShell terminal in VS Code. 
Create local project virtual environment, activate it, and install packages. 
When asked to use the new .venv click yes. 

```shell
py -m venv .venv
.\.venv\Scripts\activate
py -m pip install --upgrade pip setuptools wheel
py -m pip install -r requirements.txt
```

---

## macOS/Linux Setup Instructions

Open a default terminal in VS Code. 
Create local project virtual environment, activate it, and install packages. 

```zsh
python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install --upgrade pip setuptools wheel
python3 -m pip install -r requirements.txt
```

---

## Tell VS Code to use .venv

Open the Command Palette: Press Ctrl + Shift + P (Windows) or Cmd + Shift + P (Mac/Linux)
Then type: Python: Select Interpreter
Press Enter.

Look for the interpreter with .venv in the path.
Click on that interpreter to select it.
Confirm it's selected: You should see the Python version and .venv path in the lower-left status bar of VS Code.

---

## Working on the Project

Open the .ipynb Jupyter notebook file in VS Code. 
Run the entire notebook before you start to edit. 
As you make progress, use Git to add, commit, and push your work to your GitHub repo.

```shell
git add .
git commit -m "describe the change here"
git push -u origin main
```

---

### Introduction

### Imports

### Tasks

### Section 1. Accessing and Storing Song Lyrics Using a Public API

### Section 2. Sentiment Analysis of Song Lyrics Using spaCyTextBlob

#### Section 2.1. Interpretation Polarity and Subjectivity Scores

#### Section 2.2. Interpretation Polarity and Subjectivity Scores

### Section 3. 

### Section 4. 

---

# Requests, JSON, and basic NLP with spaCy

Complete the tasks in the Python Notebook in this repository.
To be submitted for credit, all changes must be committed and pushed to this repository (do not create your own repository unless instructed to on the course website).

## Rubric

* (Question 1) Lyrics printed: 1 pt
* (Question 1) File created and submitted with notebook: 1 pt
* (Question 2) Correct polarity reported: 1 pt
* (Question 2) Question answered thoughtfully: 1 pt
* (Question 3) Function defined as specified: 1 pt
* (Question 3) Song lyrics retrieved and stored in separate files (0.5 pts/song): 2 pts
* (Question 4) Polarity scores printed (with appropriate label containing song title, .25 pts/song): 1 pt
* (Question 4) Questions answered thoughtfully: 2 pts

---

## Authors

Contributors names and contact info <br>
@github.com/Data-Git-Hub <br>

---

## Version History
- P4 Sect - 2.0 - Modify requests-json-nlp.ipynb, README.md
- P4 Sect - 1.1 - Modify requests-json-nlp.ipynb, README.md
- P4 Sect - 1.0 - Create icon folder, 4thpog.gif; Modify requests-json-nlp.ipynb, README.md
- P4 Init - 0.0 - Create requests-json-nlp.ipynb, requirements.txt; Modify README.md
## Test History