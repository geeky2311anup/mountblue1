# Scaling with Load Balancers and Scaling Types

## Abstract
This paper explains how to solve performance and scaling problems in a project. The focus is on using load balancers and the two main types of scaling, vertical and horizontal. The goal is to make the system faster and more reliable when more users are using it.

## Introduction
In many projects, performance and scaling become issues when the number of users grows. If the system is not able to handle the traffic, users face slow response or downtime. The aim of this paper is to explain simple scaling methods and how load balancers can help.

## Background / Related Work
Scaling means improving the system so that it can handle more work. Vertical scaling means increasing the power of one machine, while horizontal scaling means adding more machines. A load balancer helps in spreading user requests across multiple servers.

## Method / Approach
### Data / Inputs
* Information about user requests.
* Current server capacity.

### Steps
1. Check how much load the system can handle now.
2. Study vertical scaling options like adding CPU or memory.
3. Study horizontal scaling options like adding new servers.
4. Use a load balancer to divide requests fairly.
5. Measure the improvement in performance.

### Tools
* Load Balancer – used to share traffic between servers.
* Monitoring tools – used to check system usage and find limits.

## Implementation
* Folder structure
  * `docs/` – this technical paper
  * `src/` – project source code
* Key components
  * Load balancer setup
  * Server configuration
* Assumptions
  * The project will grow in user numbers.
  * Extra servers are available when needed.

## Results
* The system can now handle more users without slowing down.
* Response time is improved.
* Horizontal scaling gave better results than only vertical scaling.

## Discussion
The results show that load balancers with horizontal scaling are better for big systems. Vertical scaling is simple but limited because one server cannot grow forever. A mix of both methods can be used. In the future, the system can add auto-scaling to adjust servers based on traffic.

## Conclusion
Scaling is very important for system performance. By using load balancers and choosing the right scaling method, projects can handle more users and avoid downtime. The main idea is to grow the system in a simple and reliable way.

## References
* DigitalOcean, [What is Load Balancing?](https://www.digitalocean.com/community/tutorials/what-is-load-balancing), 2023.    
* Nginx, [Load Balancing Documentation](https://docs.nginx.com/nginx/admin-guide/load-balancer/), 2023.
* GeeksforGeeks, [Horizontal and Vertical Scaling in System Design](https://www.geeksforgeeks.org/system-design/system-design-horizontal-and-vertical-scaling/), 2023.
