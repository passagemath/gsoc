# passagemath GSoC ideas list


## Port to Pyodide (WebAssembly)

[Pyodide](https://github.com/pyodide/pyodide) is a Python distribution for the browser and Node.js based on WebAssembly (WASM).
Several dependencies (non-Python packages, Python libraries) have already been ported to Pyodide and are part of the Pyodide distribution.
A GSoC project would now make a subset of the passagemath distributions available in Pyodide. 
As an application, serverless interactive documentation of the passagemath library could be built, where code examples can be executed directly in the browser.

Mentor: [Matthias Köppe](https://www.math.ucdavis.edu/~mkoeppe/)

Length: 350 hours


## Full integration of Normaliz

[passagemath-polyhedra](https://pypi.org/project/passagemath-polyhedra/) contains interfaces to [Normaliz](https://www.normaliz.uni-osnabrueck.de/), the state-of-the-art library by Bruns et al. for computations with polyhedra, cones, lattice points, etc.
By far not all features of Normaliz are exposed in passagemath-polyhedra. 
A GSoC project would expand the existing interface, aiming for full coverage.

Mentor: [Matthias Köppe](https://www.math.ucdavis.edu/~mkoeppe/)

Skills: Solid knowledge of polyhedral geometry or/and commutative algebra, Python experience

Length: 90 to 350 hours


## Full integration of Macaulay2

Mentor: [Matthias Köppe](https://www.math.ucdavis.edu/~mkoeppe/)

Length: 90 to 350 hours


## Integration of Sage with proof assistants / theorem provers / SMT systems / constraint programming systems

Mentor: [Matthias Köppe](https://www.math.ucdavis.edu/~mkoeppe/)

Rquired skills: Solid knowledge of a system such as LEAN, Isabelle, CVC5, MiniZinc; Python experience

Length: 350 hours


## Enhanced optimization solver interfaces for Sage

Mentor: [Matthias Köppe](https://www.math.ucdavis.edu/~mkoeppe/)

Skills: Solid knowledge of linear optimization, Python experience, ideally experience with Python optimization interfaces

Length: 90 to 350 hours

See [sagemath/sage#26511: Use Python optimization interfaces: SCIP, cvxpy, PuLP, Pyomo, cylp...](https://github.com/sagemath/sage/issues/26511)


## Connecting manifolds and optimization

Mentor: [Matthias Köppe](https://www.math.ucdavis.edu/~mkoeppe/)

Skills: Solid knowledge of nonlinear optimization, basic knowledge of differential geometry, Python experience, ideally experience with Python optimization interfaces

Length: 350 hours

See [sagemath/sage#26511](https://github.com/sagemath/sage/issues/26511), [sagemath/sage#30525](https://github.com/sagemath/sage/issues/30525)
