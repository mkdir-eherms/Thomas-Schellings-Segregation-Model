# Thomas-Schellings-Segregation-Model

The following model is based off of Thomas Schelling’s “Dynamic Models of Segregation” (1971), which proposes a simple model of racial segregation. The Schelling model of the world is a grid; each cell represents a house. The houses are occupied by two kinds of “agents,” labeled red and blue, in roughly equal numbers. About 10% of the houses are empty.

At any point in time, an agent might be happy or unhappy, depending on its “tolerance level” of other agents in its immediate neighborhood. The neighborhood of each house is the set of eight adjacent cells. In one version of the model, the tolerance level is set such that agents are happy if they have at least two neighbors like themselves (i.e., 2/8 neighbors), and unhappy if they have one or zero.

The simulation proceeds by choosing an agent at random and checking to see whether it is happy. If so, then nothing happens; if not, the agent chooses one of the unoccupied cells at random and moves.
