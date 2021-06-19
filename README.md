# Dynamic Network Simulation 

### Aim
A network consists of 7 nodes n0-n6 connected in ring topology. Each link is a duplex connection of 10Mbps bandwidth and 10ms latency. Data packets need to be transferred from node n0 to node n3 taking the shortest path. This is a dynamic network where the routing adjusts to link failures as node n2 goes in `sleep mode`. 

### Network Topology
<a href="url"><img src="https://github.com/arshitas/Dynamic_Network/blob/main/topology.png" align="center" height="480" width="520" ></a>

### Results

**Fig 1:**  Starting from 0.5s node n0 sends data traffic to n3 taking the shortest path

<a href="url"><img src="https://github.com/arshitas/Dynamic_Network/blob/main/OUTPUT/Fig%201.png" align="center" height="480" width="720"></a>

**Fig 2:** At 1.0 packets are dropped as node n2 goes in sleep mode resulting in link failure between n1-n2 and n2-n3

<a href="url"><img src="https://github.com/arshitas/Dynamic_Network/blob/main/OUTPUT/Fig%202.png" align="center" height="480" width="720"></a>

**Fig 3:** Dynamic routing ensures data traffic flows through a different route

<a href="url"><img src="https://github.com/arshitas/Dynamic_Network/blob/main/OUTPUT/Fig%203.png" align="center" height="480" width="720"></a>

**Fig 4** After 2.0s, node n2 is re-established and takes the shortest route

<a href="url"><img src="https://github.com/arshitas/Dynamic_Network/blob/main/OUTPUT/Fig%204.png" align="center" height="480" width="720"></a>
