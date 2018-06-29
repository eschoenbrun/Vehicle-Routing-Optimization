# Vehicle-Routing-Optimization

Vehicle Routing Problems (VRP) are essential to any business incorporating transportation in its operations.  Whether it’s a retailer transporting merchandise from warehouses to stores or a service provider delivering goods to end users, finding the optimal sequence of stops resulting in improvements in supply chain performance may lead to notable financial gains and competitive advantages.

Typically, in VRP problems the network’s edges are the distances between the two destinations.  However, in dense, urban areas where congestion is common, distance is not the optimal measure of cost reduction.  Instead, we propose that time traveled should be the baseline metric, since it more accurately represents the entity’s transportation cost.

There is additional value in a default route where a corporation can anticipate costs, and while allowing operators to follow a GPS system might optimize routing in real-time, it is much more difficult to forecast costs like maintenance schedules and hourly wages.

We have built a network using a dataset of 1.1 Billion NYC TLC trips, designating five destination points from the depot of a theoretical company.  Using several shortest-path algorithms, we determine the optimal path between two destinations, and calculate its mean travel. Using the new weights to build a high-level network, we can now run several VRP algorithms to determine the optimal sequence of stops. 
