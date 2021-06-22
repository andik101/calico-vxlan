# calico-vxlan
Enabled VXLAN on the default IP pool


## Fixed the Calcio crash issue
Calico supports two types of encapsulation: VXLAN and IP in IP. VXLAN is supported in some environments where IP in IP is not (for example, Azure, AWS)

###Calico MTU with VXLAN (IPv4)
In this yaml the MTU sizes is set to 1410, you can change it to your appropriate MTU size.
