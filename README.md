# hungalg

A python implementation of [the Hungarian Algorithm](http://en.wikipedia.org/wiki/Hungarian_algorithm). Initially made to solve [the 345th Project Euler problem](https://projecteuler.net/problem=345).

### Problem description

The Hungarian Algorithm solves the assignment problem, defined as follows:

> There are a number of agents and a number of tasks. Any agent can be assigned to perform any task, incurring some cost that may vary depending on the agent-task assignment. It is required to perform all tasks by assigning exactly one agent to each task and exactly one task to each agent in such a way that the total cost of the assignment is minimized.

The hungalg module can both minimize and maximize ('profit') a given matrix.

### References

[1] http://csclab.murraystate.edu/bob.pilgrim/445/munkres.html

[2] http://en.wikipedia.org/wiki/Hungarian_algorithm