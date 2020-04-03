---
id: tools-we-want
title: Tools we want
---

# Tools we want

Some of these will be really important, but also don't be afraid to write up something you'd like to see built even if it is a small quality of life improvement for students and volunteers. These can make excellent small project ideas for graduates, and even current students, sometimes with mentoring.

## bigger tools

### TODO: coordinate the marking of homework

### really fast, uninvasive formative assessment tools

perhaps along the lines of [socrative](https://socrative.com/)

### a kahoot that supports code excerpts

Kahoot is good but creation and maintenance of quizzes is too time consuming because code-excerpts have to be screenshotted to be included as reference images when questions are on coding.

### quick data pool / theme generator (mostly for live-coding)

A tool or set of tools to provide teachers with example context and data for them to use in examples and live-coding, to avoid them falling back on "list of mentor names"

These data could be strings, or json objects

- (examples of list of city names, languages, famous space ships from movies, fictional characters)
- it will be useful to (eventually) accompany the data with sample ideas for use:
  - example: fictional characters:
    - analyse the numeric age property to find the youngest and oldest, character, or those characters within an age range.
    - list all the character whose first names start with E

If this draws from a google spreadsheet that would avoid the need for an interface to be built for later content generation.

Data sets:
https://github.com/awesomedata/awesome-public-datasets

Here's my list of no auth APIs - the tool shouldn't need to draw from APIs - static data is fine, but some of these APIs are fun.
https://docs.google.com/document/d/1LS961Lm3-bZ2tmQAgP9BH4HJTAlczVnQ10vPJcKSLig/edit#heading=h.ph2asob9cqxq

## Misc small tools

### Tool: zoom "who's missing"

Find or write a Zoom integration to help show not simply attendance but a **live** view of who is **NOT** in the class?
As we start with fully-remote classes, this is one of the key questions - it's really easy to miss that one of your 20 students has dropped off and is missing the session.

First simplest version:

```
Inputs: meeting id, list of expected user names (or email addrs, possibly)
Outputs: list of user names who are currently not in the meeting, timestamp
```

### Tool: random student picker (very low priority, fun authentic task for a student project)

- Something to randomly pick a participant from the current live list of participants
  - pedagogy note, as a teacher often you'll want to be more strategic than this allows, and to "cold call" instead, but sometimes the random generator can add some fun. See https://teachlikeachampion.com/blog/cold-call-not-popsicle-sticks-hands-key-differences-matter/
- it could have a fun spin-the-wheel animation
- it should be _really_ quick to use
- it should work well when given little screen space, to allow the teacher to keep it small in a corner.
- advanced: some students with good p5.js skills might want to animate