# 44.32.99.0/24

Create an issue or a pull request to request for some IPs.

# NOTE

1. All allocations are for 'non-commercial use'.
2. All allocations are for 'furthering the use of amateur radio'.
3. Jie Feng\'s name is on the paperwork.  Speak to him if you
have a special request, first.
4. Sanjeev will provide tunnels and bandwidth.  This is for the 
reasons \#1 and \#2 above, only.
5. All allocations, even if they follow the rules (such as they are),
are subject to renumbering; either for operational reasons or
because future us will be smarter than present us.

# Subnet Plan

The Network we have is a /24.  I propose to divide it as folllows:

- ''44.32.99.0/26''. This will be for DCS1 and SARTS common equpment, 
such as Repeater Links, etc.  It will be a flat network.
- ''44.32.99.64/26''. RESERVED
- ''44.32.99.128/25''.  This will be for leaf nodes, coming in
via VPN.  The VPN hub will be 44.32.99.254.

To make routing a bit easier for those members who have multiple
IP addresses/nodes, 
- Requests for single IP addresses should start 'downwards* from ''.253''.  
- Requests for 2 addresses should start *downwards* from ''.192''.  
- Requests for 4 addresses should start *upwards* from ''.129''.
- Requests for more than these contiguous addresses are special
cases anyway, we assume we know what we are doing.


