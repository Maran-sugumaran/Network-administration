# Network-administration
Like every IT company, the Uplink Corporation has its own network. But, unlike the rest of the companies around the world, Uplink's network is subject to very specific restrictions:

Any pair of servers within the network should be directly connected by at most 1 link.
Each link is controlled by some specific network administrator.
No server has more than 2 links connected to it, that are controlled by the same administrator.
For easier management, links controlled by some administrator cannot be redundant (this is, removing any link will disconnect some two previously connected servers)
Notice that 2 connected servers might not have any direct link between them. Furthermore, in order to keep the network in a secured status, Uplink directives periodically try to perform some modifications over the network to mislead hackers. The problem is, having such a huge network, they need a software to efficiently simulate the network status after any of such modifications. You have been assigned to write the core section of that software.

Operations performed by the directives are:

Change the administrator assigned to some particular link.
Place some number of security devices along a particular link.
Also, given a network administrator, they would like to know how many devices are in the path created by links controlled by that administrator (if any) between 2 servers.
