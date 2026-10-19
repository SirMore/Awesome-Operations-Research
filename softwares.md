# Software, Solvers, and Modeling Tools

A practical guide to Operations Research software. Commercial products are listed separately from open-source tools so users can choose according to licensing, budget, support, and deployment needs.

See also: [Solver Comparison](solver-comparison.md), [Modeling Languages](modeling-languages.md), [Libraries](libraries.md), [Tutorials](tutorials.md), and [Best Of](best-of.md).

## Contents

- [Open-Source Solvers](#open-source-solvers)
- [Commercial Solvers](#commercial-solvers)
- [Modeling Languages and Algebraic Modeling Systems](#modeling-languages-and-algebraic-modeling-systems)
- [Constraint Programming Tools](#constraint-programming-tools)
- [Simulation Software](#simulation-software)
- [Spreadsheet and Teaching Tools](#spreadsheet-and-teaching-tools)
- [Solver Benchmarking and Portals](#solver-benchmarking-and-portals)

## Open-Source Solvers

- [Bonmin](https://github.com/coin-or/Bonmin) - Open-source COIN-OR solver for convex mixed-integer nonlinear programming.
- [CBC](https://github.com/coin-or/Cbc) - Open-source COIN-OR branch-and-cut solver for mixed-integer linear programming.
- [CLP](https://github.com/coin-or/Clp) - Open-source COIN-OR simplex solver for linear programming.
- [COIN-OR](https://www.coin-or.org/) - Open-source initiative hosting optimization solvers, modeling tools, and computational OR libraries.
- [Couenne](https://github.com/coin-or/Couenne) - Open-source COIN-OR solver for global optimization of nonconvex mixed-integer nonlinear programs.
- [CVXOPT](https://cvxopt.org/) - Open-source Python package for convex optimization, including conic and quadratic programming.
- [ECOS](https://github.com/embotech/ecos) - Open-source embedded conic solver for second-order cone programming.
- [GLPK](https://www.gnu.org/software/glpk/) - GNU Linear Programming Kit for LP, MIP, and related mathematical programming models.
- [HiGHS](https://highs.dev/) - Open-source high-performance LP, MIP, and QP solver with C, C++, Python, Julia, and other interfaces.
- [Ipopt](https://coin-or.github.io/Ipopt/) - Open-source interior-point solver for large-scale nonlinear optimization.
- [lp_solve](https://lpsolve.sourceforge.net/5.5/) - Open-source mixed-integer linear programming solver and modeling library.
- [MiniZinc](https://www.minizinc.org/) - Open-source constraint modeling language and toolchain with many supported back-end solvers.
- [OR-Tools](https://developers.google.com/optimization) - Open-source Google suite for routing, scheduling, integer programming, CP-SAT, flows, and assignment problems.
- [OSQP](https://osqp.org/) - Open-source operator-splitting solver for convex quadratic programming.
- [SCIP](https://www.scipopt.org/) - Solver for constraint integer programming, mixed-integer programming, and mixed-integer nonlinear programming; source-available with academic-friendly licensing.
- [SCS](https://www.cvxgrp.org/scs/) - Open-source splitting conic solver for large-scale convex cone programs.

## Commercial Solvers

- [AIMMS](https://www.aimms.com/) - Commercial optimization modeling platform for prescriptive analytics applications.
- [AMPL](https://ampl.com/) - Commercial algebraic modeling language with broad solver connectivity and a free community edition for some uses.
- [Artelys Knitro](https://www.artelys.com/solvers/knitro/) - Commercial nonlinear optimization solver for continuous and mixed-integer nonlinear problems.
- [FICO Xpress](https://www.fico.com/en/products/fico-xpress-optimization) - Commercial optimization suite for linear, integer, quadratic, conic, and nonlinear optimization.
- [Frontline Analytic Solver](https://www.solver.com/) - Commercial Excel-based optimization, simulation, and analytics platform.
- [GAMS](https://www.gams.com/) - Commercial algebraic modeling system for mathematical programming and equilibrium models.
- [Gurobi Optimizer](https://www.gurobi.com/) - Commercial solver for LP, MIP, QP, QCP, SOCP, and related optimization models.
- [Hexaly Optimizer](https://www.hexaly.com/) - Commercial global optimization solver formerly known as LocalSolver, focused on large-scale combinatorial and nonlinear models.
- [IBM ILOG CPLEX Optimizer](https://www.ibm.com/products/ilog-cplex-optimization-studio/cplex-optimizer) - Commercial solver for linear, integer, quadratic, and conic optimization.
- [LINDO/LINGO](https://www.lindo.com/) - Commercial optimization modeling and solver environment for linear, nonlinear, stochastic, and integer models.
- [MOSEK](https://www.mosek.com/) - Commercial solver for LP, QP, conic, semidefinite, exponential cone, power cone, and mixed-integer conic problems.

## Modeling Languages and Algebraic Modeling Systems

- [AIMMS](https://www.aimms.com/) - Commercial modeling environment for optimization applications and decision-support systems.
- [AMPL](https://ampl.com/) - Algebraic modeling language for expressing optimization models independently from solvers.
- [CVXPY](https://www.cvxpy.org/) - Open-source Python-embedded modeling language for convex optimization.
- [CVXR](https://cvxr.rbind.io/) - R modeling package for disciplined convex optimization.
- [GAMS](https://www.gams.com/) - Algebraic modeling system for optimization and large-scale mathematical programming.
- [JuMP](https://jump.dev/) - Open-source Julia modeling language built on MathOptInterface.
- [MathOptInterface](https://jump.dev/MathOptInterface.jl/stable/) - Julia abstraction layer connecting modeling tools to solvers.
- [MiniZinc](https://www.minizinc.org/) - Constraint modeling language for finite-domain, SAT, MIP, and hybrid solvers.
- [Mosel](https://www.fico.com/en/products/fico-xpress-optimization/docs/latest/mosel/mosel_lang/dhtml/moselreflang.html) - Modeling and programming language in the FICO Xpress ecosystem.
- [OPL](https://www.ibm.com/docs/en/icos) - Optimization Programming Language used with IBM ILOG CPLEX Optimization Studio.
- [OR-Tools Modeling](https://developers.google.com/optimization) - Modeling APIs for CP-SAT, routing, assignment, flows, and linear solvers.
- [PuLP](https://coin-or.github.io/pulp/) - Open-source Python modeling package for linear and integer programming.
- [Pyomo](https://www.pyomo.org/) - Open-source Python algebraic modeling language for linear, nonlinear, stochastic, and mixed-integer optimization.
- [PySCIPOpt](https://github.com/scipopt/PySCIPOpt) - Python interface to SCIP for mathematical optimization and constraint integer programming.
- [YALMIP](https://yalmip.github.io/) - MATLAB modeling toolbox for optimization and control.

## Constraint Programming Tools

- [Choco Solver](https://choco-solver.org/) - Open-source Java constraint programming solver.
- [CP Optimizer](https://www.ibm.com/products/ilog-cplex-optimization-studio/cplex-cp-optimizer) - Commercial IBM solver for scheduling and constraint programming.
- [MiniZinc](https://www.minizinc.org/) - Solver-independent constraint modeling language with a large benchmark and challenge ecosystem.
- [OR-Tools CP-SAT](https://developers.google.com/optimization/cp/cp_solver) - Open-source CP-SAT solver for constraint programming and integer optimization.
- [Timefold Solver](https://timefold.ai/) - Open-source Java/Kotlin solver for planning, scheduling, routing, and timetabling; successor ecosystem to OptaPlanner.

## Simulation Software

- [AnyLogic](https://www.anylogic.com/) - Commercial simulation platform supporting discrete-event, agent-based, and system dynamics models.
- [Arena](https://www.rockwellautomation.com/en-us/products/software/arena-simulation.html) - Commercial discrete-event simulation software used in manufacturing, logistics, and service systems.
- [ExtendSim](https://extendsim.com/) - Commercial simulation environment for discrete-event, continuous, and hybrid systems.
- [FlexSim](https://www.flexsim.com/) - Commercial 3D simulation software for production, logistics, material handling, and healthcare operations.
- [GPSS](https://en.wikipedia.org/wiki/GPSS) - Historical general-purpose simulation language for discrete-event systems.
- [JaamSim](https://jaamsim.com/) - Open-source discrete-event simulation software with 3D animation and process modeling.
- [OpenModelica](https://openmodelica.org/) - Open-source Modelica-based environment for modeling, simulation, optimization, and analysis of complex systems.
- [salabim](https://www.salabim.org/) - Open-source Python package for discrete-event simulation.
- [Simio](https://www.simio.com/) - Commercial simulation and scheduling platform for discrete-event and object-oriented modeling.
- [SimPy](https://simpy.readthedocs.io/) - Open-source Python framework for process-based discrete-event simulation.

## Spreadsheet and Teaching Tools

- [Analytic Solver](https://www.solver.com/analytic-solver-platform) - Commercial Excel-based optimization, simulation, data mining, and decision analytics suite.
- [Excel Solver](https://support.microsoft.com/office/define-and-solve-a-problem-by-using-solver-5d1a388f-079d-43ac-a7eb-f63e45925040) - Built-in Microsoft Excel add-in for small optimization models.
- [LINDO/LINGO](https://www.lindo.com/) - Commercial teaching and modeling system widely used in OR courses.
- [OpenSolver](https://opensolver.org/) - Open-source Excel add-in for linear, integer, and nonlinear optimization models.
- [Plain Solver](https://juantorresmi.github.io/plain-solver/) - Free browser-based modeling tool that builds LP, MIP and nonlinear models from plain-English sentences, solves them with HiGHS, and exports Excel Solver-style reports.
- [POM-QM for Windows](https://wps.prenhall.com/bp_weiss_software_1/) - Educational software for production and operations management models.
- [QM for Windows](https://wps.prenhall.com/bp_weiss_software_1/) - Teaching software for quantitative methods and operations management.
- [SolverStudio](https://solverstudio.org/) - Excel add-in for building optimization models with languages such as AMPL, GAMS, PuLP, and Pyomo.

## Solver Benchmarking and Portals

- [COIN-OR Projects](https://www.coin-or.org/projects/) - Catalog of open-source optimization solvers and OR software.
- [Hans Mittelmann Benchmarks](https://plato.asu.edu/bench.html) - Long-running benchmark pages comparing solvers across LP, MIP, conic, nonlinear, and other problem classes.
- [JuliaOpt Solver Table](https://jump.dev/JuMP.jl/stable/installation/#Supported-solvers) - JuMP-supported solver list and installation guidance.
- [Pyomo Solver Recipes](https://pyomo.readthedocs.io/en/stable/) - Documentation for solving Pyomo models with supported solvers.
