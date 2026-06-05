---
title: Activities
---

# Schedule

The tentative schedule is as follows:

{{< image src="/schedule.jpg" alt="Tentative schedule" position="center" style="width: 80%" >}}

Here are [a PDF version](/schedule.pdf) and [a list version
(PDF)](/schedule-list.pdf).

# Plenary talks

## Nils Bruin (Simon Fraser University)

*Developing a software package within a computer algebra system*

Abstract: When writing software to perform advanced mathematical computations
one generally needs to rely on preexisting libraries. Developing the software
within a computer algebra is then often the most attractive option. To maximize
the utility of the software, one should then ensure the newly developed
routines integrate well with the existing ones. There are choices to make
whether to package the software separately or aim for integration into the
larger package directly.

As a case study, we will look at the development of the period matrix
functionality for algebraic Riemann surfaces in SageMath (see
[here](https://doc.sagemath.org/html/en/reference/curves/sage/schemes/riemann_surfaces/riemann_surface.html)),
as well as a closely related package for computing Riemann Theta functions (see
[here](https://github.com/nbruin/RiemannTheta)). We review the design
considerations and decisions made for these packages in view of the different
stages in their development history and leave it to the audience if they want
to take it as a shiny example or a cautionary tale.

In addition, we will showcase the functionality of the packages to serve as an
illustration of the utility of putting the extra effort into mathematical
software to make it useful beyond the original narrow application.

## Mark Giesbrecht (University of Waterloo)


*Sparse Exact Linear Algebra: Theory, Algorithms, and Implementation*

Exact linear algebra over integers, finite fields, and related exact domains
have a rich interaction between asymptotic complexity and practical
implementation. This talk will explore the transition from dense algorithms
whose costs are governed by cubic exponents and matrix multiplication, to
sparse and black-box methods based on block Wiedemann's techniques and linear
recurring sequences. We'll pay particular attention to subcubic algorithms for
sparse exact linear algebra, including Otilde(n^2.5) integer/rational solving
and recent faster-than-matrix-multiplication methods for Smith form.

We'll also discuss how these algorithmic ideas are (and might be) realized in
software, including LinBox and Sage. The emphasis is on the feedback between
theory and implementation: black-box abstractions, blocking, preconditioning,
modular computation, lifting, and certification provide both the foundation for
improved complexity bounds and the architecture for effective exact linear
algebra software.

## Jenny Lawson (University of Calgary)

Title and abstract TBA.

# Work organization 

A few key points:
- Participants are welcome to work at their own pace and extent set their own
schedule, although meal times are fixed.
- Some days will begin or end with plenary talks or wrap-up sessions that all
participants should attend.
- Throughout the day there may be labs and tutorials about specific topics that
will only interest and be attended by participants who wish to learn about that
topic.
- Participants are encouraged to make the most out of their visit: this can
mean discussing Sage on a hike in the mountains, late-night karaoke, etc.

# Scientific content and organization

Although the organizers are number theorists, **we welcome participants from
all areas of mathematics** who are interested in Sage.

# Invited speakers
We will have plenary talks from:

- [Nils Bruin](https://www.sfu.ca/math/people/faculty/nbruin.html) (Simon Fraser University)
- [Mark Giesbrecht](https://cs.uwaterloo.ca/~mwg/index.shtml) (University of Waterloo)
- Jenny Lawson (University of Calgary)

Titles and abstracts will be posted on the website soon.

## Labs and tutorials

We will also have labs and tutorials aimed at beginners, including:
- Basics of the terminal.
- Basics of git and GitHub.
- Getting your code into Sage.

If you want a particular topic to be discussed, please ask us in the
application form.

## Contributions to Sage

We will strongly encourage (first) contributions to SageMath.
