# Test Request

## Test request

The OpenLab provides two kinds of resources: VM\(Virtual Machine\) and PM\(Physical Machine\) for testing. Currently we only utilize virtual machines to support automating jobs for SDKs and tools integration test with OpenLab CI. On the other hand you can request PMs for your special testing if VM can't meet your testing needs.

1. Submit a [test request](https://github.com/theopenlab/openlab/issues/new?template=integration_test_request.md&labels=integration%20case) to OpenLab, fill out some information to show your test cases like what testing scenario are you planning to implement, what kind of machines \(VMs or PMs\) and how many do you expect to use and so on 
2. The governance team @theopenlab/governance will confirm the request to check whether it is acceptable, if yes then will add it into [TODO list](https://github.com/orgs/theopenlab/projects/1#column-1860008)
3. The test request in TODO list can be assigned, if you wish to work on it please pick it up, move it to [IN PROGRESS list](https://github.com/orgs/theopenlab/projects/1#column-1860011), edit it to add the development plan into comments
4. Begin your development and test if you picked up the test request, and follow [development guide](development-guide.md).

## Share your testing result

* If you use OpenLab CI, the test result will be shown on [http://status.openlabtesting.org/builds](http://status.openlabtesting.org/builds) automatically
* If you use physical machine to test, please commit the test result into comments of test request related issue. A blog also is a good choice to show more details of testing.

