Yuanou Shen

This repo is a clone of https://github.com/nelaturuk/education_pathways

**Activity 1**

![Activity 1](https://user-images.githubusercontent.com/90863981/135778903-93611b1b-e43d-4c40-b4c2-2a598b355aa2.PNG)

**Activity 2**

![Activity 2](https://user-images.githubusercontent.com/90863981/135784460-626161d1-096c-407c-846e-ca0ea6f9e164.PNG)

**Activity 3**

![Activity 3](https://user-images.githubusercontent.com/90863981/135779711-253cf237-4575-4bde-ad10-7e2ebe7cae0e.png)

**Activity 4**

![Activity 4 (1)](https://user-images.githubusercontent.com/90863981/135780490-a15d3e0a-7785-4dc4-ab50-3089e5ff6b6d.PNG)
![Activity 4 (2)](https://user-images.githubusercontent.com/90863981/135780500-fdd437bd-7838-4a8a-b610-5a48ea32be46.PNG)

**Activity 5**

Functional requirement: The tool should implement a login system. Users should be able to create an account where they can write down notes (such as which courses they find interesting).

Non-functional requirement: The tool should have a more colorful user interface. In my opinion, the current user interface is very minimalistic and does not have a lot of colors. I would suggest adding more colors to make it more visually appealing. 




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
