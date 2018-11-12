# Connect to OpenLab

Follow the steps below to connect the OpenLab:

1. Submit an issue to target project that plan to connect OpenLab, let target project maintainers know what we want to do, and discuss some details, looks like: [gophercloud Issue 592](https://github.com/gophercloud/gophercloud/issues/592)
2. To define CI jobs running in zuul pipelines if the above issue is approved, there are two choices to do it:
   * new a file named **.zuul.yaml** under the root directory of target project, edit the file to define which CI jobs will run in zuul pipelines, then submit a pull request to target project, like: [gophercloud PR 593](https://github.com/gophercloud/gophercloud/pull/593)
   * if adding the new file is not allowed, please edit the content in **projects.yaml** file under the directory `./zuul.d` of [openlab-zuul-jobs](https://github.com/theopenlab/openlab-zuul-jobs)
3. Target project maintainer should install **TheOpenLab-CI** [github APP](https://github.com/apps/theopenlab-ci), so that OpenLab CI system and target project can communicate with each other, **TheOpenLab-CI** github APP only require basic permissions to update check status and commit test result log URL in PR comments, you can see permission details in APP installation web page.

