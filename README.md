# Uncommon Julia Error: Handling Zero Input in Power Function

This repository demonstrates a common error in Julia related to handling zero input in functions involving exponentiation.  The `my_function` in `bug.jl` does not account for the undefined case of 0^0, leading to an error. The solution in `bugSolution.jl` addresses this issue.