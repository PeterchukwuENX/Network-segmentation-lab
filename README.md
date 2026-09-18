Network Segmentation Lab

This one's about building a small business-style network from scratch in Cisco Packet Tracer - a few VLANs, a router handling traffic between them, and some access rules controlling who can actually talk to who.

The reasoning behind it: understanding networking concepts on paper is one thing, but actually building a network and watching traffic get blocked or allowed based on rules I wrote is a completely different level of understanding. This is me doing that.

What I'm building
- 2-3 VLANs (Staff, Guest, Servers) on a single network, kept logically separate from each other
- A router handling traffic between those VLANs (inter-VLAN routing)
- Access rules (ACLs) that stop the Guest network from reaching the Servers network - the kind of segmentation real networks use so a compromised guest device can't just wander into sensitive systems

Why I'm doing this
Part of my path toward a SOC analyst role. Reading network diagrams and alerts makes a lot more sense once you've actually built the thing being diagrammed - segmentation especially, since it's one of the first things that comes up when talking about limiting how far an attacker can move once they're in.
