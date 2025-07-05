# JuliaCon 2025 presentation about FixedSizeArrays

Presentation for [talk](https://pretalx.com/juliacon-2025/talk/J3J7U8/) about [FixedSizeArrays.jl](https://github.com/JuliaArrays/FixedSizeArrays.jl) at JuliaCon 2025.

## Rendering

Install dependencies with

```julia
import Pkg
Pkg.instantiate()
```

Make sure Quarto is installed correctly with

```julia
using quarto_jll
run(`$(quarto()) check install`)
```

Then, if all is good you can render the presentation locally with

```julia
run(`$(quarto()) render index.qmd`)
```
