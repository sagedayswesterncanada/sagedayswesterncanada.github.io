---
title: Activities
---

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

## Plenary talks

We will have a few of plenary talks (list will be announced as soon as it is
confirmed), no more than one each day.

## Labs and tutorials

We will also have labs and tutorials aimed at beginners, including:
- What is Free and Open Source Software (FOSS).
- Installing SageMath.
- Basics of SageMath.
- Basics of the terminal.
- Basics of git and GitHub.
- Getting your code in Sage.

If you want a particular topic to be discussed, please ask us in the
application form.

## Contributions to Sage

We will strongly encourage (first) contributions to SageMath. Participants can
come with their own topic, discuss topic ideas with the organizers, or pick one
in the list below. These subjects are self-contained, achievable during the
workshop and suitable for a first contribution to SageMath.

### Drinfeld modules

- Implement solutions to the *discrete logarithm problem* and the *inversion
problem* Drinfeld modules; see the original paper by T. Scanlon [*Public key
cryptosystems based on Drinfeld modules are
insecure*](https://math.berkeley.edu/~scanlon/papers/dmc7aug00.pdf), or §A.2.1
of [A. Leudière's thesis](https://theses.fr/2024LORR0109).\
    *(Proposed by: Antoine Leudière)*

- Implement orders (or *annihilators*) of elements in the module of points of a
  Drinfeld module over a finite field.\
    *(Proposed by: Antoine Leudière)*

### Function fields

- Sage's function field machinery has improved significantly in recent years,
but still has room for improvements to both speed and functionality.\
*(Proposed by: Vincent Macri)*

### Linear algebra

- Make the variable of the following characteristic polynomial less ambiguous:
    ```
    sage: my_matrix = diagonal_matrix([x, x, x])
    sage: my_matrix.characteristic_polynomial()
    x^3 - 3*x*x^2 + 3*x^2*x - x^3
    ```
    *(Proposed by: Antoine Leudière)*

# Schedule of the plenary sessions

TBD
