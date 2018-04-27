<a id="devex-badge" rel="Delivery" href="https://github.com/BCDevExchange/assets/blob/master/README.md"><img alt="In production, but maybe in Alpha or Beta. Intended to persist and be supported." style="border-width:0" src="https://assets.bcdevexchange.org/images/badges/delivery.svg" title="In production, but maybe in Alpha or Beta. Intended to persist and be supported." /></a>

# Municipal Solid Waste Disposal in B.C.

A set of R scripts to create the municipal solid waste disposal in B.C. indicator published on [Environmental Reporting BC](https://www2.gov.bc.ca/gov/content?id=B71460AF7A8049D59F8CBA6EE18E93B8).


### Data

The  data used for the indicator is available from the [B.C. Data Catalogue](https://catalogue.data.gov.bc.ca/dataset/d21ed158-0ac7-4afd-a03b-ce22df0096bc) under the [Open Government Licence - British Columbia](https://www2.gov.bc.ca/gov/content?id=A519A56BC2BF44E4A008B33FCF527F61).


### Code

There is one R script and one RMarkdown file associated with the indicator.

Most packages can be installed from CRAN using `install.packages()`, but you will need to install [envreportutils](https://github.com/bcgov/envreportutils), [bcmaps](https://github.com/bcgov/bcmaps), and [bcmaps.rdata](https://github.com/bcgov/bcmaps.rdata) using remotes:

```r
install.packages("remotes") # If you don't already have it installed

library(remotes)
install_github("bcgov/envreportutils")
install_github("bcgov/bcmaps")
install_github("bcgov/bcmaps.rdata")
```

### Getting Help or Reporting an Issue

To report bugs/issues/feature requests, please file an [Issue](https://github.com/bcgov-c/msw-disposal-indicator/issues/).

### How to Contribute

If you would like to contribute, please see our [CONTRIBUTING](CONTRIBUTING.md) guidelines.

Please note that this project is released with a [Contributor Code of Conduct](CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.

### License

    Copyright 2018 Province of British Columbia

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at 

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.


This repository is maintained by [Environmental Reporting BC](http://www2.gov.bc.ca/gov/content?id=FF80E0B985F245CEA62808414D78C41B). Click [here](https://github.com/bcgov/EnvReportBC-RepoList) for a complete list of our repositories on GitHub.