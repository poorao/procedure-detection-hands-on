# Procedure Detection Hands-On
This repository contains all the resources required for Procedure Detection Hands-on session. This is a binary classification problem to detect a list of sentences as procedure or not. We will learn to solve this problem by engineering features specific to the procedures or instructions in the procedure. 

## Data
- We will use the data scraped from Libre help - help.libreoffice.org and Ubuntu help - help.ubuntu.com 
- These are the list of steps which are both procedures and non-procedures
- Data can be found in the data folder

## Installation
```
pip install -r requirements.txt
python -m spacy download en_core_web_sm
```
## Code
- All the code can be found in the Google colab notebook linked below.

[![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Ghm2jTRoX7LxPNyeGUF8bguh9fse0CyY?usp=sharing)

### FastText Feature Extraction
[![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1dr5blHTQ5PPVfHIWGme4aBmVY9lLAK2H?usp=sharing)