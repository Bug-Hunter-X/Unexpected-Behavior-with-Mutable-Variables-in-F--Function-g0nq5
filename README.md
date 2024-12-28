# F# Mutable Variable Bug

This repository demonstrates a common issue in F# related to the unexpected behavior of mutable variables within functions. The `add` function modifies its input parameters, leading to unintended consequences when the original variables `x` and `y` are reused outside of the function.