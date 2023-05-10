# constrained-particles

Interactive particle simulation with constraints - each particle must stay equidistant from two other particles. Check it out at [mklilley.github.io/constrained-particles](https://mklilley.github.io/constrained-particles/).

## Back story

Back in July 2022, I participated in a nature workshop in one of London's ancient woodlands. As part of the workshop, we did an activity that allows us to experience how complex systems behave. This activity involved each participant choosing 2 other participants (buddies you might say). Everyone's task was to stay equidistant from their buddies. When the activity began, everyone moved around in a way that was difficult to predict and I wondered whether such a system would ever settle down into equilibrium. So, I made a physics simulation to explore this question.

## Understanding the interactive simulation

You can play with this simulation at [mklilley.github.io/constrained-particles](https://mklilley.github.io/constrained-particles/). There are several controls and buttons. Here is what they do:
- **Max speed** - the higher this is, the faster the particles move around. The reason this is not simply called speed is because the speed is determined by forces between particles that push them towards an equidistant position. Max speed ensures the particles don't continue to move faster and faster over time.
- **Friction** - This provides resistance to motion. Although particles experience no force when they are equidistant from their buddies, they will continue to overshoot this equidistant position without some friction.
- **Number of particles** - Changes the number of particles in the simulation (min = 3)
- **Toggle connections** - The default is to display lines and arrows from a particle to its buddies. You can toggle this on and off using this control
- **Toggle distances** - In the bottom right corner of the screen, you'll find a metric that tells you how close the particles are to reaching the desired state where each particle is equidistant from its 2 buddies. When `Total distance deviation = 0` the simulation has reached that state. You can toggle on and off the display of this metric using this control
- **Reset** - Restarts the simulation without resetting the other parameters you've chosen.