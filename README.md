# Julia Type Instability Bug

This repository demonstrates a common performance issue in Julia related to type instability. The `myfunction` in `bug.jl` has a return type that depends on the input value which is inefficient.  The solution (`bugSolution.jl`) shows how to address this by ensuring type stability.