[![CircleCI](https://circleci.com/gh/dockstore/dockstore.svg?style=svg)](https://circleci.com/gh/dockstore/dockstore)
[![codecov](https://codecov.io/gh/dockstore/dockstore/branch/develop/graph/badge.svg)](https://codecov.io/gh/dockstore/dockstore)
[![Website](https://img.shields.io/website/https/dockstore.org.svg)](https://dockstore.org)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7259426.svg)](https://doi.org/10.5281/zenodo.7259426)

[![Uptime Robot status](https://img.shields.io/uptimerobot/status/m779655940-a297af07d1cac2d6ad40c491.svg)]()


# Dockstore

Dockstore provides a place for users to share tools and workflows encapsulated in Docker and described with the Common 
Workflow Language (CWL), WDL (Workflow Description Language), Nextflow, or Galaxy. This enables scientists to share analytical 
workflows so that they are  machine readable as well as runnable in a variety of environments. While the 
Dockstore is focused on serving researchers in the biosciences, the combination of Docker + workflow languages can be used by 
anyone to describe the tools and services in their Docker images in a standardized, machine-readable way.  
Dockstore is also a leading implementor of the GA4GH API standard for container registries, [TRS](https://www.ga4gh.org/news/tool-registry-service-api-enabling-an-interoperable-library-of-genomics-analysis-tools/). The usage of this is to enumerate the docker containers 
(from quay.io and docker hub) and the workflows (from github/bitbucket/local) that are available 
to users of Dockstore.org.

For the live site see [dockstore.org](https://dockstore.org)

This repo contains the web service component for Dockstore as well as collecting issues for the project as a whole. 

For the related web UI see the [dockstore-ui](https://github.com/dockstore/dockstore-ui2) project.
For the related CLI see the [cli](https://github.com/dockstore/cli) project.


