# Puddle-World
Continuous variant of the standard discrete state/action space grid world

The puddle world involves an agent trying to traverse a continuous grid space to reach within a certain distance from a target location

The state space is continuous (as a two-dimensional coordinate space)
The action space is discrete (based off of the 360 degree mark intervals). An action is determined by an angle (with a set magnitude for the vector movement)

In the puddle world, there are a few additions which can create interesting environments for learning:
 - Puddles (similar to cliffs in the standard grid world setup): if the agent travels into a puddle (determined by a circle), the agent respawns at the start location
 - Jackpot: if the agent traverses the jackpot area, there is an added reward for this

There are many other possible extensions of this environment, which can create interesting RL schemes for continuous state/action space environments
