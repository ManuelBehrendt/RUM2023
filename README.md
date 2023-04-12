# Instructions - MERA hand-on Session - RUM2023
Manuel Behrendt

## 1. Install Julia 1.6.*
on your system: https://julialang.org/downloads/#long_term_support_release

- Note: Apple silicon M1/M2 should work with the macOS 64bit version

- Alternatively use the Julia version manager and make Julia 1.6.* the default: https://github.com/JuliaLang/juliaup

- Further information: https://docs.julialang.org/en/v1.6/

## 2. Download course
from git repository: TBD
clone ... / wget 
```
README.md
Manifest.toml
Project.toml
assets
MERA_course.ipynb
MERA_course.jl
installation.jl
output_00300
output_00300.jld2
```

## 3. Download simulation files 
Zenodo...
into notebook/script folder: ...

## 4. Install Julia packages
Execute the Julia file "installation.jl" . It uses the prepared evironment for this folder and installs all necessary packages with the correct verions that are needed for this course:
- julia installation.jl  (from command line)
- or in the REPL include("installation.jl")
A similar list should appear on the screen:
```
  [a93385a2] JuliaDB v0.13.0 
  [02f895e8] Mera v1.2.0  
  [438e738f] PyCall v1.92.3 ⚲ 
  [d330b81b] PyPlot v2.11.1 
  [2913bbd2] StatsBase v0.32.2 
  [a759f4b9] TimerOutputs v0.5.22 
```

## 5. Start course
- open the Julia REPL and execute step by step the code in the script (copy/paste)
- or open the Jupyter notebook/lab ...ipynb (alternatively in Visual Studio Code IDE) the Julia 1.6.* Kernel should be available 