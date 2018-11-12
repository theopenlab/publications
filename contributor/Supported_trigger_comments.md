# Supported trigger comments

If a repository have connected to OpenLab, when pull request of the repository is `opened`, `changed` and `reopened`, those events will trigger OpenLab integration tests automatically by default, and test result will be pushed back into the comments of related pull request. If we want to trigger to retest the integration tests manually, please input the following special keyword in comments of pull request, enjoy it.

## kubernetes/cloud-provider-openstack
https://github.com/kubernetes/cloud-provider-openstack/

| Comment keyword | Status | Description |
| --------------- | ------ | ----------- |
| `/retest` | **DONE** | Rerun all of the following unit and acceptance tests |
| `/test all` | **DONE** | Rerun all of the following unit and acceptance tests |
| `/test cloud-provider-openstack-unittest` | **DONE** | Run unit tests |
| `/test cloud-provider-openstack-acceptance-test-lb-octavia`   | **DONE** | Run integration tests against OpenStack LBaaS and Octavia |
| `/test cloud-provider-openstack-acceptance-test-keystone-authentication-authorization` | **DONE** | Run integration tests against OpenStack Keystone |
| `/test cloud-provider-openstack-acceptance-test-k8s-cinder` | **DONE** | Run integration tests against OpenStack Cinder, **kubernetes.io/cinder** provisioner |
| `/test cloud-provider-openstack-acceptance-test-standalone-cinder` | **DONE** | Run integration tests against OpenStack Cinder, **openstack.org/standalone-cinder** provisioner |
| `/test cloud-provider-openstack-acceptance-test-csi-cinder` | **DONE** | Run integration tests against OpenStack Cinder, **CSI Cinder** |
| `/test cloud-provider-openstack-acceptance-test-flexvolume-cinder` | **DONE** | Run integration tests against OpenStack Cinder, **Flexvolume Cinder** |
| `/test cloud-provider-openstack-acceptance-test-e2e-conformance` | **DONE** | Run Kubernetes(master) E2E conformance test with cloud-provider-openstack |
| `/test cloud-provider-openstack-acceptance-test-e2e-conformance-stable-branch-v1.10` | **DONE** | Run Kubernetes(v1.10) E2E conformance test with cloud-provider-openstack |

**NOTE:** E2E conformance test result is shown in kubernetes testgrid dashboard http://k8s-testgrid.appspot.com/conformance-cloud-provider-openstack too.

## gophercloud/gophercloud
https://github.com/gophercloud/gophercloud/

| Comment keyword | Status | Description |
| --------------- | ------ | ----------- |
| `recheck` | **DONE** | Rerun all test jobs against OpenStack master, same with PR event trigger, include: unit and integration tests |
| `recheck stable/mitaka` | **DONE** | Run integration tests against OpenStack Mitaka release |
| `recheck stable/newton` | **DONE** | Run integration tests against OpenStack Newton release |
| `recheck stable/ocata` | **DONE** | Run integration tests against OpenStack Ocata release |
| `recheck stable/pike` | **DONE** | Run integration tests against OpenStack Pike release |
| `recheck stable/queens` | **DONE** | Run integration tests against OpenStack Queens release |
| `recheck stable/rocky` | **DONE** | Run integration tests against OpenStack Rocky release |

## terraform-providers/terraform-provider-openstack
https://github.com/terraform-providers/terraform-provider-openstack/

| Comment keyword | Status | Description |
| --------------- | ------ | ----------- |
| `recheck` | **DONE** | Rerun all test jobs against OpenStack master, same with PR event trigger, include: unit and integration tests |
| `recheck stable/mitaka` | **DONE** | Run integration tests against OpenStack Mitaka release |
| `recheck stable/newton` | **DONE** | Run integration tests against OpenStack Newton release |
| `recheck stable/ocata` | **DONE** | Run integration tests against OpenStack Ocata release |
| `recheck stable/pike` | **DONE** | Run integration tests against OpenStack Pike release |
| `recheck stable/queens` | **DONE** | Run integration tests against OpenStack Queens release |
| `recheck stable/rocky` | **DONE** | Run integration tests against OpenStack Rocky release |
| `recheck designate` | **DONE** | Run integration tests against OpenStack Designate master branch |
| `recheck trove` | **DONE** | Run integration tests against OpenStack Trove master branch |
| `recheck lbaas` | **DONE** | Run integration tests against OpenStack LBaaS master branch |
| `recheck fwaas` | **DONE** | Run integration tests against OpenStack FWaaS master branch |
