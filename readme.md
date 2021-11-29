# SceneChecker

SceneChecker is a library for verifying scenarios involving vehicles executing complex plans in large cluttered workspaces. SceneChecker converts the scenario description into to a hybrid automaton, and attempts verification by exploiting the symmetries in the underlying dynamics. It can use any existing reachability analysis tool as a subroutine although this implementation has been tested with DryVR and Flow*. The details of the theory are available in the publications listed on the [SceneChecker page](https://publish.illinois.edu/scenechecker/). In experiments, SceneChecker shows up to 20x speedup in verification time (over using DryVR and Flow* directly).

