# Linux



NETFILTER CHAINS
1. INPUT - used for filtering incoming packets. Our host is the 
packet destination.
2. OUTPUT - used for filtering outgoing packets. Our host is the 
source of the packet.
3. FORWARD - used for filtering routed packets. Our host is router.
4. PREROUTING - used for DNAT / Port Forwarding
5. POSTROUTING - used for SNAT (MASQUERADE)
