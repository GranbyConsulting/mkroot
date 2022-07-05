# mkroot

Generate Root Certificate for Local Addresses

This projects contains scripts and configuration files to generate
a root certificate that can be used for hosts with .local addresses
or IPv4 addresses from the well-known local ranges. Users can thus
trust this cert to allow embedded devices to automatically create
certs that will avoid errors while browsing there web servers, while
avoiding the need to trust each one. Since the root cert is defined
to only apply to local addresses, the risk in trusting it is low.
