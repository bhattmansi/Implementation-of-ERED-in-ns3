# Implementation-of-ERED-in-ns3

## Course Code: CS822

## Assignment: #GP1

### Overview
Effective RED (ERED) [1] aims to reduce packet loss rates in a simple and scalable manner by making several refinements and by controlling packet dropping function both with average queue size and instantaneous queue size. The original paper of ERED used ns-2 [2] for comparing its performance against RED [3]. However, till date the implementation of ERED is not publicly available in any network simulator. This repository provides an implementation of ERED algorithm in ns-3 [4].


### References

[1] [Abbasov, B. & Korukoglu, S (2009). Effective RED: An algorithm to improve RED's performance by reducing packet loss rate](https://www.sciencedirect.com/science/article/pii/S1084804508000684)

[2] http://www.isi.edu/nsnam/ns/

[3] [Floyd, S. & Jacobson, V. (1993). Random early detection gateways for congestion avoidance](http://ieeexplore.ieee.org/document/251892/).

[4] http://www.nsnam.org/
