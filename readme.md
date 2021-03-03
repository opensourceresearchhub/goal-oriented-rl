### Goal-Oriented Reinforcement Learning : Mapping The Current State And A Desired State To An Action ###

The idea behind this architecture comes from humans' ability to put a goal in mind, then find strategies and actions that can take the agent from the current state to the desired state (goal). (Check the idea image). We train the network from the replay buffer to map the current state to a future state separated by a distance, along with the average of the actions that were applied between the two states.

If we want to extend the concept, we can try an architecture that maps the current state and the desired state to a sequence of actions instead of a single average action.

There is code to run both architectures on Cartpole-v1 and Mountaincar-v0 (check the code folder for that).

If you would like to contribute in any form (on code, on paper, graphics, etc.), please open a pull request or contact us. 

Contributors to this repository will be added to the final paper if published.

### Folders ###

/code contains the code to demonstrate the concept and the architecture.

/idea contains a diagram of the main concept.

/ paper contains the .tex paper along with the last generated pdf.
