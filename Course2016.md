Domain-Specific Languages of Mathematics
========================================

News
----

2016-01-25: The date of the exam has been changed to 2016-03-15, 14:00.

2016-01-25: Due to administrative reasons, we are down to one TA,
Irene.  Thanks Victor for your contributions to the course!

2016-01-22: First assignment has been posted! 

Aim
---

The course will present classical mathematical topics from a computing
science perspective: giving specifications of the concepts introduced,
paying attention to syntax and types, and ultimately constructing DSLs
of some mathematical areas mentioned below.

Learning outcomes as in the [course syllabus]
(https://www.student.chalmers.se/sp/course?course_id=24179).

Course team
-----------

- Teacher : Cezar Ionescu (cezar AT)
- Examiner : Patrik Jansson (patrikj AT)
- Teaching assistants: Irene Lobo Valbuena (lobo AT), Víctor López
  Juan (lopezv AT); from 2016-01-25 only Irene
- Intern : Adam Sandberg Ericsson (saadam AT)

Schedule
--------

- Lectures Mondays 10-12 (in ED) and Fridays 13-15 (in EB)

- Exercises Wednesdays 13-15 and Thursdays 10-12 (in Ft-4011)

- Guest lectures in Week 4 (Monday 2016-02-08 and Friday 2016-02-12)

- Exam: 2016-03-15 afternoon.  Re-exam: 2016-08-23 afternoon.

Assignments
-----------

The assignments are to be solved in **teams of three**.

- [Assignment01](Assignments/Assignment01.lhs), due 2016-02-02 23:59.
  Submission via Fire, at [URL](https://xdat09.ce.chalmers.se/2016/lp3/dslm/)

Lectures
--------
*Note*: the summaries are written as a mixture of markdown and lhs.
To compile them, you can use a suitably modified form of this
[Makefile](aux/Makefile) and the [bib](aux/ref.bib) and
[template.tex](aux/template.tex) files.

- [Lecture 01, Introduction](Lectures/Lecture01.lhs).  [Slides](Lectures/slides01.pdf).
- [Lecture 02, Logic and Functional Programming, Part I](Lectures/Lecture02.lhs).
- [Lecture 03, Logic and Functional Programming, Part II](Lectures/Lecture03.lhs).  
- [Lecture 03, Logic and Functional Programming, Part II](Lectures/Lecture03.lhs).  
- [Lecture 04, Proofs and Programs in Mathematics](Lectures/Lecture04.lhs).

Exercises
---------

- [Exercises for 2016-01-20](Exercises/Exercises-2016-01-20.lhs).
  [Solutions](Exercises/FOL.lhs) to selected exercises; you can use
  these for the assignment if you wish.
- [Exercises for 2016-01-21](Exercises/Exercises-2016-01-21.lhs).
- [Exercises for 2016-01-27--28](Exercises/Exercises-2016-01-27--28.lhs). You will need the file [AbstractFOL.lhs](Exercises/AbstractFOL.lhs).

Literature
----------

There is no course textbook.  We will use many sources: references
will be provided in the lecture summaries.

Some important references:

### Functional programming

- **Thinking Functionally with Haskell**, Richard Bird, Cambridge
  University Press, 2014
  [URL](http://www.cs.ox.ac.uk/publications/books/functional/)
- **Introduction to Functional Programming Using Haskell**, Richard
  Bird, Prentice-Hall, 1998.  A previous (but *very* different)
  version of the above.
- **An Introduction to Functional Programming**, Richard Bird and Phil
  Wadler, Prentice-Hall, 1988. A previous (but *very* different)
  version of *both* of the above.

### DSLs

- **Functional Programming for Domain-Specific Languages**, Jeremy
  Gibbons.  In *Central European Functional Programming School 2015*,
  LNCS 8606, 2015.
  [URL](http://link.springer.com/chapter/10.1007%2F978-3-319-15940-9_1)

  This is currently *the* standard reference to DSLs for the
  functional programmer.

- **Folding Domain-Specific Languages: Deep and Shallow Embeddings**,
  Jeremy Gibbons and Nicolas Wu,
  ICFP 2014. [URL](http://www.cs.ox.ac.uk/publications/publication7584-abstract.html)

  Available at the same link: a highly recommended
  [short version](http://www.cs.ox.ac.uk/people/jeremy.gibbons/publications/embedding-short.pdf)
  and the two videos of Jeremy presenting the most important ideas
  of DSLs in a very accessible way.

- **Programming Languages**, Mike Spivey.  Lecture notes of a course
  given at the CS Department in Oxford.  Useful material for
  understanding the design and implementation of embedded DSLs.
  [URL](http://spivey.oriel.ox.ac.uk/corner/Programming_Languages)

- **Domain Specific Languages**, Martin Fowler, 2011.
  [URL](http://martinfowler.com/books/dsl.html)

  The view from the object-oriented programming perspective.

### The computer science perspective

- **Communicating Mathematics: Useful Ideas from Computer Science**,
  Charles Wells, *American Mathematical Monthly*, May 1995.  [URL](http://www.cwru.edu/artsci/math/wells/pub/pdf/commath.pdf)

  This article was one of the main triggers of this course.

### Mathematics

- **The Language of First-Order Logic, 3rd Edition**, Jon Barwise and John
  Etchemendy, 1993.  Out of print, but you can get it for one penny
  from Amazon UK.  A vast improvement over its successors (as Tony
  Hoare said about Algol 60).

- **Mathematics: Form and Function**, Saunders Mac Lane, Springer 1986.
  An overview of the relationships between the many mathematical
  domains.  Entertaining, challenging, rewarding.
  [Fulltext from the library](http://chalmers.summon.serialssolutions.com/sv-SE/search?ho=t&q=Mathematics%3A%20Form%20and%20Function)

More references will be added in due course.
