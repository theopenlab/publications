---
description: >-
  Find out a bit more about what OpenLab is, what we are documenting, and links
  to documents.
---

# Introduction
## OpenLab

OpenLab is a community-led program to test and improve support for the cloud-related SDKs/Tools as well as platforms like Kubernetes, Terraform, CloudFoundry and more. The goal is to improve the usability, reliability and resiliency of tools and applications for hybrid and multi-cloud environments.

## How to join OpenLab

There is plenty of room for helping to shape of future of OpenLab and ensuring things run smoothly. If you are interested in OpenLab system, please follow the guidelines below:

### To be an OpenLab member
Join us to be a member of OpenLab firstly, then you will find out what's happening in OpenLab, what fellow open source community members are doing using OpenLab resources, also as a member you can access OpenLab resources for your testing, please follow the simple [member application](Member_Application.md) guide. Then you will visit OpenLab [status board](https://github.com/orgs/theopenlab/projects/1). 

### Test request
If you have an idea or real use case about some integration scenarios like integrating Kubernetes and OpenStack, and plan to do proof of concept(POC) against some technologies, all you have to do is just sharing your idea and use case in OpenLab, if others are interested in your case, they will pick up your task and complete the subsequent testing work, pay attention on updating of OpenLab [web site](https://openlabtesting.org/explore/), we will share the test result on it. Start your test request [here](./contributor/Testing_Request.md) now.

### Development
The main work of OpenLab is to provide an auto integration testing for different upstream tool chains of OpenStack, e.g. Gophercloud, Terraform. Always we have to add CI jobs for the test requests submitted to OpenLab, if you are interesting in this job, please follow [development guide](Development_guide.md).

### Resource sponsoring
The OpenLab has multiple resource pools(virtual machine, physical machine and device) provided by multiple cloud providers to run testing jobs, like VEXXHOST, OpenTelekomCloud, Citynetwork and so on. Thanks to OpenLab sponsors we can offer both virtual machine and physical machine to users for their own tests. We'd very appreciate it if you would like to [donate](./contributor/Resource_Sponsor.md) resources to OpenLab.

## References
* OpenLab web site is hosted on [OpenLab](https://openlabtesting.org/)
* Join OpenLab IRC channel `#askopenlab` on freenode.net, if you have no idea how to do it, see the [guide](https://freenode.net/kb/answer/chat)
* OpenLab CI Jobs' [status](http://status.openlabtesting.org/status)
* Source code of OpenLab CI jobs is hosted on [openlab-zuul-jobs](https://github.com/theopenlab/openlab-zuul-jobs)
* The OpenLab CI github APP is hosted on [github APP](https://github.com/apps/theopenlab-ci)