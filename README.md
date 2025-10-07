## Minimal_Immrax for ROS2
This is a clean, minimal version of immrax without NN functionality, linrax, or any other bells and whistles beyond the basic MM reachability functionality. It is also a customized version that fixes some issues the official immrax repo has with working within the RTA-GPR pipeline.

This is a lightweight package that could also be easier to use for raspberry pi onboard computation.



## Immrax Itself
`immrax` is a tool for interval analysis and mixed monotone reachability analysis in JAX.

Inclusion function transformations are composable with existing JAX transformations, allowing the use of Automatic Differentiation to learn relationships between inputs and outputs, as well as parallelization and GPU capabilities for quick, accurate reachable set estimation.

For more information, please see the full [documentation](https://immrax.readthedocs.io).

## Installation
No installation needed! This is set up as a ROS2 package with no executables. It can be imported into any python ROS2 script after cloned into the workspace src folder and built with colcon.