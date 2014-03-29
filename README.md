---
layout: ots
title: README 
---

This is a friendly how-to to program and hardware hack on the Arduino device.
This course is run by OpenTechSchool.
First, a quick refresher on the course:

At the end of the course students will have achieved the following

* Know what an Arduino is
* Install and use the Arduino IDE on their computer
* Modify and Downlaod the Blink program

Nice to have obectives

* Attach a simple bread board circuit to the Arduino (design is already provided)
* Load a simple program to control the bread board
* Modify it and load again


We are hoping students have written a little code before but we can probably cope with
any who have not.

# Class format

At OpenTechSchool we tend to go *practical* and *at your own pace*.

Practical meaning that we aren't big on theory, or requiring that people
understand something completely before using it. We aren't expecting any of the
students to become computer scientists. Generally programming for our students
is a way of solving some practical problem. If they want to accomplish it with
LISP or a spreadsheet is entirely up to them.

At your own pace means that we provide access to the complete course notes at
the beginning of the session. Then students can progress individually. Some
students will get through very quickly, others will take some time, and most
will finish the core work with time to spare. The core work should be
completable by everyone. To keep things interesting we supply various
additional topics which are entirely optional.

A class schedule looks like this:

    1200 - Students still arriving, writing name tags, setting up laptops.
    1230 - Introductions, wifi instructions and location of coursework.
    1235 - Students learn stuff.
    1545 - Thankyous, maybe demonstrations.

As you can see, the schedule just has a big chunk of 'learn stuff'. We like to
keep things open.

# Author Guide

So, fork this repository. The guide is written as a [Jekyll](http://jekyllrb.com/)
site, hosted on GitHub pages. It's set up so you can just write pages in Markdown.
A markup guide is below.

Course work goes under `core/` or `extras/`. It's all linked together by
`index.md` in the root direcory.

* `core/` covers the basic goals of the course. In this course that means
  setting up Git, creating a GitHub account, creating a repo, etc etc. Put any
  images in `core/images/`
* `extras/` are all the interesting things people can do once they have
  completed the basics. Things like hosting with GitHub Pages, or doing Pull
  Requests and exploring GitHub can be done here. Put any images in
  `extras/images/`

It's easiest to start at the end. Think of a fun and interesting topic to add to
the extras. Then you can copy this file to get an idea for formatting.

# Markup Guide

# First level section
## Second level section
### Third level section
#### Fourth level section

* List item
  * Sub item
  * Sub item 2
* List it m 2

1. Ordered list item
2. Ordered list item 2
3. Ordered list item 3
  * Sub item 1
  * Sub item 2
4. Ordered list item 4
  1. Ordered sub item 1
  2. Ordered sub item 2
5. Ordered list item 5


*emphasis text* for emphasis

**strong text** for strong

Getting literal with `backticks`

    Or use an indent of 4 spaces,
    to get yourself a code block,
    that looks lovely.

> Do a bit of blockquoting. You can still reflow the text as much as you like.
Newlines are awesome.
And made of win.

[links for nerds](http://slashdot.org)

[links for internal stuff](section8.html)

This is a horizonal rule:

******

If you want to highlight some ruby code:

    def foo
        puts 'foo'
    end

Bit of command line:

    $ holla holla
    get dolla
    $ 

For a more complete list of languages see [highlight.js](http://softwaremaniacs.org/media/soft/highlight/test.html)

