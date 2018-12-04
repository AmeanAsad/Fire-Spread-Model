# Fire-Spread-Model
A stochastic approach to modeling wildfires using cellular automata concepts


The fire spread model can be used using the object fire_model
    intitialize_fire() will start a fire at a random spot. 
    take_fire_step() will take a firey stochastic step towards the fire spread. 
    
 There are a few physical parameters that I attempted to integrate:
  1. Wind direction which is a vector to determine the direction of wind. 
  2. Moisture levels, using a randomly generated matrix. 

Example of Generated simulation after 50 steps:
 ![Simulation Image](https://github.com/AmeanAsad/Fire-Spread-Model/blob/master/fire_sim1.jpeg?raw=true)
 
