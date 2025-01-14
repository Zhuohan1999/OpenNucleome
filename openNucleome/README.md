## openNucleome

- __init__: Logs the version and imports main class from the whole_nucleus_model

- whole_nucleus_model.py: Creates the main class for the system, including the context, and controls which interactions are included during the simulation

- chromosome.py: All the interactions related to chromosome-chromosome

- speckle.py: All the interactions between speckle-speckle, and speckle-chromosome

- nucleolus.py: All the interactions between nucleolus-nucleolus, nucleolus-speckle, and nucleolus-chromosome

- lamina.py: All the interactions between lamina-other particles, and includes the nucleus deformation force when squeezing the model

- utils: The folder contains functions for calculating the contact probabilities between chromosome and nuclear landmarks (Lamina and Speckles), and the contact probabilities among chromosomes. In addition, it also contains the coordinate transformation from OpenMM default unit to reduced unit, and the creation of the last configuration in one trajectory.
