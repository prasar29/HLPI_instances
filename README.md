The datafile "hub25node.dat" contains Civil Aeronautics Board dataset of 25 nodes and the datafile "AP50.dat" contains first 50 nodes of Australian Post dataset. These datases are commonly used to create test instances for hub location problems. 
In the datasets, the first matrix contains the demand between the nodes, while the next matrix contains the distances between the nodes.
In the paper "An Exact Method for Trilevel Hub Location Problem with Interdiction" we generate experimental instances through varying these aspects: Weights, Co-efficient of transhipment, No. of hubs to locate, and No. of hubs to interdict
Weights (w_1,w_2) are varied in the following sets {(0.2, 0.8), (0.4, 0.6), (0.5,0.5), (0.6, 0.4), (0.8, 0.2)}
Co-efficient of transhipment is varied in the set {0.1, 0.5, 0.9}
No. of hubs to locate (p) is varied in the set {5, 10}
No. of hubs to interdict (r) is varied in the set {2,3,4} for p = 5; and (7,8,9) for p = 10 (CAB dataset), and (8,9) for p = 10 (AP dataset).
