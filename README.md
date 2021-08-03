Adversarial Method for Showing Lower Bounds in EasyCrypt
========================================================

This repository contains mechanizations in EasyCrypt of the
adversarial method for showing lower bounds.

This is joint work between Boston University faculty

* [Mark Bun](https://cs-people.bu.edu/mbun/) (mbun [at] bu [dot] edu)
* [Marco Gaboardi](https://cs-people.bu.edu/gaboardi/) (gaboardi@bu.edu)
* [Alley Stoughton](http://alleystoughton.us) (stough@bu.edu)

in collaboration with Boston University doctoral student

* [Weihao Qu](https://www.bu.edu/cs/profiles/weihao-qu/) (weihaoqu@bu.edu)

and Stuyvesant High School student and BU RISE program intern

* Carol Chen

We have a general EasyCrypt framework for expressing lower bounds problems

 * [`AdvLowerBounds.eca` - general adversarial lower bounds framework](../main/AdvLowerBounds.eca)

as well as a general EasyCrypt framework for expressing upper bounds problems

 * [`UpperBounds.eca` - general upper bounds framework](../main/UpperBounds.eca)

We have applied these frameworks to

 * [proving a lower bound for computing the or (disjunction)
   function of a list of booleans](../main/OrFunctionLB.ec)

 * [proving a lower bound for searching for the least index into an
   ordered list (in which duplicate elements are allowed) where a
   given element is located, as well as proving an upper bound for
   the binary search algorithm for this problem](../main/searching)

We also have some [work-in-progress](../main/work-in-progress).
