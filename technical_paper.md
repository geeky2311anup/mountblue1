Scaling

Scaling means making a system capable of handling more users and more work.
 When many people use a website or an app at the same time, it can become slow or stop working.
 To solve this, we use scaling. There are two types: vertical scaling and horizontal scaling.

Vertical Scaling (Scaling Up):
This means upgrading a single machine to make it stronger.
 For example, adding more RAM, faster CPU, or bigger storage.
 It is simple and quick, but it has limits because one machine cannot be upgraded forever.
 Also, if that machine fails, the whole system goes down.

Horizontal Scaling (Scaling Out):
This means adding more machines instead of upgrading just one.
 For example, using 10 normal servers instead of 1 big server.
 The workload is shared among all servers.
 This makes the system more reliable and able to handle very large numbers of users.
 If one server fails, the others still work.
 The only drawback is that it is more complex to set up.

Load Balancer:
In horizontal scaling, we use a load balancer.
 A load balancer works like a traffic police officer.
 It distributes user requests across different servers so that no server gets overloaded.
 If one server fails, the load balancer sends the requests to healthy servers.

Summary:

Scaling = improving system performance.

Vertical Scaling = upgrade one server.

Horizontal Scaling = add more servers.

Load Balancer = divides work among servers.
