# OGH2023
Julia teaching materials for the OpenGeoHub summer school 2023 in Poznan, Poland.

## Schedule
See the [schedule at pretalx](https://pretalx.earthmonitor.org/opengeohub-summer-school-2023/schedule/).

### Tuesday 29th of August 2023 in Room 18
### 09:00 - 10:30
- Introduction (`ogh_summerschool_julia.pdf`, `intro.ipynb`)
- Differences with other languages (`differences.ipynb`)
- Managing packages (`package-manager.ipynb`)
- Parallel processing (`parallel.ipynb`)

### 11:00 - 12:30
- Geospatial processing in Julia (`juliageo.ipynb`)
- Opening the hackathon files (`ogh2023.ipynb`)

## Prerequisites
Please install Julia either from the [Windows store](https://www.microsoft.com/store/apps/9NJNWW8PVKMN) or follow the instructions for installing Julia with Juliaup [here](https://github.com/JuliaLang/juliaup?tab=readme-ov-file#installation).

Afterwards run the following in a command-line to install the packages used in this session.
`julia -e "using Pkg; Pkg.add([\"GeoDataFrames\", \"Rasters\", \"GeoArrays\", \"GeoInterface\", \"IJulia\", \"Plots\", \"WellKnownGeometry\"])"`

One can also run the same from *within* Julia by starting Julia, typing `]` to enter package mode (the prompt should turn blue) and input:
`add GeoDataFrames Rasters GeoArrays GeoInterface IJulia Plots WellKnownGeometry`

## Usage
Please git clone this repository and run jupyterlab to run these notebooks.

```julia
using IJulia
jupyterlab()  # this will launch a browser window
```

Alternatively, you could run these notebooks interactively in VS Code (with the Julia plugin). After following the steps in prerequisites, one could also use their existing Jupyter installation to open/create Julia notebooks.
