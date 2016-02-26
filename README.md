Metrics.jl
======

[![Project Status: Active - The project has reached a stable, usable state and is being actively developed.](http://www.repostatus.org/badges/0.1.0/active.svg)](http://www.repostatus.org/#active) [![Julia Version 0.4.0+](https://img.shields.io/badge/Julia%20Version-0.4.0+-blue.svg)](https://img.shields.io/badge/R%20Version-0.4.0+-blue.svg) [![Build Status](https://travis-ci.org/paulhendricks/Metrics.jl.svg?branch=master)](https://travis-ci.org/paulhendricks/Metrics.jl) [![Build status](https://ci.appveyor.com/api/projects/status/56u32eosqom801ht?svg=true)](https://ci.appveyor.com/project/paulhendricks/metrics-jl)

`Metrics.jl` is a set of tools for quickly scoring models in data science and machine learning. This toolset is written in Julia for blazing fast performance. This toolset's API follows that of [sklearn.metrics](http://scikit-learn.org/stable/modules/classes.html#sklearn-metrics-metrics) as closely as possible so one can easily switch back and forth between the two languages without too much cognitive dissonance. The following types of metrics are currently implemented in `Metrics.jl`:

-   Regression metrics (implemented in 0.1.0)

The following types of metrics are soon to be implemented in `Metrics.jl`:

-   Classification metrics (to be implemented in 0.1.0)
-   Multilabel ranking metrics (to be implemented in 0.1.0)
-   Clustering metrics (to be implemented in 0.1.0)
-   Biclustering metrics (to be implemented in 0.1.0)
-   Pairwise metrics (to be implemented in 0.1.0)

Installation
------------

You can install:

-   the latest released version from Github with

``` julia
Pkg.clone("git://github.com/paulhendricks/Metrics.jl.git")
```

If you encounter a clear bug, please file a minimal reproducible example on [Github](https://github.com/paulhendricks/Metrics.jl/issues).
