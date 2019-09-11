# zealsd.github.io
ZealOS Debian/BSD-Based Operating System Website

## Introduction

- ZealOS is a temporary working name.
- Fork of Debian with emphasis on server / distributed architecture or microservice arch.  
- Our own packages may replace some base packages, but should be pretty minimal.  Again, these packages are just forks of the upstream copies.
  - Not all Debian packages, even the "Debian-only/Debian-specific" ones such as `base-files`.
- Our own packages will be (actually, already are) available in the apt repo. 
- I need to find a place to host this apt repo publicly.
- The operating system effectively revolves around a piece of software called `centrald` or `dcentd`, depending on which version you use.  This is a centralized but distribtued command & control system targeting mainly: Provisioning, Deployment of Applications, and System Monitoring. 
- Despite being centralized, it still attempts to follow the `U*NIX` philosophy.

## Ideas / Future

- Operating system installed by git, controlled by `dcentd` and `cctl `
- Need to work on semantic versioning. 
