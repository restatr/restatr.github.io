# restatr

*Open-source tools for Stata apostates.*

## The Problem

Stata is the dominant platform in applied microeconomics. Many of the field's most-cited econometric methods — `ivreg2`, `reghdfe`, `xtabond2` — are implemented as user-contributed packages. These packages are open-source in a frustrating sense: the source code is freely available, but it can only be *executed* inside Stata, which requires a commercial licence. The community contributes the value; the platform captures the rent.

This creates barriers to **reproducibility** (verifying published research requires a licence), **scalability** (large-scale computational work requires per-core Stata/MP licences), and **access** (researchers at less-resourced institutions are locked out).

## What restatr Does

restatr aims to provide open-source R implementations of the most important Stata commands for applied econometrics, validated for numerical equivalence against the originals.

The first package is **[ivreg2r](https://github.com/restatr/ivreg2r)**, an R implementation of Stata's `ivreg2` for IV/GMM estimation with flexible variance-covariance estimation. It is under active development, with an initial release now available.

## Links

- [ivreg2r](https://github.com/restatr/ivreg2r)
- [GitHub Organization](https://github.com/restatr)