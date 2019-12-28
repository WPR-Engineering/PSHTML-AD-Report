# Additional VMWare Reporting for PSHTML-AD-Report

This fork of the PSHTML-AD-Report project adds functionality to the existing report tool so that various metrics can be collected from VMWare infrastructures.

The resulting report will contain the Active Directory reporting provided by the base project bwya77/PSHTML-AD-REPORT, in addition to a new tab that provides reporting on various VMWare metrics obtained from vCenter.

This script is designed to run from a secure jump station or other secure origin that has read access to both vCenter and Active Directory.

The additional tab introduced will contain the following VMWare metrics:

* List of all VMs 
* List of open snapshosts 
* List of VMs with outdated VMware tools 
* List of all datastores (current capacity, max capacity) 
* List of all port groups 
* List of all ESXi hosts
