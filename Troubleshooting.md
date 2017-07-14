# DO081x - Fundamentals of Containers, Kubernetes, and Red Hat OpenShift
## Lab Environment Troubleshooting Guide
As we collect reports of installation problems we will publish resolutions/suggestions here. Official environments tested are:

* macOS 10.12
* Microsoft Windows 10 Pro
* Red Hat Enterprise Linux 7.3. 

We may not be able to assist students with environments outside of this list.

## Scenarios
* Error configuring authorization on host
  * Try executing the following:
  ```
  minishift delete
  minishift start
  ```
