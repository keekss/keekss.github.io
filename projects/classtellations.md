---
layout: project
type: project
image: images/classtellations-progress.png
title: Fathom
permalink: projects/fathom
# All dates must be YYYY-MM-DD format!
date: 2020-12-18
labels:
  - Web development
  - Academic Advising
---

<img style="display: inline-block; height: 300px; margin-left: auto; margin-right: auto;" src="../images/classtellations-progress.png">

For our ICS 314 Final Project, my group and I visual guide a tool to help with academic advising and student planning.

Classtellations<sup>1</sup> provides a drag-and-drop interface for students to experiment with the timings of different courses (with arrows showing prerequisites) to plan an optimal path toward graduation.  If prerequisites are not met in an attempted drag-and-drop, the system will alert the user and abort the operation.

The drag-and-drop Progress tab also synchronizes with a Transcipt tab, showing a time-sorted list with a status and number of credits for each course.  The progress page can be printed as a PDF, and the right-most tab includes a list of UH Manoa academic advisors and program requirements.

My portion of the project focused on the drag-and-drop interface, for which I used the libraries React Beautiful DnD (Drag and Drop) and React Xarrows.  The page uses a database (MongoDB) of classes to form an inverted index of semesters from which the display is made and re-updated from the database as click-and-drag operations modify it.

Currently, the system is implemented for ICS students following the General Track, with a default starting arrangement of course timing.  I hope to have a chance, in the future, to add other ICS tracks and eventually other department majors.

For further details, free to check out our project home page [here](https://uh-classtellations.github.io/) and our github repository [here](https://github.com/uh-classtellations/uh-classtellations).  Our project is also deployed on Digital Ocean [here](https://classtellations.xyz/).

<sup>1</sup> The name "Classtellations" is a portmanteau of "class" and "constellations" to match UH Manoa's STAR System's voyaging & navigation theme.  The "stars", i.e. courses, form a constellation to guide you, a craft pioneered by ancient Pacific celestial navigators.