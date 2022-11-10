# automata-bug-visualizer

This repository contains a visualizer that can be used to test automata-encoded BUG algorithms.

BUG algorithms are algorithms for navigation in space with obstacles, given that the agent has only limited sensors and memory.
The algorithms BUG1 and BUG2 have been proposed for two-dimensional space with polygonal obstacles, however, similar algorithms
exist for other spaces. This project uses two-dimensional discrete spaces with square cells.

Yet another feature is how to encode the algorithm itself. Here, we use a _finite state machine_, or an _automaton_,
to represent the whole program, following the [Automata-Based Programming](https://en.wikipedia.org/wiki/Automata-based_programming_%28Shalyto%27s_approach%29)
paradigm by [Anatoly Shalyto](https://en.wikipedia.org/wiki/Anatoly_Shalyto).

It was initially not clear whether one can implement a BUG algorithm using an automaton with a sane number of states,
and what runtime environment (actions and predicates) is required for that. However, after some research it was found to be possible,
and now you can experiment with that. Using this visualizer, you can create an automaton that solves the problem. Try it!
