# Firewall

The code establishes an SSH connection to a Cisco router using Netmiko and enters enable mode. 
It then sends a set of configuration commands to the router to configure a basic firewall policy.
The policy consists of an extended ACL named "firewall" that permits all IP traffic and logs it, and applies the ACL to incoming traffic on the gigabitethernet0/0 interface. 
Finally, the code prints the output of the configuration commands and disconnects from the router.
Note that the specific commands used to configure a firewall policy will depend on the vendor and model of the router, as well as the desired configuration.
The Netmiko library provides support for a wide range of network devices and vendors, so be sure to consult the documentation for the library and the specific device you are configuring to ensure that the appropriate commands are used.
it's important to ensure that your firewall policy is appropriate for your specific security needs and compliance requirements.
