# openstack-ops-tools
This is a repository of useful tools we use for working with openstack.

## portping
This tool has been renamed to serviceping and is now maintained in it's
own github repository:

    https://github.com/yahoo/serviceping

## get_instance_info
Generate an instance state based on information from libvirt on the hypervisors
and information from the openstack nova service.

This is useful to generate state information that can be done before and after
operational actions to see potential issues.