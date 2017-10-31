Good for large number of voltage sources.

A mesh is defined as a loop that does not contain any other loop within it.

Each mesh is assigned a mesh current which flows through the loop.

* Assign mesh currents in each mesh.
* Apply KVL around each mesh in terms of the unknown mesh current and solve
  them.
* Branch currents can be found afterwards, by taking the algebraic sum of the
  loop currents that are common on individual branches.
* Solve the resulting simultaneous equations for the assumed loop currents.
