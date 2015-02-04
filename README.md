# hard-drive-analysis

Analysis of hard drives and their failures

*Data is from the following sources*:

* https://www.backblaze.com/blog/hard-drive-data-feb2015/
* https://en.wikipedia.org/wiki/S.M.A.R.T.
* https://www.backblaze.com/hard-drive-test-data.html


## Analysis

* We can think of this as a time series analysis.
* We can use Google's [CausalImpact](https://github.com/google/CausalImpact) R package to figure out which SMART factors predict failure