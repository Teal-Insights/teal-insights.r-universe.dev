# teal-insights.r-universe.dev

The package list for <https://teal-insights.r-universe.dev>. R-universe builds every package in [`packages.json`](packages.json).

A package missing from this file is removed from the universe. This includes Teal Insights' CRAN packages: now that this file exists, R-universe no longer adds them on its own, so add each new one here.

`saisdata` is pinned to a tag, so R-universe builds that release and not whatever is on `main`. To release a new version, push the new tag and change `branch` here.
