# robotframework-pyvmomi

Introducing robotframework-pyvmomi

Expose VMWare API as robotframework keywords.

The reason for this robotframework package is to integrate the incredibly useful PyVmomi project with the robotframework test framework. 
In the course of working on system management software, We found that there is no inbuilt robotframework package to communicate with vCenter for testing purposes, This package helps the robotframework users communicate with vCenter and perform various operations.

This is possible in several ways, but the cleanest route seemed to be to expose a subset of the VMWare SDK to robotframework through keywords. PyVmomi has already done a lot of this work and we don't want to replicate their effort, so this is just a thin layer between the two.

# Under Development. Coming Soon....
