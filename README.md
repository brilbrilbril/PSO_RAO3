# Swarm Intelligence
Final project from Advanced Machine Learning Course from Telkom University

Implementation of PSO and RAO-3 Algorithm

## PSO
Particle Swarm Optimization is Optimization algorithm inspired by bird flocking and fish schooling, depends on particle's position and velocity.

### Steps
1. Initialize population or particles
2. Calculate the fitness score using objective function
3. Compare the fitness score of old particles and current particles
4. Choose the particles that have best fitness score
5. Update the velocity using eq 1 (vi)
6. Update the position using eq 2 (xi)
<img width="314" alt="image" src="https://github.com/brilbrilbril/PSO_RAO3/assets/90541357/330cfd86-b416-48ee-aa1b-981da02276e2">

source: https://or.stackexchange.com/questions/7025/how-to-interpret-velocity-computation-in-particle-swarm-optimization

7. Repeat 2 - 6 until the stopping criteria satifsied
   
   
### Result
<img width="428" alt="image" src="https://github.com/brilbrilbril/PSO_RAO3/assets/90541357/cc5f3204-0954-4c05-b870-6aa242867837">

## RAO-3 Algorithm
RAO-3 is Optimization Algorithm based on interaction between its best solution and worst solution.

### Steps
1. Initialize solution candidates.
2. Calculate the fitness score
3. Choose the solution with the best and the worst fitness score
4. Update the position of solution candidates using this eq
<img width="717" alt="image" src="https://github.com/brilbrilbril/PSO_RAO3/assets/90541357/d0246ab4-2d8b-4355-97ed-5e6039339382">

5. Compare all the solution candidates with the updated solutions, the better fitness score of the candidates will be kept
6. Updated solutions will be "old solutions" in the next iteration
7. Repeat 2 - 6 until stopping criteria is satisfied

### Result
<img width="474" alt="image" src="https://github.com/brilbrilbril/PSO_RAO3/assets/90541357/fc59bf6a-c418-4c7a-966c-1d800eac2325">


For more information, check the notebook.
