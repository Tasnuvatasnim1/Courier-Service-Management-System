# Courier-Service-Management-System
This project optimizes delivery routes, ensuring timely and cost-effective package handling. The system will leverage three key algorithms:

Rabin-Karp Algorithm: The Rabin-Karp algorithm in our code is a string-searching algorithm that uses hashing to find a pattern within a text. In this code, the Rabin-Karp algorithm is used to compare the hashed version of the entered password with the hashed version stored in the user or delivery person account file accordingly. If the hash values match, it further checks the actual characters to confirm the match.

Dijkstra's Algorithm: This algorithm finds the shortest path between a source (origin) and all destinations (customer addresses), ensuring the most efficient delivery routes for couriers.

0-1 Knapsack Problem: This algorithm optimizes the selection of packages for a courier to carry, considering weight constraints. It ensures couriers can maximize deliveries while adhering to capacity limitations.

# Problem Statement

The challenge is to design an algorithm-based system for a courier delivery system. This system optimizes delivery routes to minimize travel time and distance for couriers, while ensuring efficient package allocation considering capacity constraints. The challenge lies in designing a system that addresses the following key aspects of courier delivery:

Route Optimization: Identifying the most efficient delivery routes that minimize travel time and distance for couriers.

Cost Efficiency: Ensuring cost-effectiveness by optimizing delivery routes and courier capacity utilization.

# Flowchart
![fc](https://github.com/user-attachments/assets/74095cbe-a627-42a9-84e5-c231d95a54fd)

# Limitations
1. The adjacency matrix for Dijkstra’s algorithm is hard-coded.
2. The system assumes one delivery route for simplicity, which may not be efficient in real-world scenarios with multiple orders.
3. The 0-1 Knapsack algorithm assumes fixed capacity, which might not be flexible enough for varying package sizes and weights.
4. The authentication mechanism relies solely on comparing hashed passwords using the Rabin-Karp algorithm. So for larger values it might be as issue. 
5. The command-line interface provided by the code is basic and may not offer a user-friendly experience. 
6. The code lacks comprehensive input validation and robust error handling mechanisms. Means it doesn't handle cases where file I/O operations failure can occur. Input validation needs to be performed to ensure that inputs are within expected ranges and formats.
7. The code uses Windows-specific functions like SetConsoleTextAttribute and system("cls"), making it less portable across different operating systems.


