
# Home

Welcome to the documentation for the [ACCESS-CM3 model configurations](https://github.com/ACCESS-NRI/access-cm3-configs)! 


## ACCESS-CM3 Documentation Overview

See the navigation links on the left. Some reading tips, see:

 - [Contributing](/contributing) 
 - [Inputs](/inputs/Forcing-data-models) 
 - [Configuration choices/Configurations](/configurations/Overview/) 
 - [Infrastructure](/infrastructure/Architecture/) 

## access-cm3-configs Overview
ACCESS-CM3 configurations are provided via branches in the [access-cm3-configs](https://github.com/ACCESS-NRI/access-cm3-configs) GitHub repository, this repository is currently private. The [access-cm3-configs](https://github.com/ACCESS-NRI/access-cm3-configs) repository contains several configurations using the following components:

- [MOM5](https://github.com/ACCESS-NRI/mom5) ocean model
- [UM](https://github.com/ACCESS-NRI/UM) atmosphere model

All the configurations use the [Payu](https://payu.readthedocs.io/en/latest/) and rose/cylc workflow management tools, and pre-built executables available on [NCI](https://nci.org.au/).

### Repository structure

Each configuration in [github.com/ACCESS-NRI/access-cm3-configs](https://github.com/ACCESS-NRI/access-cm3-configs) repository is stored as a git branch. Most of the branches are named according to the following naming scheme:


#### Supported configurations



#### How to use this repository to run a model

All configurations use [payu](https://github.com/payu-org/payu) and rose/cylc to run the model.

This repository contains many related experimental configurations to make support
and discovery easier. As a user it does not necessarily make sense to clone all the
configurations at once.

In most cases only a single experiment is required. If that is the case, choose which experiment and then run

```sh
git clone -b <experiment> https://github.com/ACCESS-NRI/access-cm3-configs <experiment>
```

and replace `<experiment>` with the branch name or tag of the experiment you wish to run.

[ACCESS-Hive](https://access-hive.org.au/) contains [detailed instructions for how to configure and run ACCESS models with `payu`](https://access-hive.org.au/models/run-a-model).

#### CI and Reproducibility Checks

This repository makes use of GitHub Actions to perform reproducibility checks on model config branches.


