**Statistics, OR, Finance, etc.**

- [ANALYSIS](#analysis)
- [ACTUARIAL SCIENCE](#actuarial-science)
   * [Econometrics](#econometrics) 
- [BENCHMARKS](#benchmarks)
   * [Preprocessor](#preprocessor)    
- [OPERATIONS RESEARCH](#operations-research)
   * [Optimization](#optimization)
   * [Org-JuliaOpt](#org-juliaopt)
- [STATISTICS](#statistics)
   * [Org-JuliaStats](#org-juliastats)
      + [Probabilistic Programming](#probabilistic-programming)
   * [Bayesian](#bayesian)
   * [Gaussian](#gaussian)
   * [Regression Analysis](#regression-analysis)
   * [Statistical Tests](#stat-tests)
   * [Valuation](#valuation)
      + [Org-JuliaQuant](#org-juliaquant)
- [VIDEOS](#videos)

----

# ANALYSIS
- [General guidelines (table) for choosing a statistical analysis](http://www.ats.ucla.edu/stat/mult_pkg/whatstat/default.htm) which was adapted from [Choosing the Correct Statistic](http://bama.ua.edu/~jleeper/627/choosestat.html) developed by James D. Leeper, Ph.D.
- [Rational and Irrational Thought: The Thinking that IQ Tests Miss](http://www.scientificamerican.com/article/rational-and-irrational-thought-the-thinking-that-iq-tests-miss/) 

----

# ACTUARIAL SCIENCE 

### Econometrics 
- [copula.jl](https://github.com/floswald/copula.jl) :: Julia Copula package implements the gaussian AR1 copula.
- [DynamicFactorModels.jl](https://github.com/joidegn/DynamicFactorModels.jl) :: Dynamic Factor Models for Julia.
- [Dynare.jl](https://github.com/DynareTeam/Dynare.jl) :: This package aims at bringing to Julia some of the algorithms incorporated in Dynare, a platform for solving dynamic economic models.
- [Econometrics.jl](https://github.com/cgroll/Econometrics.jl) :: Econometric models in Julia.
- [GARCH.jl](https://github.com/AndreyKolev/GARCH.jl) :: Generalized Autoregressive Conditional Heteroskedastic (GARCH) models for Julia.
- [Jconometrics.jl](https://github.com/adriantorrie/Jconometrics.jl) :: MATLAB to Julia port of Spatial Econometrics.
- [julia__timeseries](https://github.com/ElOceanografo/julia_timeseries) :: Time-series analysis functions for Julia.
- [Loss.jl](https://github.com/johnmyleswhite/Loss.jl) :: General functions for estimating loss functions inspired by Kaggle's release of code for many common metrics.
- [QuantEcon.jl](https://github.com/QuantEcon/QuantEcon.jl) :: This package collects code for quantitative economic modeling. It is currently comprised of two main parts: 1. A toolbox of routines useful when doing economics and 2. Implementations of types and solution methods for common economic models.
   - [Quantitative economic modelling](http://quant-econ.net/jl/index.html) lecture series in Julia language, designed and written by Thomas J. Sargent and John Stachurski, that is freely available as a [PDF](http://quant-econ.net/_static/pdfs/jl-quant-econ.pdf) file too.
- [RuinProbability.jl](https://github.com/Hank-Qian/RuinProbability.jl) :: For calculating the ruin probability with real data under different claims models.
- [SolveDSGE](https://github.com/RJDennis/SolveDSGE) :: The package contains a variety of methods for solving Dynamic Stochastic General Equilibrium (DSGE) models to first- or second-order accuracy. It will be of most interest to macro-economists, but others may find the routines for reordering the complex Schur form and the generalized complex Schur form useful.
- [TimeData.jl](https://github.com/cgroll/TimeData.jl) :: This package provides fast, robust and convenient representation of time series data.


###### Learning Resources
- [Self-Study Plan for Becoming a Quantitative Developer](http://www.quantstart.com/articles/Self-Study-Plan-for-Becoming-a-Quantitative-Developer)
- Blog : [Julia introduction by Sébastien Villemot](http://econforge.github.io/posts/2014/juil./28/cef2014-julia/) at Computational in Economics and Finance (CEF) conference 2014 in Oslo. 

----

# BENCHMARKS 
- [Microbenchmark timings](http://speed.julialang.org) with a [Timeline](http://speed.julialang.org/timeline/)
- [Benchmark.jl](https://github.com/johnmyleswhite/Benchmark.jl) :: A package for computing simple benchmarks, comparing functions and packages.
- [BenchmarkLite.jl](https://github.com/lindahua/BenchmarkLite.jl) :: A lightweight Julia package for simple performance benchmark.
   __Resources__ ::
   * [Notebook showing the usage of BenchmarkLite.jl](http://nbviewer.ipython.org/github/lindahua/BenchmarkLite.jl/blob/master/examples/mathfuns_benchmark.ipynb)
- [Criterion.jl](https://github.com/jakebolewski/Criterion.jl) :: A port of the Haskell's Criterion and Clojure's Criterium library to Julia, that runs benchmarks, analyzing the results using various statistical techniques.
- [julia_qsortbenchmarks](https://github.com/illerucis/julia_qsortbenchmarks) ::  Suggested improvements to Julia's Quicksort implementation.
- [JuliaBenchmarks](https://github.com/kapiliitr/JuliaBenchmarks) :: Porting HPC Challenge benchmarks to Julia.
- [raytracer.jl](https://github.com/JuliaLang/julia/blob/master/test/perf/kernel/raytracer.jl) :: Raytracer in the Julia kernel and other [raytracer](https://github.com/jakebolewski/rays) packages.
- [SimplexBenchmarks](https://github.com/mlubin/SimplexBenchmarks) :: Benchmarks comparing individual operations of the Simplex method for linear programming in Julia and other languages. Uses modified version of jlSimplex to generate data from real instances.
- [SortPerf.jl](https://github.com/kmsquire/SortPerf.jl) :: Julia module to test the performance of sorting algorithms.

### Preprocessor
- [Precompile.jl](https://github.com/JuliaLang/julia/blob/master/base/precompile.jl) :: Precompilation in Julia base, and its [documentation](http://docs.julialang.org/en/latest/stdlib/base/#Base.precompile)

----

# OPERATIONS RESEARCH 
- [CGRASP.jl](https://github.com/tautologico/CGRASP.jl) :: Continuous Greedy Randomized Adaptive Search Procedure (CGRASP), in Julia.
- [CSDP.jl](https://github.com/joehuchette/CSDP.jl) :: Julia wrapper for the CSDP semidefinite programming solver.
- [jlSimplex](https://github.com/mlubin/jlSimplex) :: Proof-of-concept implementation of the (dual) simplex algorithm for linear programming in Julia.
- [JuMP.jl](https://github.com/IainNZ/JuMP.jl) :: Modelling language for Linear, Integer, and Quadratic Programming.
  * _JuMP DOCS_::
  * [MIT-ORC Fall-2013 JuMP tutorial](https://github.com/IainNZ/JuMPTutorial)
- [JuMPeR.jl](https://github.com/IainNZ/JuMPeR.jl) :: Julia for Mathematical Programming (JuMP) extension for Robust optimization.
- [jobshop](https://github.com/stefan-k/jobshop) :: The Jobshop (Open Shop Scheduling Problem (OSSP)) problem is solved with evolutionary strategies in Julia.
- [MinFinder.jl](https://github.com/Ken-B/MinFinder.jl) :: The MinFinder algorithm to find all the minima for a differentiable function inside a bounded domain.
- [OptimizationServices.jl](https://github.com/tkelman/OptimizationServices.jl) :: Julia interface to [COIN-OR Optimization Services](https://projects.coin-or.org/OS). This Julia package is intended to be an interface between `MathProgBase.jl` and COIN-OR Optimization Services (OS), translating between the Julia-expression-tree `MathProgBase` format for nonlinear objective and constraint functions and the Optimization Services instance Language (OSiL) XML-based optimization problem interchange format.
- [Predictors.jl](https://github.com/dejakaymac/Predictors.jl)
- [Ranking.jl](https://github.com/johnmyleswhite/Ranking.jl) :: Tools for ranking in Julia.
- [RationalSimplex.jl](https://github.com/IainNZ/RationalSimplex.jl) :: Pure Julia implementation of the simplex algorithm.
- [SemidefiniteProgramming.jl](https://github.com/daviddelaat/SemidefiniteProgramming.jl) :: This package provides a Julia interface for low-level modeling of semidefinite programming problems and for solving semidefinite programs with solvers such as SDPA and CSDP.
- [SimJulia.jl](https://github.com/BenLauwens/SimJulia.jl) :: is a combined continuous time / discrete event process oriented simulation framework written in Julia inspired by the Simula library DISCO and the Python library SimPy.
- [VRP](https://github.com/IainNZ/VRP) :: Vehicle Routing Problem (VRP) is a combinatorial optimization and integer programming problem.

###### Learning Resources
+ [ORSoftwareTools2014](https://github.com/IainNZ/ORSoftwareTools2014) :: This is the repository for code/examples/instructions for the MIT course 15.S60 "Software Tools for Operations Research".
+ [DG2012Tutorial.jl](https://github.com/johnmyleswhite/DG2012Tutorial.jl) :: Simple examples of SGD-style computations in Julia.
+ [Solving a Combination Lock Puzzle with JuMP + Julia](http://iaindunning.com/2013/combination-locks.html) and the [HackerNews thread](https://news.ycombinator.com/item?id=6425160).

### Optimization 
+ [ampl.jl](https://github.com/dpo/ampl.jl) :: Julia interface to the AMPL Solver Library (ASL).
+ [AMPLMathProgInterface.jl](https://github.com/mlubin/AMPLMathProgInterface.jl) :: Wrapper for MathProgBase.jl {see the `JuliaOpt` section below}.
+ [BlackBoxOptim.jl](https://github.com/robertfeldt/BlackBoxOptim.jl) :: An experimental, work-in-progress global optimization framework for Julia, supporting both multi- and single-objective optimization problems, focused on (meta-)heuristic/stochastic algorithms (DE, PSO, CMA-ES etc).
- [Convex.jl](https://github.com/cvxgrp/Convex.jl) :: a julia package for disciplined convex programming.
- [CPLEX.jl](https://github.com/joehuchette/CPLEX.jl) :: The CPLEX.jl package provides an interface for using IBM's CPLEX Optimizer™ from the Julia language. You cannot use CPLEX.jl without having purchased and installed a copy of CPLEX Optimizer™ from IBM. This package is available free of charge and in no way replaces or alters any functionality of IBM's CPLEX Optimizer product.
- [CUTEst.jl](https://github.com/lpoo/CUTEst.jl) :: Julia interface for CUTEst.
- [DDUS.jl](https://github.com/vgupta1/DDUS.jl) :: Data-driven Uncertainty Sets for the JuMPeR framework. 
- [ECOS.jl](https://github.com/jfsantos/ECOS.jl) :: Julia wrapper for the ECOS SOCP solver.
- [GeneticAlgorithms.jl](https://github.com/forio/GeneticAlgorithms.jl) :: is a lightweight framework that simplifies the process of creating genetic algorithms and running them in parallel.
- [IProfile](https://github.com/timholy/IProfile.jl) :: Preferably, use [IProfile in Base packages](http://docs.julialang.org/en/latest/stdlib/profile/) to profile your code, which contains an "instrumenting profiler" for the Julia language. And, [ReadTheDocs](http://julia.readthedocs.org/en/latest/stdlib/profile/)
- [JuliaCMAES](https://github.com/Staross/JuliaCMAES) :: CMA-ES port - a mix of the original minimal MATLAB implementation (purecmaes.m) and the full one (cmaes.m).
- [Junquo.jl](http://github.com/IainNZ/Junquo.jl) :: stands for "JUlia Nonconvex QUadratically constrained quadratic program Optimizer", a (mixed-integer) nonconvex quadratically constrained quadratic program (QCQP) solver.
- [LSQ.jl](https://github.com/davidlizeng/LSQ.jl) :: is a library that makes it easy to formulate and solve least-squares optimization problems with linear equality constraints.
- [Memoize.jl](https://github.com/simonster/Memoize.jl) :: Easy memoization for Julia.
- [MOpt.jl](https://github.com/floswald/MOpt.jl) :: Parallel derivative-free Moment Optimization for Julia.
- [NLTester](https://github.com/IainNZ/NLTester) :: Code for benchmarks comparing AMPL, Julia, and YALMIP (MATLAB) for nonlinear modeling.
- [pikaia.jl](https://github.com/tmeits/pikaia.jl) :: Genetic Algorithms (GA's).
- [Polyopt.jl](https://github.com/joachimdahl/Polyopt.jl) :: Julia package for polynomial optimization using semidefinite programming. 
- [Proximal.jl](https://github.com/johnmyleswhite/Proximal.jl) :: Translation of Parikh and Boyd code for proximal algorithms.
- [Quadprog.jl](https://github.com/harmeling/Quadprog.jl) :: A wrapper around Ipopt.jl to solve quadratic programming problems. This package provides the function quadprog which calls the Ipopt.jl library for Interior Point Nonlinear Optimization.
- [QuickCheck.jl](https://github.com/pao/QuickCheck.jl) :: is listed in METADATA and based on QuickCheck specification-based randomized tester for Julia. 
  * _DOCS_::
  * [https://quickcheckjl.readthedocs.org/](https://quickcheckjl.readthedocs.org/)
- [SCIP.jl](https://github.com/mlubin/SCIP.jl) by @mlubin :: An optimization software for mixed-integer programs.
- [SCIP.jl](https://github.com/ryanjoneil/SCIP.jl) by @ryanjoneil :: A Julia interface to the SCIP solver.
- [SCS.jl](https://github.com/karanveerm/SCS.jl) :: Julia Wrapper for SCS (https://github.com/cvxgrp/scs).

### Org-[JuliaOpt](http://juliaopt.org/) 
An umbrella group for Julia-based optimization-related projects, with its own [mailing list](https://groups.google.com/forum/#!forum/julia-opt) at Google groups. 
- [Cbc.jl](https://github.com/JuliaOpt/Cbc.jl) :: Julia interface to the mixed-integer linear programming solver Cbc via the CoinMP C library.
- [GLPKMathProgInterface.jl](https://github.com/JuliaOpt/GLPKMathProgInterface.jl) :: Interface between the GLPK.jl wrapper and MathProgBase.jl.
+ [Gurobi.jl](https://github.com/JuliaOpt/Gurobi.jl) :: is a Julia interface for the Gurobi Optimizer, a [commercial optimization solver for a variety of mathematical programming problems](https://en.wikipedia.org/wiki/Gurobi), including linear programming (LP), quadratic programming (QP), quadratically constrained programming (QCP), mixed integer linear programming (MILP), mixed-integer quadratic programming (MIQP), and mixed-integer quadratically constrained programming (MIQCP).
+ [Ipopt.jl](https://github.com/JuliaOpt/Ipopt.jl) :: is a Julia interface to the Ipopt nonlinear solver.
+ [KNITRO.jl](https://github.com/JuliaOpt/KNITRO.jl) :: This package provides an interface for using the KNITRO solver from the Julia language, which can only be used after having purchased and installed a copy of KNITRO from Ziena Optimization. 
+ [LsqFit.jl](https://github.com/JuliaOpt/LsqFit.jl) :: Simple curve fitting functionality from Optim.jl has been moved into its own package.
+ [MathProgBase.jl](https://github.com/JuliaOpt/MathProgBase.jl) :: Solver-independent functions (incl. linprog and mixintprog) and low-level interface for Mathematical Programming.
+ [Mosek.jl](https://github.com/JuliaOpt/Mosek.jl) :: Interface to the Mosek solver in Julia.
+ [NLopt.jl](https://github.com/JuliaOpt/NLopt.jl) :: Package to call the NLopt nonlinear-optimization library from the Julia language.
+ [Optim.jl](https://github.com/JuliaOpt/Optim.jl) :: A basic optimization algorithms implementation.

###### Learning Resources
+ [juliaopt-notebooks](https://github.com/JuliaOpt/juliaopt-notebooks) :: A collection of IJulia notebooks related to optimization.
+ [Slides of Iain Dunning's 2013 talk about the JuliaOpt collection of packages](https://docs.google.com/presentation/d/1FlHt245YxPXFwOHmxLYW1z5_QjdCYHVPjy5Zo12lx1I/edit?usp=sharing) at the Cambridge Area Julia Users Network Meetup.

----

# STATISTICS
- [AD_StatTest-julia](https://github.com/manuamador/AD_StatTest-julia) :: An implementation of the Anderson Darling statistical test for exponential or Rayleigh distributions in Julia.
- [ApproXD.jl](https://github.com/floswald/ApproXD.jl) :: B-splines and linear high-dimensional approximators in multiple dimensions for Julia.
- [BasicSpace.jl](https://github.com/johnmyleswhite/BasicSpace.jl) :: A port of the R "basicspace" package to Julia.
- [BNMF.jl](https://github.com/r9y9/BNMF.jl) :: Gamma Process Non-negative Matrix Factorization (GaP-NMF).
- [Bootstrap.jl](https://github.com/julian-gehring/Bootstrap.jl) :: Bootstrapping is a widely applicable technique for statistical estimation, especially in the absence of closed-form solutions.
- [Causality.jl](https://github.com/tfgit/Causality.jl) :: A Julia Package for Causal Inference.
- [CauseMap.jl](https://github.com/cyrusmaher/CauseMap.jl) :: An implementation of Convergent Cross Mapping (CCM), a method for causal inference in non-linear dynamics systems, written in Julia.
- [Civecm.jl](https://github.com/andreasnoackjensen/Civecm.jl) :: Cointegration in Vector Error Correction Models in Julia.
- [Church.jl](https://github.com/LaurenceA/Church.jl) :: Perform MCMC inference in complex, and simple, probabilistic models.
- [ConditionalRandomFields.jl](https://github.com/jperla/ConditionalRandomFields.jl) :: Scalable Conditional Random Fields code for Julia.
- [ConjugatePriors.jl](https://github.com/johnmyleswhite/ConjugatePriors.jl) :: Closed form expressions for conjugate priors in Julia.
- [CRBM.jl](https://github.com/kzahedi/CRBM.jl) :: Conditional RBMs package. 
- [CrossDecomposition.jl](https://github.com/simonster/CrossDecomposition.jl) :: Canonical-Correlation Analysis (CCA).
- [CTDE.jl](https://github.com/adolgert/CTDE.jl) :: Continuous time, discrete event system in Julia.
- [CurveFit.jl](https://github.com/pjabardo/CurveFit.jl) :: Simple least squares and curve fitting functions.
- [JointMoments.jl](https://github.com/tensorjack/JointMoments.jl) :: Tensors and statistics for joint central moments. 
- [DA.jl](https://github.com/trthatcher/DA.jl) :: A package for linear and quadratic regularized Discriminant Analysis.
- [DiscreteFactor.jl](https://github.com/wlbksy/DiscreteFactor.jl) :: Discrete factor and its operations in Probabilistic Graphical Models.
- [DiscreteInference.jl](https://github.com/lindahua/DiscreteInference.jl) :: Viterbi algorithm.
- [DiscriminantAnalysis.jl](https://github.com/johnmyleswhite/DiscriminantAnalysis.jl) :: Methods for discriminant analysis, in Julia.
- [Divergences.jl](https://github.com/gragusa/Divergences.jl) :: A Julia package for evaluating divergences.
- [DPMM.jl](https://github.com/sbos/DPMM.jl) :: Dirichlet Process Mixture Models in Julia.
- [Earth.jl](https://github.com/lendle/Earth.jl) :: is the wrapper for the stand-alone version of R's earth package. The [Earth package in R](http://cran.r-project.org/web/packages/earth/) for [Multivariate Adaptive Regression Splines](http://en.wikipedia.org/wiki/Multivariate_adaptive_regression_splines) (MARS), a form of regression analysis.
- [FactorModels.jl](https://github.com/joidegn/FactorModels.jl) :: Factor models or diffusion index models.
- [FeldtLib.jl](https://github.com/robertfeldt/FeldtLib.jl) :: Comparing two set of samples (empirical distributions)Baumgartner-Weis-Schindler statistic and tests.
- [Hotspot.jl](https://github.com/jzelner/Hotspot.jl) :: Hotspot modeling.
- [hmm.jl](https://github.com/nfoti/hmm.jl) :: Julia implementation of Hidden Markov Models.
- [HyperLogLog.jl](https://github.com/johnmyleswhite/HyperLogLog.jl) :: A simple HyperLogLog implementation in Julia.
- [HypothesisTests.jl](https://github.com/simonster/HypothesisTests.jl) :: T-tests, Wilcoxon rank sum (Mann-Whitney U), signed rank, and circular statistics in Julia.
- [Isotonic.jl](https://github.com/ajtulloch/Isotonic.jl) :: This implements several algorithms for isotonic regression in Julia.
   * @ajtulloch's blog on [speeding up Isotonic Regression with Julia](http://tullo.ch/articles/python-vs-julia/) and the [IJulia notebook](http://nbviewer.ipython.org/url/gist.githubusercontent.com/ajtulloch/9485996/raw/94b3d0e6bd67256f1f02eebb1463365dbc8b64fc/Julia.ipynb)
- [ITC.jl](https://github.com/johnmyleswhite/ITC.jl) :: Code for modeling intertemporal choice in Julia.
- [JAGS.jl](https://github.com/olofsen/JAGS.jl) :: A Julia interface to JAGS, to provide a shared library as an interface between Julia and JAGS - Just another Gibbs sampler.
- [Jags.jl](https://github.com/goedman/Jags.jl) :: Julia package for using Just another Gibbs sampler.
- [JuMPStoch.jl](https://github.com/joehuchette/JuMPStoch.jl) :: A stochastic optimization framework for JuMP.
- [KernSmooth.jl](https://github.com/lendle/KernSmooth.jl) :: A direct port of the R package KernSmooth, (v2.23-10.), carrying an unlimited license.
- [KLDivergence.jl](https://github.com/johnmyleswhite/KLDivergence.jl) :: KL-divergence estimation in Julia.
- [KSVM.jl](https://github.com/remusao/KSVM.jl) :: Kernel Support Vector Machine (SVM) written in Julia.
- [Lasso.jl](https://github.com/simonster/Lasso.jl) :: Lasso solvers for linear and generalized linear models.
- [LIBSVM.jl](https://github.com/simonster/LIBSVM.jl) :: Julia bindings for LIBSVM.
- [LARS.jl](https://github.com/simonster/LARS.jl) :: Least angle regression.
- [ManifoldLearning.jl](https://github.com/wildart/ManifoldLearning.jl) :: A Julia package for manifold learning and non-linear dimensionality reduction.
   - [Documentation](http://manifoldlearningjl.readthedocs.org/en/latest/index.html)
- [MCMC2.jl](https://github.com/johnmyleswhite/MCMC2.jl) :: Alternative MCMC package design demo.
- [MCMCExampleRepository.jl](https://github.com/goedman/MCMCExampleRepository.jl) :: Repository for MCMC Julia examples.
- [MCMCModels.jl](https://github.com/scidom/MCMCModels.jl) :: Scratch space for hosting temporarily current model specification for MCMC inference.
- [Mamba.jl](https://github.com/brian-j-smith/Mamba.jl) :: Markov chain Monte Carlo simulation toolkit for julia.
- [MixedModels.jl](https://github.com/dmbates/MixedModels.jl) :: A Julia package for fitting (statistical) mixed-effects models.
- [MixtureModels.jl](https://github.com/lindahua/MixtureModels.jl) :: A Julia package for probabilistic mixture models.
- [MultivariateAnalysis.jl](https://github.com/lindahua/MultivariateAnalysis.jl) :: A Julia package for multivariate data analysis (e.g. dimension reduction).
- [NaiveBayes.jl](https://github.com/nutsiepully/NaiveBayes.jl) :: Simple Naive Bayes implementation in Julia.
- [NURBS.jl](https://github.com/TheBB/NURBS.jl) :: A Julia package for manipulating NURBS objects (curves, surfaces, volumes, etc.).
- [KernelEstimator.jl](https://github.com/panlanfeng/KernelEstimator.jl) :: The julia package for nonparametric density estimate and regression.
- [NHST.jl](https://github.com/johnmyleswhite/NHST.jl) :: Null hypothesis significance tests.
- [ParallelSparseRegression.jl](https://github.com/madeleineudell/ParallelSparseRegression.jl) :: A Julia library for parallel sparse regression, that implements solvers for regression problems including least squares, ridge regression, lasso, non-negative least squares, and elastic net; and proposes to add fast methods to obtain regularization paths.
- [PGM0.jl](https://github.com/micklat/PGM0.jl) :: A bottom-up approach to probabilistic graphical models.
- [ProbabilisticModeling.jl](https://github.com/johnmyleswhite/ProbabilisticModeling.jl) :: A BUGS-like language for describing probabilistic models in Julia.
- [ProbTopicModels.jl](https://github.com/lindahua/ProbTopicModels.jl) :: Probabilistic topic models.
- [PValueAdjust.jl](https://github.com/dirkschumacher/PValueAdjust.jl) :: P-value adjustment methods for multiple testing correction. 
- [QuantileRegression.jl](https://github.com/vincentarelbundock/QuantileRegression.jl) :: Quantile regression in the Julia language.
- [Queries](https://github.com/carljv/Queries) :: Composable queries for Julia DataFrames.
- [RandomProcesses.jl](https://github.com/johnmyleswhite/RandomProcesses.jl) :: Random processes (CRP, CRT) in Julia.
- [RBM.jl](https://github.com/kzahedi/RBM.jl)
- [Regression.jl](https://github.com/lindahua/Regression.jl) :: Algorithms for regression analysis (e.g. linear regression and logistic regression).
- [Ridge.jl](https://github.com/johnmyleswhite/Ridge.jl) :: Ridge regression and classification.
- [Rmath.jl](https://github.com/dmbates/Rmath.jl) :: Archive of functions that emulate R's d-p-q-r functions for probability distributions.
- [RunningStats.jl](https://github.com/johnmyleswhite/RunningStats.jl) :: Julia translation of John D. Cook's code for running moment statistics and univariate regressions.
- [SGD.jl](https://github.com/johnmyleswhite/SGD.jl) by @johnmyleswhite :: Fit models using SGD in Julia.
- [SDP.jl](https://github.com/trthatcher/SDP.jl) by @trthatcher :: Statistical Data Processing.
- [SGDDemo.jl](https://github.com/johnmyleswhite/SGDDemo.jl) :: Stochastic Gradient Descent (SGD) predictive models for large data sets in Julia.
- [SGD2.jl](https://github.com/johnmyleswhite/SGD2.jl) :: Stochastic gradient descent, a draft of new methods for SGD calculations.
- [SpecialFunctions.jl](https://github.com/nolta/SpecialFunctions.jl) :: Functions for AMOS, a statistical software package for [structural equation modeling](http://en.wikipedia.org/wiki/Structural_equation_modeling), produced by SPSS.
- [SimpleMCMC.jl](https://github.com/fredo-dedup/SimpleMCMC.jl) :: Small framework for MCMC sampling and maximization on user-defined models.
- [SimpleRL.jl](https://github.com/johnmyleswhite/SimpleRL.jl) :: A bare-bones package for simulating RL models and estimating them from behavioral data.
- [SmoothingKernels.jl](https://github.com/johnmyleswhite/SmoothingKernels.jl) :: Smoothing kernels for use in kernel regression and kernel density estimation.
- [TopicModels.jl](https://github.com/slycoder/TopicModels.jl) :: TopicModels for Julia.
- [Turing.jl](https://github.com/LaurenceA/Turing.jl) :: A Turing complete probabilistic programming language embedded in Julia.
- [VCOV.jl](https://github.com/gragusa/VCOV.jl) :: Build StatusHeteroskedasticity and Autocorrelation Consistent Covariance Matrix Estimation for Julia.

###### Learning Resources
* [DCStats.jl](https://github.com/johnmyleswhite/DCStats.jl) :: IJulia Notebooks that provide a brief introduction to Julia for statistical programming.
* [What’s Wrong with Statistics in Julia?](http://www.johnmyleswhite.com/notebook/2014/11/29/whats-wrong-with-statistics-in-julia/)

## Org-[JuliaStats](https://github.com/JuliaStats/)
The [github home page](https://JuliaStats.github.io).
- [DataFrames.jl](https://github.com/JuliaStats/DataFrames.jl) :: A Library for working with tabular data in Julia.
   * _DOCS_:: The [DataFrames manual section on IO](http://juliastats.github.io/DataFrames.jl/io.html).
- [DataArrays.jl](https://github.com/JuliaStats/DataArrays.jl) :: This package extends Julia by introducing data structures that can contain missing data.
- [DataFramesMeta.jl](https://github.com/JuliaStats/DataFramesMeta.jl) :: Metaprogramming tools for DataFrames.
- [DimensionalityReduction.jl](https://github.com/JuliaStats/DimensionalityReduction.jl) :: Methods for dimensionality reduction.
- [Distance.jl](https://github.com/JuliaStats/Distance.jl) :: A Julia package for evaluating distances(metrics) between vectors.
- [Distances.jl](https://github.com/JuliaStats/Distances.jl) ::  A Julia package for evaluating distances(metrics) between vectors.
- [Distributions.jl](http://juliastats.github.io/Distributions.jl/index.html) :: The Distributions package.
   * _DOCS_:: are available at [distributionsjl.readthedocs.org](http://distributionsjl.readthedocs.org/en/latest/)
- [GLM.jl](https://github.com/JuliaStats/GLM.jl) :: Linear models (LM's) and generalized linear models (GLM's) in Julia.
- [Lora.jl](https://github.com/JuliaStats/Lora.jl) :: is a generic engine for implementing Bayesian statistical models using Markov Chain Monte Carlo (MCMC) methods. 
- [MLBase.jl](https://github.com/JuliaStats/MLBase.jl) :: A set of functions to support the development of machine learning algorithms.
- [PGM.jl](https://github.com/JuliaStats/PGM.jl) :: A Julia framework for probabilistic graphical models.
- [RmathDist.jl](https://github.com/JuliaStats/RmathDist.jl) :: This package provides a julia interface to the distributions provided by the standalone Rmath library, which is part of the R project for statistical computing.
- [Sampling.jl](https://github.com/JuliaStats/Sampling.jl) :: Basic sampling algorithms package, that provides algorithmic support to statistics-related packages, including [Distributions.jl](https://github.com/JuliaStats/Distributions.jl).
- [StatsBase.jl](https://github.com/JuliaStats/StatsBase.jl) :: The Stats meta-package for basic statistics functions for Julia.
   * _DOCS_:: Documentation available at [statsbasejl.readthedocs.org](http://statsbasejl.readthedocs.org/en/latest/)
- [SVM.jl](https://github.com/JuliaStats/SVM.jl) :: Native Julia implementations of standard SVM algorithms.
- [TimeSeries.jl](https://github.com/JuliaStats/TimeSeries.jl) :: Time-series toolkit for Julia.
- [TimeModels.jl](https://github.com/JuliaStats/TimeModels.jl) :: Modeling time series in Julia.

### Probabilistic Programming
- [OpenPP.jl](https://github.com/JuliaStats/OpenPP.jl) :: Open Source Probabilistic Programming in Julia.
- [Sigma.jl](https://github.com/zenna/Sigma.jl) :: A probabilistic programming environment implemented in Julia that allows you to specify probabilistic models as normal programs, and perform inference.
- [Stan.jl](https://github.com/goedman/Stan.jl) :: Julia package for using [Stan](http://en.wikipedia.org/wiki/Stan_%28software%29), a probabilistic programming language for Bayesian inference written in C++, and licensed under the New BSD License. The Stan language is used to specify a Bayesian statistical model, which is an imperative declaration of the log probability density function.
- [Stochy.jl](https://github.com/null-a/Stochy.jl) :: Probabilistic Programming in Julia.

## Bayesian 
- [BayesModels.jl](https://github.com/lindahua/BayesModels.jl) :: Tools and Building Blocks for Bayesian Modeling and Probabilistic Inference.
- [BayesNets.jl](https://github.com/sisl/BayesNets.jl) :: Bayesian Networks for Julia.
- [Bolstad2.jl](https://github.com/goedman/Bolstad2.jl) :: Julia functions from W.M. Bolstad's "Understanding Computational Bayesian Statistics".
- [GeometricMCMC.jl](https://github.com/scidom/GeometricMCMC.jl) :: Geometric MCMC algorithms and zero-variance (ZV) Monte Carlo Bayesian routines.
- [MCBN.jl](https://github.com/binarybana/MCBN.jl) :: Monte Carlo Bayesian averaging over Bayesian networks.
- [NestedSampling.jl](https://github.com/kbarbary/NestedSampling.jl) :: Nested Sampling algorithms for Julia.
- [VarBayes.jl](https://github.com/acetoline/VarBayes.jl) :: Variational Bayesian methods in Julia.

## Gaussian
- [GP.jl](https://github.com/pschulam/GP.jl) :: Gaussian processes in Julia.
- [GaussianMixtures.jl](https://github.com/davidavdav/GaussianMixtures.jl) :: Julia modules for Gaussian Mixture Models. 
- [GaussQuadrature.jl](https://github.com/billmclean/GaussQuadrature.jl) :: Another package that generates the points and weights of the Gauss quadrature rules.
- [GaussianProcesses.jl](https://github.com/johnmyleswhite/GaussianProcesses.jl) :: A port of the Gaussian Processes toolkit to Julia.
- [NaiveBayes.jl](https://github.com/johnmyleswhite/NaiveBayes.jl) :: The Gaussian Naive Bayes model in Julia.

## Regression Analysis
- [OutOfSampleBootstrap.jl](https://github.com/grayclhn/OutOfSampleBootstrap.jl) :: Regression model validation (out-of-sample) statistics.

## Statistical Tests
- [RobustStats.jl](https://github.com/mrxiaohe/RobustStats.jl) :: A collection of robust statistical tests based on the R package WRS (R-Forge repository) by Rand Wilcox.
- [StatTests.jl](https://github.com/i-kiwamu/StatTests.jl) :: [A set of statistical tests for Julia.

----

## Valuation
**Finance**
- [AssetMgmt.jl](https://github.com/cgroll/AssetMgmt.jl) :: Asset Management.
- [FinMarkets.jl](https://github.com/imanuelcostigan/FinMarkets.jl) :: Describe and model financial markets objects using Julia.
- [FRED.jl](https://github.com/joidegn/FRED.jl) :: Package to read from the St. Louis Federal Reserve Bank API.
- [Ito.jl](https://github.com/aviks/Ito.jl) :: An open source toolkit for financial computing in Julia.
- [Lazy.jl](https://github.com/one-more-minute/Lazy.jl) :: Functional programming for Julia.
- [LibTrading.jl](https://github.com/StefanKarpinski/LibTrading.jl) :: The Julia LibTrading package is a wrapper for the libtrading library, which "is an open source API for high-performance, low-latency trading applications".
- [MCInsurance.jl](https://github.com/mkriele/MCInsurance.jl) :: This Julia package provides multi-period Monte Carlo simulations for life insurance.
- [OpenFiscaFrance.jl](https://github.com/openfisca/OpenFiscaFrance.jl) :: A port of OpenFisca-France to Julia. This is the OpenFisca package containing the formulas and parameters of the french tax-benefit system.
- [Pandas.jl](https://github.com/malmaud/Pandas.jl) :: A Julia front-end to Python's Pandas package.
- [Quandl.jl](https://github.com/milktrader/Quandl.jl) :: Julia api to Quandl open source financial, economic and social datasets.
- [SDE.jl](https://github.com/mschauer/SDE.jl) :: Simulation and inference for Ito processes and diffusions.
- [TradingSystem.jl](https://github.com/milktrader/TradingSystem.jl) :: Quantitative trading framework in Julia.
- [ZVSimulator.jl](https://github.com/scidom/ZVSimulator.jl) :: The ZVSimulator package provides a framework for assessing the zero variance (ZV) principle for Monte Carlo or random sampling via simulation.

### Org-[JuliaQuant](https://github.com/JuliaQuant)
- [FinancialBlotter.jl](https://github.com/JuliaQuant/FinancialBlotter.jl) :: Financial Instruments and Accounting in Julia.
- [FinanceStats.jl](https://github.com/JuliaQuant/FinanceStats.jl) :: An experimental sandbox of functions that implement common statistical methods in finance.
- [MarketTechnicals.jl](https://github.com/JuliaQuant/MarketTechnicals.jl) :: Technical analysis of financial time series in Julia.
- [TradeModels.jl](https://github.com/JuliaQuant/TradeModels.jl) :: Modeling the allocation of resources to markets based on the restraints of objective functions.

----

# VIDEOS
* [Statistical Models in Julia video by Douglas Bates (@dmbates)](https://www.youtube.com/watch?v=v9Io-p_iymI)

