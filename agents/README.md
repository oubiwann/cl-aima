## Agents (Subsystem of AIMA Code)

[comment]: # (Changed by: Peter Norvig, 30-Oct-1996)

The <b>agents</b> subsystem covers the code in Part I of the book: the
basic environment simulator <tt>run-environment</tt>; simulations for
the vacuum and wumpus worlds, and some simple agents for those worlds.
It also includes the abstract class <tt>grid-environment</tt>, which
is an environment that supports physical objects located in a
two-dimensional rectangular grid of spaces.  It serves as the basis
for the vacuum and wumpus worlds, as well as for more complex
environments like the shopping world of Chapter 8.
