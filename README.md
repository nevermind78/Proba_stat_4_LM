# Proba_stat_4_LM
# Courses <img src="https://assets.datacamp.com/production/course_24364/shields/original/shield_image_course_24364_20200812-1-16vdo9s?1597254250" width=100 height=100 alt="MD">

> It's commonly said that data scientists spend 80% of their time cleaning and manipulating data and only 20% of their time analyzing it. The time spent cleaning is vital since analyzing dirty data can lead you to draw inaccurate conclusions. Data cleaning is an essential task in data science. Without properly cleaned data, the results of any data analysis or machine learning model could be inaccurate. In this course, you will learn how to identify, diagnose, and treat a variety of data cleaning problems in Python, ranging from simple to advanced. You will deal with improper data types, check that your data is in the correct range, handle missing data, perform record linkage, and more!

[![Anaconda version](https://sal.as/images/installing-anaconda-on-wls/anaconda_horizontal.png](https://badge.fury.io/js/courses-md)

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Requirements](#requirements)
- [Getting started](#getting-started)
- [What sorcery is this?](#what-sorcery-is-this)
- [Documentation](#documentation)
- [Examples](#examples)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->



## Requirements

* [Git][git] 2+
* [Node.js][node] 8+



## Getting started

Install the [Yeoman generator][generator-courses-md] to get started:

```bash
npm install -g yo generator-courses-md
```

Create a directory in which to write your courses. Go into it and run the generator:

```bash
mkdir courses
cd courses
yo courses-md
```

Run `yo courses-md --help` or read the [project's documentation][generator-courses-md] to see what options are available.



## What sorcery is this?

Courses MD allows you to write Markdown which will be automatically transformed
into HTML slides.

The resulting HTML files are [Remark][remark] slides and Courses MD uses
[md2remark][md2remark] to process the Markdown, so you should familiarize
yourself with these 2 tools to know what you can do.



## Documentation

The documentation is written with Courses MD itself:

* Read it [as Markdown on GitHub](https://github.com/MediaComem/courses-md/tree/master/subjects/documentation#readme)
* Read it [as HTML slides on GitHub Pages](https://mediacomem.github.io/courses-md/latest/subjects/documentation/)



## Examples

Take a look at these [COMEM+ web development courses][comem-webdev] which were written with Courses MD, for example:

* [Git Branching][comem-webdev-git-branching]
* [REST APIs Introduction][comem-webdev-rest]



[comem-webdev]: https://github.com/MediaComem/comem-webdev#subjects
[comem-webdev-git-branching]: https://mediacomem.github.io/comem-webdev-docs/2017/subjects/git-branching/
[comem-webdev-rest]: https://mediacomem.github.io/comem-webdev-docs/2017/subjects/rest/
[generator-courses-md]: https://github.com/MediaComem/generator-courses-md
[generator-courses-md-docs]: https://github.com/MediaComem/generator-courses-md#readme
[git]: https://git-scm.com
[md2remark]: https://github.com/AlphaHydrae/md2remark
[node]: https://nodejs.org
[remark]: https://remarkjs.com/#1
