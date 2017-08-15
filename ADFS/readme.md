# adfs-6vms-regular-template-based

#This template deploys x2 VMs (DC), x2 VMs (ADFS) and x2 VMs (WAP) into a new or existing Vnet; DCs and ADFS will be deployed to the Internal subnet and the WAP to the DMZ. All of these VMs will be configured within an Availability Set for HA purposes, NSGs between the Intenral-DMZ & DMZ-Internet and Load Balancers for ADFS and WAP, the latter with a public IP. There will be x3 storage accounts, x2 of them to store the OS & data disks and the third for diagnosis.
