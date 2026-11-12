# jmozez.r-universe.dev

Registry for <https://jmozez.r-universe.dev>, which builds ready-to-install
binaries of these R packages for Windows, macOS and Linux:

| Package | Source | Website |
|---|---|---|
| tidydiversity | <https://github.com/jmozez/tidydiversity> | <https://tidydiversity.in4metrix.dev> |
| tidymapr | <https://github.com/jmozez/tidymapr> | <https://tidymapr.in4metrix.dev> |

Install without compiling:

```r
install.packages(c("tidydiversity", "tidymapr"),
  repos = c("https://jmozez.r-universe.dev", "https://cloud.r-project.org"))
```
