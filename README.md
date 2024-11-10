# Basic Load Balancer

A simple load balancer built with Node.js to distribute requests across multiple backend servers. This project demonstrates how to implement load balancing using both **Round Robin** and **Least Connection** algorithms to efficiently distribute requests.

## Features

- **Round Robin Load Balancing**: Distributes requests evenly across servers in a circular order, ensuring each server receives an equal number of requests over time.
- **Least Connection Load Balancing**: Directs each request to the server with the fewest active connections, optimizing server load based on current activity.

