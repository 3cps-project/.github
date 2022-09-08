# 3-CPS: An Environment-Centric IR for Compiling Strict Higher-Order Languages

3-CPS is an NSF supported project on intermediate representations, analyses,
and compiler optimizations for strict higher-order programming languages.
At the center of our project lies an annotated CPS-based IR called 3-CPS.
The general annotation mechanism allows "facts" determined by program analysis
and "decisions" determined by optimization policies to be associated with the
program's representation. One of the most important classes of fact annotations
is explicit information about the environment structure required to manage bindings
of variables; this is designed to be closely connected to the run-time machine resources
needed for these bindings (heap records, stack frames and registers). This information is
key to mapping the source language efficiently onto these resources.

## Publications

> [**Analyzing binding extent in 3CPS**](https://dl.acm.org/doi/10.1145/3547645) <br>
> by Benjamin Quiring, John Reppy, and Olin Shivers. <br>
> *Proceedings of the ACM on Programming Languages*,
> Volume 6, Issue ICFP, Article Number 114,
> August 2022. <br>
> The artifacts associated with this paper can be found at either
> <https://github.com/3cps-project/icfp2022-artifacts> or
> <https://zenodo.org/record/6958457>.

> [**3CPS: The Design of an Environment-Focussed Intermediate Representation**](https://doi.org/10.1145/3544885.3544889) <br>
> by Benjamin Quiring, John Reppy, and Olin Shivers. <br>
> *Proceedings of the 33rd Symposium on Implementation and Application
> of Functional Languages (IFL ’21)*,
> September 2021.

## People

The 3CPS project is led by John Reppy (University of Chicago) and
Olin Shivers (Northeastern University).  The currently active participants
are (in alphabetical order):

* Nathan Cantor (UChicago)
* Benjamin Quiring (University of Maryland; previously at Northeastern)
* John Reppy (UChicago)
* Olin Shivers (Northeastern)
* Skye Soss (UChicago)
* Byron Zhong (UChicago)

## Support

The 3CPS project is supported, in part, by the National Science Foundation
under grant numbers 2212537 and 2212538.
