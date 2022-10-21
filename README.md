# salmon-nf

This is a [Nextflow](https://nextflow.io) workflow built by NICHD DATA Scholar to help Researchers

Using NextFlow -- we should know about:

Including:
* [Pipeline Parameters](https://www.nextflow.io/docs/latest/getstarted.html?highlight=parameters#pipeline-parameters)
* [Processes](https://www.nextflow.io/docs/latest/process.html)
* [Channels](https://www.nextflow.io/docs/latest/channel.html)
* [Operators](https://www.nextflow.io/docs/latest/operator.html)
* [Configuration](https://www.nextflow.io/docs/latest/config.html)

This file uses two processes using the [Anaconda](anaconda.org) packaging from the [bioconda channel](https://anaconda.org/bioconda):
* [curl](https://anaconda.org/bioconda/curl)
* [salmon](https://anaconda.org/bioconda/salmon)

The containers used as noted in the *`nextflow.config`* file are retrieved from the CAVATICA registry and were constructed from Dockerfiles:
* [curl-docker](https://github.com/adeslatt/curl-docker)
* [salmon-docker](https://github.com/adeslatt/salmon-docker)
