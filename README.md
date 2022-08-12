In order to use this ipopt, add these in python:

path = "~/ipopt-linux64/ipopt"

SolverFactory('ipopt',executable=path).solve(self.iN)
