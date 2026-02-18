<img src="restatr.svg" width="150">

# restatr

*Open-source tools for Stata apostates.*

## The Problem

Stata is the dominant platform in applied microeconomics, and researchers like Baum, Schaffer, Stillman, Correia, and others have done the field an enormous service by implementing key econometric methods — `ivreg2`, `reghdfe`, `xtabond2` — as user-contributed Stata packages. Writing for Stata made sense: that's where the users were.

But these community-built packages have become so central that they're effectively part of Stata's value proposition. The result is that access to foundational methods depends on a commercial licence, creating barriers to **reproducibility** (verifying published research requires a licence), **scalability** (large-scale computational work requires per-core Stata/MP licences), and **access** (researchers at less-resourced institutions are locked out).

## What restatr Does

restatr aims to provide open-source R implementations of the most important Stata commands for applied econometrics, validated for numerical equivalence against the originals.

The first package is **[ivreg2r](https://github.com/restatr/ivreg2r)**, an R implementation of Stata's `ivreg2` for IV/GMM estimation with flexible variance-covariance estimation. It is under active development, with an initial release now available.

## Links

- [ivreg2r](https://github.com/restatr/ivreg2r)
- [GitHub Organization](https://github.com/restatr)