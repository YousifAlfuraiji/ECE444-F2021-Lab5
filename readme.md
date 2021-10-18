# ECE444 Lab 5 - Forentend Design
By: Yousif Al-Furaiji

This repo is a clone of https://github.com/nelaturuk/education_pathways

## Activity 1: Screenshot
![Acitivity 1](https://user-images.githubusercontent.com/47069889/137664552-f37869af-6688-4565-9ce2-349f582410b1.png)

## Activity 6: Screenshot and Question Response
![Activity 6](https://user-images.githubusercontent.com/47069889/137664570-c10268a2-58e0-4f95-bcd6-e6e036c76ab1.png)

The new UI has a much more readable table. In the old UI, the text in some of the columns did not align with the header text which can cause issues as a person would have to slow down reading while going through many entries in the table. In the new styled UI, the table columns are properly spaced out using padding and text align CSS properties. The new table is also more readable due to the different color header.

# CARTE Education Pathways

## Description
Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

## Setup Instructions

### With Docker



## Repository files:

`./Procfile ./wsgi.py` *tells gunicorn how to run the program*

`./environment.yml  ./requirements.txt` *specifies python requirements for anaconda and pip respectively*

`./__init__.py` *main flask code*

`./readme.md` *this file*

`./resources:` *contains datasets used in the program*

`course_vectorizer.pickle df_processed.pickle`

`course_vectors.npz       graph.pickle`

`./static:` *contains any static elements of the webpage, in this case just the CARTE logo*
`CARTE_logo.jpg`

`./templates:` *contains flask templates for rendering HTML*

`_formhelpers.html course.html       index.html        results.html`
