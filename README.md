# Optim_placement_fonctions_service_telecoms
 



# Suggestions

* Rather than charging libraries in every file, uisng libraries only once in terminal before executing files. 
* Move to the src directory : 
  
```julia
using CPLEX 
using JuMP
using DelimitedFiles



include("run.jl")
test() 

```
