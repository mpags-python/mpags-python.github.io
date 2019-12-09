## Student evaluation of module

### Students at Nottingham

* Please visit [BlueCastle](https://bluecastle-uk-surveys.nottingham.ac.uk) → SET/SEM Surveys
* MSc students should see PHYS4038 module listed
* PhD students will need to enter a "PIN number":  V6Q6S8
* (Interpret "Moodle" as "course webpage")

### PhD students at other institutions

* Please use [this anonymous form](https://forms.office.com/Pages/ResponsePage.aspx?id=7qe9Z4D970GskTWEGCkKHlMauSc2cM9NlviB4UBUGJtUQ0wwNEQwMkxSM09FWE0wSVU5NFBHREREWC4u).


## Course information

This postgraduate course is designed to give a general introduction to the Python
programming language and its wider ecosystem, with a focus on the elements most
important for data analysis and scientific research.

The course is aimed at students on the [MSc Machine Learning in Science][MLiS] (MLiS)
programme at the University of Nottingham (for which it is PHYS4038) as well as
first-year PhD students at the University of Nottingham and a number of other
institutions, via the Midland Physics Alliance Graduate School ([MPAGS][MPAGS]
[AS1][AS1]). Others may be able to join, on request, both for credits or on a more
informal (unassessed) basis. Teaching sessions will be delivered to students at remote
institutions via online live-stream. Recordings and materials will also be available for
asynchronous learning.

As students taking this module are expected to hold an undergraduate degree in a science
subject, a limited level of prior programming experience (in any language) is
assumed. Please note that, although the majority of the course will be useful for all
science postgrads, there will be some subject-specific content, including an overview of
key tools for astronomers.

## Joining the course

MSc students should enrol via the University of Nottingham
[module enrolment form][MSc-enrolment], after discussing their options with their tutor.

PhD students should enrol for the module via the
[MPAGS module sign-up page][MPAGS-enrolment]. If you are enrolling late, please also
[email the convenor][SPB].

Any others wishing to join should [email the convenor][SPB].


## Lecturer

The course is taught by **Dr Steven Bamford**. Outside of teaching sessions he can be
contacted via [email][SPB], or at his office: A112b in the CAPT building (#25 on the
[campus map][MAP]).

## Timetable and format

Teaching sessions will held each **Monday at 1pm**.  The main course starts on **7th October
2019** and runs for ten weeks (ending 9th December).
Preceding this there is a MLiS-only introductory session on Monday 30th September.

For Nottingham students the course will be delivered face-to-face, in room A13 in the
George Green library. Students may use the desktop computers in the room, or bring their
own laptops.

The live-stream link for remote students will be made available in advance.  Note that
all that is required is an internet connection and a web-browser -- we will not be
using the usual MPAGS access node infrastructure. In order to receive this link you must
have enrolled on the course (in one of the ways described above).

Each session will consist of a lecture, lasting up to one hour, followed -- after a short
break -- by an exercise class for local students. Remote students may complete the
exercises in their own time.

The course will be assessed by the development of a complete Python program performing
some scientific analysis of your choice.

## Topics

A preliminary outline of the topics is given below. This may be slightly altered and
expanded as the course progresses.

* Session 1-2: Introduction to Python
* Session 3: Staying organised
* Session 4: Numerical Python and Plotting
* Session 5: Scientific Python
* Session 6: Data handling
* Session 7: Python for specialists (astronomy and theory, but useful for all)
* Session 8: **Presentations (MSc only)**
* Session 9: Bayesian inference and deep learning in Python
* Session 10: Robust, fast & friendly code

## Lecture materials

Materials accompanying the course will appear here as the course progresses.

* Session 0 (MSc students only): [slides](assets/slides/2019/python2019_session_0.pdf)
* Session 1: [slides](assets/slides/2019/python2019_session_1.pdf)
* Session 2: [slides](assets/slides/2019/python2019_session_2.pdf)
* Session 3: [slides](assets/slides/2019/python2019_session_3.pdf)
* Session 4: [slides](assets/slides/2019/python2019_session_4.pdf)
* Session 5: [slides](assets/slides/2019/python2019_session_5.pdf)
* Session 6: [slides](assets/slides/2019/python2019_session_6.pdf)
* Session 7: [slides](assets/slides/2019/python2019_session_7.pdf)
* Session 8: MSc presentations
* Session 9: [slides](assets/slides/2019/python2019_session_9.pdf)
* Session 10: [slides](assets/slides/2019/python2019_session_10.pdf)

For advance reference, [here are the slides used for last year's MPAGS course][SLIDES2008].

## Exercises

Solutions to the exercises will appear here as the course progresses.

* Session 1: [notebook](https://nbviewer.jupyter.org/github/mpags-python/exercises/blob/master/Exercises1.ipynb)
* Session 2: [notebook](https://nbviewer.jupyter.org/github/mpags-python/exercises/blob/master/Exercises2.ipynb)
* Session 4: [notebook](https://nbviewer.jupyter.org/github/mpags-python/exercises/blob/master/Exercises4.ipynb)
* Session 5: [notebook](https://nbviewer.jupyter.org/github/mpags-python/exercises/blob/master/Exercises5.ipynb)

The exercises and some examples shown in lectures can be <a
href="https://github.com/mpags-python">found on Github</a>. You are strongly advised to avoid consulting the solutions until you have tried the problems yourself!

## Assessment

To qualify for MSc or MPAGS credits, in addition to attending the majority of lectures
you will need to produce a Python program. Your program may address any scientific
purpose you like, e.g. data analysis, simulation, modelling, experiment control,
visualisation, etc.  Ideally the program will do something that is relevant for your
research projects, particularly in the case of MPAGS students.

In addition to producing the code itself, MSc students will also give a presentation on
their ongoing development, and a short final report. Percentages below refer to mark
weightings for students on MSc programmes.

MPAGS credits are awarded for reasonable attendance and an acceptable final code
submission; intermediate submissions for feedback are encouraged, but optional. No
report or presentation are required.

### Code

Your program should (as a rough guide)…

* be written as an executable module (.py file) or Jupyter notebook (.ipynb)
* do something meaningful: analyse real data or perform a simulation
* define at least two user functions (but typically more) 
* make use of appropriate specialist modules
* produce at least one informative plot 
* comprise >~ 50 lines of actual code (excluding comments, imports and other ‘boilerplate’)
* contain no more than 1000 lines in total (if you have written more, please isolate an individual element)

You should submit the source code (.py/.ipynb file), together with pdf/png files of the output plot(s).

Your code should be submitted in the form of a GitHub repository containing the source
code (.py/.ipynb file), together with pdf/png files of the output plot(s).  The
repository should also contain a README file explaining the functionality of the code
and explaining how it should be run.

<a href="https://classroom.github.com/a/K4tUSkL0">Click here to setup the GitHub repo for submitting your coursework code.</a>

To indicate that you have submitted your code for marking and feedback, create a branch
named `sub1`, `sub2` or `sub3` as appropriate for the submission stage.

Further details regarding setting up your GitHub repository for submission will be given
in the lectures.

There will be three submission deadlines (at 3pm on the respective dates):
* initial work submitted by **1 Nov** *(5%)*
  * a README describing what you intend your code to do and a rough outline of the code
  (classes, functions, snippets, comments, pseudocode)
  * *you will receive feedback within about one week, with the aim of helping you make
    good choices regarding modules and the structure your code*
* ongoing work submitted by **15 Nov**  *(15%)*
  * a roughly working version of your code -- it is intended that this be incomplete and/or
    contain bugs (but try to make it reasonably easy to understand!)
  * *you will receive feedback within about one week, with the aim of improving the
      structure, style and efficiency of your code*
* final submission by **13 Dec** *(40%)*
    * your final working code

### Presentation

MSc students must also deliver a 5 minute presentation *(20%)* during the workshop on 25 Nov,
describing their on-going development.

### Report

Along with their final code, MSc students must additionally submit, a short (2--3 sides
of A4) report *(20%)* describing the purpose of the code, any key design decisions, the outputs,
and scope for improvements.


## Preliminaries

If you intend to use your own computer, then, before the course begins, <strong>you should ensure that you have working Python interpreter available, ideally the Anaconda distribution</strong> (see below). For this course you are strongly recommended to use a recent version (3.4+).  Linux and OSX already have Python installed, but you are not recommended to use them!  Instead, install a version of Python specifically for your research, as described below. If you have any difficulties installing and running Python, please ask for help during – or shortly after – the first session.

You should use Python 3.  While Python 2 is still available and in use, most projects
have moved over to Python 3 by now. Note that Python 3 is not backward compatible with
Python 2 due to a small number of significant changes, i.e. code that works with Python
2 will not necessarily work with Python 3.  Some of the differences will be explained
during the course.


## Getting Python

You are <strong>highly</strong> recommended to install Python using the freely-available <a href="https://www.anaconda.com/download/" title="Anaconda" target="_blank">Anaconda</a> distribution.  This gives you the most convenient route to a standalone Python 3 installation with most (if not all) of the modules you need easily available.

If you are missing a Python module, you can usually get it with one of the following (in the order you should try them):

* `conda install <modulename>`
* `pip install <modulename>`

Beware that you can have multiple versions of condo and pip on one computer, each associated with a particular Python distribution (and perhaps a specific Anaconda environment).  Make sure are using the correct one!

Using your operating system's own version of Python, or installing Python in any other
manner, is just asking for trouble.

## Writing Python

While you can write Python in any text editor, you should choose one with support for
Python code, i.e. providing automatic formatting, code highlighting, and ideally integrated
documentation. If you're old-school, Emacs and Vim are good choices. More modern options include:
* [`Spyder`][SPYDER] is an integrated scientific development environment (IDE), which comes
ready-installed with Anaconda.
* [`PyCharm`][PYCHARM] is an excellent Python-specific editor and IDE. It is free for educational
and academic use.
* [`Jupyter`][JUPYTER] provides in-browser notebooks, which are very good for interactive
  analysis use, or early stages of code development.


[MLiS]: https://www.nottingham.ac.uk/pgstudy/courses/physics-and-astronomy/machine-learning-in-science-msc.aspx
[MPAGS]: https://warwick.ac.uk/fac/sci/physics/mpags
[AS1]: https://warwick.ac.uk/fac/sci/physics/mpags/modules/comp/python
[SPB]: mailto:steven.bamford@nottingham.ac.uk
[PYCHARM]: https://www.jetbrains.com/pycharm/
[SPYDER]: https://www.spyder-ide.org
[JUPYTER]: https://jupyter.org
[MAP]: https://www.nottingham.ac.uk/sharedresources/documents/mapuniversitypark.pdf
[MPAGS-enrolment]: https://warwick.ac.uk/fac/sci/physics/mpags/signup/
[MSc-enrolment]: https://www.nottingham.ac.uk/studentservices/services/module-enrolment.aspx
[SLIDES2008]: slides2018
