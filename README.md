
# SAT Solver

[![Build Status](https://travis-ci.org/ben-marshall/sat-solver.svg?branch=master)](https://travis-ci.org/ben-marshall/sat-solver)
[![Documentation](https://codedocs.xyz/ben-marshall/sat-solver.svg)](https://codedocs.xyz/ben-marshall/sat-solver/)

A simple SAT Solver based on the AC-3 Algorithm

---

This is a simple SAT solver based on the AC-3 Algorithm. It takes sets of
boolean expressions over a set of one or more variables, and computes whether
the expression(s) are *satisfiable*, that is: can be evaluated as true for
some set of inputs.

The aim is to use this as a testbed for experimenting with SAT Solvers,
looking at how they can be optimised for space/time complexity, and eventually
implemented in hardware.

