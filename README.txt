# description

This is an agent-based simulation where the agents harvest energy from their
environment and divide.

The agents have 3 different parameters whose value is transmitted to its
offspring (with mutations);

- yield: the higher this parameter, the faster the agent is and the more it
  depletes resources in its environment.

- rotation: the higher this parameter, the more frequently the agent
  changes its direction.

- division frequency: the higher this parameter, the more frequently the agent
  divides

The color of the agents reflect the value of their parameters; red is for
yield, green is for rotation and blue for division frequency.

The environment into which the agents live is a closed square grid with square
meshing. Each tile of the grid contain a certain amount of energy which can be
depleted by the agents. Energy automatically replenishes progressively and
diffuses to the neighboring tiles.

# how to make it work

Go find the raphael js library and put raphael.min.js in the same folder as the
html file, then open the html file with a web browser.
