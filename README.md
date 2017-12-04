
<!-- README.md is generated from README.Rmd. Please edit that file -->
[![Build Status](https://travis-ci.org/rauschenberger/globalSeq.svg?branch=master)](https://travis-ci.org/rauschenberger/globalSeq) [![Coverage Status](https://codecov.io/github/rauschenberger/globalSeq/coverage.svg?branch=master)](https://codecov.io/github/rauschenberger/globalSeq?branch=master)

<!--[![Platforms](http://www.bioconductor.org/shields/availability/release/globalSeq.svg)](http://bioconductor.org/packages/devel/bioc/html/globalSeq.html#archives)
[![Downloads](http://www.bioconductor.org/shields/downloads/globalSeq.svg)](http://bioconductor.org/packages/stats/bioc/globalSeq/)
[![Posts](http://www.bioconductor.org/shields/posts/globalSeq.svg)](https://support.bioconductor.org/t/globalseq/)
[![in Bioc](http://www.bioconductor.org/shields/years-in-bioc/globalSeq.svg)](http://bioconductor.org/packages/devel/bioc/html/globalSeq.html#since)
[![Build](http://www.bioconductor.org/shields/build/devel/bioc/globalSeq.svg)](http://bioconductor.org/checkResults/devel/bioc-LATEST/globalSeq/)
[![Commits](http://www.bioconductor.org/shields/commits/bioc/globalSeq.svg)](http://bioconductor.org/packages/devel/bioc/html/globalSeq.html#svn_source)
[![Coverage Status](http://www.bioconductor.org/shields/coverage/devel/globalSeq.svg)](https://codecov.io/github/Bioconductor-mirror/globalSeq/branch/master)-->
Scope
-----

Testing for association between RNA-Seq and other genomic data is challenging due to high variability of the former and high dimensionality of the latter.

Using the negative binomial distribution and a random effects model, we developed an omnibus test that overcomes both difficulties. It may be conceptualised as a test of overall significance in regression analysis, where the response variable is overdispersed and the number of explanatory variables exceeds the sample size.

The proposed test can detect genetic and epigenetic alterations that affect gene expression. It can examine complex regulatory mechanisms of gene expression.

Installation
------------

The package globalSeq depends on [R &gt;= 3.0.0](https://cran.r-project.org/), and is available from [Bioconductor](http://bioconductor.org/packages/globalSeq/):

``` r
source("https://bioconductor.org/biocLite.R")
BiocInstaller::biocLite("globalSeq")
```

Alternatively, it can be installed from [GitHub](https://github.com/rauschenberger/globalSeq). This requires the package [devtools](https://cran.r-project.org/web/packages/devtools/README.html):

``` r
devtools::install_github("rauschenberger/globalSeq",build_vignettes=TRUE)
```

Please restart R before loading the package and its documentation:

``` r
library(globalSeq)
utils::help(globalSeq)
utils::vignette("globalSeq")
```

Reference
---------

A Rauschenberger, MA Jonker, MA van de Wiel, and RX Menezes (2016). Testing for association between RNA-Seq and high-dimensional data. BMC Bioinformatics. 17:118. [html](http://dx.doi.org/10.1186/s12859-016-0961-5) [pdf](http://www.biomedcentral.com/content/pdf/s12859-016-0961-5.pdf)

<!-- [html]
<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');
  ga('create', 'UA-96845398-2', 'auto');
  ga('send', 'pageview');
</script>
-->
