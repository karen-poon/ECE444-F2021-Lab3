# CARTE Education Pathways

Name: Karen Poon

This repo is a clone of https://github.com/nelaturuk/education_pathways.

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

## Activites

### Activity 1

![activity1](https://user-images.githubusercontent.com/48849101/135701531-f8c6d853-1d05-4499-b7b0-a9dcd7bbe3aa.PNG)

### Activity 2

![activity2](https://user-images.githubusercontent.com/48849101/135701533-5cff4959-87c8-4142-aec9-3d38f599c226.PNG)

### Activity 3

![activity3](https://user-images.githubusercontent.com/48849101/135701536-c5aa3a86-7b94-49c1-b801-afc8ae82659d.PNG)

### Activity 4
![activity4-1](https://user-images.githubusercontent.com/48849101/135701538-571cc6b8-c16c-4607-86d0-148108c8f91e.PNG)
![activity4-2](https://user-images.githubusercontent.com/48849101/135701541-bf216b60-acfd-49df-b0e2-ce1e272c3d74.PNG)

### Activity 5

Functional Requirement:

I would like to improve the “Search Terms” function. Currently, it can only search by keywords, but not by course code. For example, if I search for “ECE421”, no result will show up; but if I search for “machine learning”, it will show up as the first result, along with other relevant courses. Some users might want to type the course code as a shortcut to search quicker. Therefore, users should have the ability to search by course code and/or keywords. The code should be implemented in a way that it queries from both course name and course code. 

Non-functional Requirement:

I would like to make it more responsive. Currently, the contents are initialized within the window width, but the font looks very small on mobile views. Users need to zoom in and move the page continuously to read the full description. This is not a good user experience and should be avoided. We should set the viewport with device width and a scale of 1.0, and apply different layouts for different screen sizes.

