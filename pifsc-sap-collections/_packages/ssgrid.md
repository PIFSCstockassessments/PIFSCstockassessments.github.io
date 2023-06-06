---
title: ssgrid
permalink: /packages/ssgrid/
description:  ssgrid contains utility functions for running Stock Synthesis (SS) models on the OpenScienceGrid HTCondor network.
---

Utility functions for running [Stock
Synthesis](https://github.com/nmfs-stock-synthesis/stock-synthesis) (SS)
models on the [OpenScienceGrid](https://osg-htc.org/) (OSG)
[HTCondor](https://htcondor.org/) network.

This package facilitates running Stock Synthesis models and the
following advanced diagnostics on the OSG:

- retrospective
- R0 likelihood profile
- age-structured production model (ASPM)
- deterministic recruitment model

The *ssgrid* contains functions for:

- connecting to the OSG
- uploading files to OSG
- writing files to automatically set-up the execution of the HTcondor
  job
  - creating the HTcondor *condor_submit* script
  - creating the bash shell script executed by the *condor_submit*
    script
  - creating R scripts needed to manipulate SS files using
    [r4ss](https://github.com/r4ss/r4ss) functions in order to run
    advanced diagnostics.
- submiting the HTcondor job
- downloading completed model runs
- cleaning up directories on OSG


# ssgrid R package

[ssgrid github page (PIFSCstockassessments)](https://pifscstockassessments.github.io/ssgrid/)

