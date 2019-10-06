### Aerial slung-load position tracking under unknown wind forces

The notebooks, described next, are meant to be read in conjunction with the companion pdf document "aerial slung-load position tracking under unknown wind forces.pdf".

In the notebook
- "controller_after_backstepping", we provide all the five simulations
- "model_and_change_of_coordinates.nb", we provide the equations of motion, the change of coordinates and the change of inputs
- "backstepping_steps.nb", we specify the desired trajectory, the model parameters, the control parameters, and we perform the 6 backstepping steps
- "bounded integrator.nd", we provide several bounded control laws for double integrators
- "figures.nb", we make provide the code to generate the plots found in the article (with nice titles, and legends)
- "lower bound on lyapunov function.nb", we provide the code that generates a figure, found in the report, which is concerned with the construction of a positive definite lower bound function to a Lyapunov function
- "notes of projector for update laws.nb", we provide some notes on the smooth update law
- "stability_atractivity_of_set_disturbance_removal.nb", we provide the code that generates a figure, found in the report, which is concerned with stability, and lack thereof, or equilibria sets when disturbance removal is performed.