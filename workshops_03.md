---
layout: page
title: About
permalink: /workshops_03/
date: 2018-02-15
---

## The next workshop

The next (and third!) workshop will run on 21-23rd March 2018. It is aimed at researchers with limited or no previous experience in programming and data analysis but who need these approaches in their research in the life sciences. If you are not sure if you are in this group, consider the following example.

Given the file `test.txt`:
~~~
> cat test.txt
Apple	5
Banana	12
Kiwi	7
Watermelon	2.54
~~~

What is the output of the `bash` command:

`> cat test.txt | wc -l`

If the file `text.txt` is then read into `R`:

`test <- read.table(file = “test.txt”, sep="\t", header = FALSE)`

What is the output of:

`> str(test)`

If you know the answers to these questions on top of your head, you are likely **not** the target audience for this workshop.

### Venue

[The University of Leeds](http://leeds.ac.uk), [Leeds, UK](http://www.leeds.ac.uk/campusmap), Room: [EC Stoner 9.90](http://students.leeds.ac.uk/site/custom_scripts/ajax_loader.php?type=room&id=99925).

### Costs

The workshop is free of charge for all BBSRC-funded researchers, as well as staff and students from the Universities of Leeds and Huddersfield. For all other participants a course fee of £170 will apply that will need to be paid before the workshop begins. Travel and accommodation costs are **not** covered by the organisers.

### Format of the course

The format of the materials and the nature of the delivery will be based on the successful [Software Carpentry](http://software-carpentry.org/) blended-learning model, where students learn by developing skills through hands-on live coding and peer programming sessions led by experienced instructors and supported by a small team of helpers. The workshop is limited to 25 participants; they will be expected to bring their own computers to the workshop.

### Preliminary programme:

- **Wednesday**

Introduction to the fundamentals of UNIX, command-line interface and shell.

- **Thursday**

Introduction to fundamentals of R and R Studio, including data and analysis reproducibility, concluded with example analysis of gene expression data.

- **Friday**

A "hackathon" day, during which participants will use skills learned in earlier days to solve a real-life data analysis problem of their choosing or a detailed walk-through a real-life dataset analysis.

The detailed programme will be available shortly before the beginning of the course.
