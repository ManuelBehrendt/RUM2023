# Instructions - MERA Hands-On Session - RUM2023, Oxford
Manuel Behrendt

> **Note**
> The course and simulation files will be distributed on USB sticks at the conference (download options, see below). Julia and the needed packages should be installed beforehand. We recommend using JupyterLab or VScode.

## 1. Install Julia 1.6.x
on your system: https://julialang.org/downloads/#long_term_support_release

- Note: Apple Silicon M1/M2 should work with the macOS 64bit version

- Alternatively use the Julia version manager and make Julia 1.6.x the default: https://github.com/JuliaLang/juliaup

- Further information: https://docs.julialang.org/en/v1.6/


## 2. Download course
from git repository:
>git clone https://github.com/ManuelBehrendt/RUM2023.git

## 3. Download simulation files 
into the notebook/script folder of the course (../RUM2023/>).
- Source 1: https://datashare.mpcdf.mpg.de/s/r19OAmUIfjjt2je
- Source 2: Zenodo (upcomming)

>unzip output_00300.zip

## 4. Install Julia packages
Execute the Julia file **install_packages.jl**. It uses the prepared environment for this folder and installs all necessary packages with the versions that are needed for this course:
- julia install_packages.jl  (from command line within course folder)
- or in the Julia REPL: include("install_packages.jl")

A similar list should appear on the screen at the end:
```
...
Status `~/Documents/codes/github/RUM2023/Project.toml`
  [35d6a980] ColorSchemes v3.20.0
  [7073ff75] IJulia v1.24.0
  [a93385a2] JuliaDB v0.13.0
  [02f895e8] Mera v1.2.0
  [438e738f] PyCall v1.92.3 ⚲
  [d330b81b] PyPlot v2.11.1
  [2913bbd2] StatsBase v0.32.2
  [a759f4b9] TimerOutputs v0.5.22
```

## 5. Start Course
- Open the Julia REPL within the course folder and execute step by step the code from the script (copy/paste),
- or open the ipynb-file with Jupyter notebook/lab  (alternatively in Visual Studio Code); the Julia 1.6.x Kernel should be available. We recommend the standalone App JupyterLab-Desktop: https://github.com/jupyterlab/jupyterlab-desktop
- If you have a working Jupyter installation, it should detect the Jupyter Julia kernel; if not, you may execute: 
>import Pkg; Pkg.build("IJulia")

- Find additional information about MERA in the documentation (v1.2): https://manuelbehrendt.github.io/Mera.jl/stable/ 

- Further information for VScode users: https://code.visualstudio.com/docs/languages/julia