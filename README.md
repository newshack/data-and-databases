# Data and Databases

Columbia University, Lede Program

Tuesdays and Thursdays, May 24th 2016 through July 7th 2016, 10am

[Allison Parrish](http://www.decontextualize.com/), instructor.

Office hours: By appointment only.

For FERPA reasons, I ask that you e-mail me [at my Columbia
address](mailto:ap3328@columbia.edu) when discussing any matters related to
this class or your grade. Personal or professional inquiries can go to [my
personal address](mailto:allison@decontextualize.com).

## Description

Consideration of both the scientific and social implications of counting, of
turning the world into bits. Through the process of gaining fluency in the use
of Python, students will spend some time thinking through representations of
core "data types" like time, location, text, image, sound and relationships (or
networks), and the computational "affordances" associated with each. Students
will study several common metaphors for organizing and storing data – from
structureless key-value stores, to a single table or spreadsheet, to the
"multiple tables" of a relational database. We will also discuss ideas behind
publishing or sharing data, moving from HTML documents and Web 1.0 to data
services and APIs in Web 2.0, to semantics in Web 3.0. Student work and
discussion will underscore the reality that data are plentiful and circulate
and interact in a kind of informational ecosystem. As researchers, our students
will be called on both to access and to publish data products.

Notes for previous versions of the course:

* [2014](https://github.com/ledeprogram/courses/tree/master/databases)
* [2015](https://github.com/ledeprogram/courses/tree/master/databases-2015)

## Homework assignments

There will be six homework assignments in this class, each assigned on Thursday
and due the following Tuesday before the beginning of class. The homework
assignments are designed to test and expand your knowledge of the technical
concepts introduced in class. Each homework assignment is worth 10% of your grade.

With the exception of the first assignment, all homeworks will take the form of
an IPython Notebook that you fill in and send to a TA for grading. (We'll
discuss the specifics of this in class.)

## Grading

- 40% Attendance and participation
- 60% Homework assignments (10% each)

## Schedule and notes

### Week 1 (May 24 and 26)

* Orientation
* Student introductions
* [SQL basics](SQL_notes.md)

Homework #1 (due May 31): Read and respond to the following.

* [Relational and Non-Relational Models in the Entextualization of
  Bureaucracy](http://computationalculture.net/article/relational-and-non-relational-models-in-the-entextualization-of-bureaucracy)
  by Michael Castelle
* [Literature is not Data: Against the Digital
  Humanities](https://lareviewofbooks.org/article/literature-is-not-data-against-digital-humanities)
  by Stephen Marche
* [Machine
  Bias](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing)
  by Julia Angwin, Jeff Larson, Surya Mattu and Lauren Kirchner

These essays each address the limits and consequences of data-driven analysis
and public policy. Your response should take the form of a brief e-mail (no
more than 3-5 paragraphs) [sent to me](mailto:ap3328@columbia.edu). In your
response, describe the critique of one or more of the essays and discuss *how*
(if at all) you might incorporate their critique(s) into your practice as a
journalist. Also in your e-mail, include and comment on a link to an essay or
article that you feel "speaks to" the points raised in one or more of the
essays (e.g., agrees with, provides a counterexample, expands upon, responds
to).

### Week 2 (May 31 and June 2)

* SQL continued
* IPython/Jupyter Notebooks.
  [Basics](http://nbviewer.jupyter.org/github/jupyter/notebook/blob/master/docs/source/examples/Notebook/Notebook%20Basics.ipynb),
  [Running
  Code](http://nbviewer.jupyter.org/github/jupyter/notebook/blob/master/docs/source/examples/Notebook/Running%20Code.ipynb), [Markdown tutorial](http://commonmark.org/help/)
* [Installing Python
  Libraries](http://rwet.decontextualize.com/book/installing-python-libraries/)
  (other notes TK)
* [Using SQL in Python](SQL_in_Python.ipynb)
* [SQL and CSVs](CSV_to_SQL.ipynb)

To install Jupyter Notebook on OSX:

    sudo pip3 install jupyter

Depending on how you've installed Python on Windows, try:

    pip3 install jupyter
    py -3 -m pip install jupyter

[More info here.](http://jupyter.readthedocs.io/en/latest/install.html)

Homework #2 (due June 7): [Working with SQL](Homework_2.ipynb).

### Week 3 (June 7 and 9)

* [Scraping HTML with Beautiful Soup](Scraping_HTML.ipynb)

Homework #3 (due Jun 14): [Web scraping](Homework_3.ipynb).

### Week 4 (June 14 and 16)

* Working with unstructured data
* [List
  comprehensions](https://github.com/ledeprogram/courses/blob/master/databases/01%20Lists.ipynb)
  (scroll down, needs to be translated to Python 3)
* [Strings and regular
  expressions](https://github.com/ledeprogram/courses/blob/master/databases-2015/03_Strings_and_Regular_Expressions.ipynb) (note: needs to be translated to Python 3!)

Homework #4 (due June 21): [List comprehensions and regular expressions](Homework_4.ipynb)

### Week 5 (June 21 and 23)

* [HTML to SQL](HTML_to_SQL.ipynb)

Homework #5 (due June 28): [SQL schema design](Homework_5.ipynb)

### Week 6 (June 28 and 30)

* [Making a Flask app](Web_applications.ipynb) (the template files referenced
  can be found in the `templates` folder of this repository)

Homework #6: [Web applications](Homework_6.ipynb).

### Week 7 (July 5 and 7)

* [The Twitter API](Twitter_API.ipynb) (see completed `lake_bot.py` in this
  repo)
* Homework review
* If we have time: [Intro to NLP with TextBlob](http://rwet.decontextualize.com/book/textblob/)

*Extra credit homework assignment*: Create and deploy a Twitter bot. The bot
should either respond to updates on an external data source (like [NYT
4th Down Bot](https://twitter.com/nyt4thdownbot) or [Congress
Edits](https://twitter.com/congressedits)) or iterate through/randomly select
data for presentation (like [Census
Americans](https://twitter.com/censusamericans)). This extra credit assignment
can make up for up to 5% of your final grade. Complete this assignment by July
12th. [Send me](mailto:ap3328@columbia.edu) a link to the Twitter bot and a zip
file with the source code for the bot.
