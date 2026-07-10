<img src="restatr.svg" width="150">

# restatr

*Reproduce Stata results in R and Python.*

[SSC modules](https://ideas.repec.org/s/boc/bocode.html) like [`ivreg2`](https://ideas.repec.org/c/boc/bocode/s425401.html), [`reghdfe`](https://ideas.repec.org/c/boc/bocode/s457874.html), and [`xtabond2`](https://ideas.repec.org/c/boc/bocode/s435901.html) are invaluable tools in applied economics. While the modules themselves are open source, typically licensed under the [GPL v3](https://www.gnu.org/licenses/gpl-3.0.txt) or the [MIT license](https://opensource.org/license/MIT), using them to reproduce published results requires a copy of Stata. restatr uses LLM assistance to port these user-contributed tools to R and Python. Each resulting package is rigorously validated against the Stata original.  

## Packages

**[ivreg2r](https://restatr.com/ivreg2r/)** ([GitHub](https://github.com/restatr/ivreg2r)) — IV/GMM estimation with flexible variance-covariance estimation, matching Stata's `ivreg2`. 

More packages are in development.

## Links

- [GitHub Organization](https://github.com/restatr)

## Maintainer

[Francis DiTraglia](https://ditraglia.com)
