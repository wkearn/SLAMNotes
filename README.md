# SLAM Notes

These are a collection of notes I am creating as I learn more about simultaneous localization and mapping (SLAM). They take the form of [Pluto](https://github.com/fonsp/Pluto.jl) interactive notebooks.

# Installation

Clone this repository locally and `cd` into it. Then open a Julia REPL and type `]` to enter the Pkg REPL. Then run

```julia
pkg> instantiate
```
This should install Pluto and additional dependencies. Once that completes, hit backspace to get back to the Julia REPL and run

```julia
julia> import Pluto; Pluto.run()
```

This will start the Pluto server and open the welcome page in your web browser. In the "Open from File" dialog, navigate to the SLAMNotes directory and then look in the `notebooks/` directory for the notebooks. Choose the one you want to look at and click "Open" to start.

# Contents

- [Chapter 1: Landmark location](notebooks/Chapter1.jl)
