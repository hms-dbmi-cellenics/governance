# Licensing

## MIT license

The majority of the Cellenics code is made available under the permissive [MIT license](https://opensource.org/licenses/MIT), as indicated in the repos' LICENSE files. This code utilizes a variety of install-time dependencies under permissive and weak copyleft licenses that are not distributed as part of the Cellenics source code.

## GPL-3.0 and R code

The R code located in the [pipeline-runner/ folder](https://github.com/hms-dbmi-cellenics/pipeline/tree/master/pipeline-runner) in the [pipeline](https://github.com/hms-dbmi-cellenics/pipeline) repo and the [r/ folder](https://github.com/hms-dbmi-cellenics/worker/tree/master/r) in the [worker](https://github.com/hms-dbmi-cellenics/worker) repo utilizes dependencies under a variety of free / open source software licenses, including some that are under GPL-3.0 or a choice of GPL-2.0 OR GPL-3.0.

Although these dependencies are similarly not distributed as part of the Cellenics source code, in order to help with license compatibility for these dependencies, the R code in the pipeline-runner/ and r/ folders is also distributed under GPL-3.0, as indicated in the COPYING files in those folders.

As a convenience for redistributors of Cellenics, please note the following additional details about a few of the R dependencies and their licenses:

* Certain of the direct dependencies of the Cellenics R code would, by default, install subdependencies that are under AGPL-3.0 and/or GPL-2.0-only. Cellenics does not use the functionality of these subdependencies, so in order to avoid installing dependencies under these licenses, Cellenics is configured to replace these with empty packages with the same names but with no content.
* [Rtsne](https://github.com/jkrijthe/Rtsne) contains several files that are [stated as being licensed under BSD-4-Clause](https://github.com/jkrijthe/Rtsne/blob/55aad4af28766b497e07db1b80f8bdb27aada801/LICENSE#L8-L36), which is viewed by some as incompatible with GPL-3.0. The author of these files has confirmed to the Cellenics project that these files may also be distributed under BSD-3-Clause, omitting the "advertising clause" provision in clause 3.
* [proxy](https://cran.r-project.org/web/packages/proxy/index.html) is currently distributed under GPL-2.0. The proxy maintainers have confirmed to the Cellenics project that it may be used under a choice of either GPL-2.0 OR GPL-3.0.
* [Rserve](https://cran.r-project.org/web/packages/Rserve/index.html) is distributed under GPL-2.0, with client libraries published under LGPL-2.1. Cellenics uses Rserve via the [RestRserve](https://cran.r-project.org/web/packages/RestRserve/index.html) project, which is distributed under a choice of either GPL-2.0 OR GPL-3.0. Our understanding is that Rserve, when used in this manner, functions as a separate work from Cellenics and therefore is compatible with Cellenics' GPL-3.0 license given the manner of usage.

Please note that the details above are provided solely as a convenience. The Cellenics project does not provide legal advice, and all Cellenics content is subject to the disclaimers of warranties and liability set forth in the applicable license texts. You should consult with your own legal counsel if you have questions regarding licenses and license compatibility.

