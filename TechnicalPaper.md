# Scaling in modern systems

In modern distributed systems, ensuring high availability and performance requires load-balancing and scaling.
Load-balancing is a method of distributing incoming traffic equally across all the servers, thus improving reliability.
Load-balancing can be achieved in two ways - 
* Scaling horizontally
* Scaling vertically

## Horizontal scaling
Horizontal scaling means increasing the number of servers available to decrease the workload on an individual machine.
  ### Advantages
  * Superior load distribution
  * Enhanced scalability
  * Fault tolerance
  ### Disadvantages
  * System complexity
  * Architectural constraints

## Vertical scaling
Vertical scaling means increasing the power of an individual machine, i.e., adding more RAM or storage to the dedicated server.
  ### Advantages
  * Cost-effective
  * Less need for software changes
  * Less complicated maintenance
  ### Disadvantages
  * Higher possibility of shutdown
  * Single point of failure

## Conclusion
Both horizontal scaling and vertical scaling have their own sets of benefits and limitations.
The factors one needs to consider while choosing either are factors such as cost, maintenance, scalability, performance, and complexity.

## References 
* [Load Balancer Explained | System Design Basics – Gaurav Sen, YouTube](https://www.youtube.com/watch?v=K0Ta65OqQkY)
* [Vertical vs. Horizontal Scaling - Gaurav Sen, YouTube](https://www.youtube.com/watch?v=xpDnVSmNFX0&t=312s)
* [Introduction to load balancing - Design Gurus](https://www.designgurus.io/course-play/grokking-system-design-fundamentals/doc/introduction-to-load-balancing) 



  
  
