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
  
## Scenario -1
* Error running 'minishift start' on Windows Powershell

*Error:
PS C:\minishift> .\minishift.exe start
-- Starting profile 'minishift'
-- Check if deprecated options are used ... OK
-- Checking if https://mirror.openshift.com is reachable ... OK
-- Checking if requested OpenShift version 'v3.11.104' is valid ... OK
-- Checking if requested OpenShift version 'v3.11.104' is supported ... OK
-- Checking if requested hypervisor 'virtualbox' is supported on this platform ... OK
-- Checking if VirtualBox is installed ... FAIL
   See the 'Installing Prerequisites for Minishift' topic (https://access.redhat.com/documentation/en-us/red_hat_container_development_kit/3.9/html-single/getting_started_guide/#install-prerequisites) for more information
PS C:\minishift>

