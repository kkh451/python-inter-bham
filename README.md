# Introduction

This is an exemplar repository made by following the University of Birmingham flavour of the [Intermediate Research Software Development Skills In Python](https://github.com/bham-carpentries/python-intermediate-development) course.
It is based on the [Python Intermediate Inflammation](https://github.com/carpentries-incubator/python-intermediate-inflammation) template repository provided for the course. It also provides [tags](https://github.com/bham-carpentries/python-intermediate-inflammation/tags) for the repository at the end of each section.

## Purpose

This repository is intended to be used as a reference or starting point for learners who have missed a particular section of the course.
Presently, the `main` branch represents the state of the repository at the end of section 3.
Fork this repository if you wish to continue from a particular section (see below).

> [!IMPORTANT]
> When forking this repository, remember to **uncheck** the box which says to copy the `main` branch only.

This software project is not finished, does not contain a LICENCE file, the code is currently failing to run and contains some code style issues. 
It is used as a starting point for the course - issues will be fixed and code will be added in a number of places during the course by learners in their own copies of the repository, as course topics are introduced.

### Reset to the end of a section

This repository provides tags for its state at the end of a given course section. These can be used to continue the course from a particular point.
For example, to continue from the end of section 1, reset your fork of this repository:

```bash
git switch main               # make sure you are on the main branch
git reset --hard section-1
git push origin main --force  # force push the reset main branch
```

## Tests

Several tests have been implemented already, some of which are currently failing.
These failing tests set out the requirements for the additional code to be implemented during the workshop.

The tests should be run using `pytest`, which will be introduced during the workshop.
