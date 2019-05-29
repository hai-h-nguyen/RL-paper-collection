HIRO algorithm.

Contribution:



Experiments: Perform comparisons on four Ant tasks: Ant Gather, Maze, Push, and Fall requires the agent to combine locomotion
and object manipulation. Compared with FuN, SNN4HRL, VIME using 10 randomly seeded trials. Also perform hyper-parameter searches
to find a competitive baselines to the proposed approach.

Notes: To me, the approach of using hiearchy is similar to cascade PID controllers in classic control theory. In control theory,
the inner loop is tune first by fixing the output of the outer loop (setpoint of the inner loop). It also requires the inner loop
to have faster dynamics. Wonder if I can find a similar relationship with RL using hiearchy.
