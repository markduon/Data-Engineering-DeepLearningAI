## Notes for week 2
1\. If we were to arrange various aspects of data storage as a hierarchy, what should be the correct order of this hierarchy from the bottom to the top?
+ Bottom layer: Raw storage ingredients
+ Middle layer: Storage systems
+ Top layer: Storage abstractions

Explanation: The bottom layer of the hierarchy consists of the raw storage ingredients since all storage solutions are built on top of the physical ingredients like SSD and magnetic disks, along with processes like networking, serialization, and compression. The middle layer consists of storage systems like databases and object storage that are built on top of the raw ingredients. Then the top layer consists of the these storage systems arranged into storage abstractions like data warehouses, data lakes, and data lakehouses.

2\. Availability, often referred to as uptime, is the percentage of time a service is expected to be in an operable state.

3\. What does the term "durability" refer to in the context of data systems?
+ Durability refers to the ability of a storage system to withstand data loss.

4\. RTO is the maximum acceptable time for a service outage, while RPO defines the acceptable state after recovery.

5\. Zero trust requires authentication for every action, while hardened perimeter security relies on a physical barrier.

6\. Batch Processing:
- Processes data in fixed time periods (e.g., daily batches)
- Traditional approach to data processing
- Optimal for non-real-time analysis needs

7\. Data Marts: These are subsets of data warehouses focused on specific business areas, making data more accessible for analytics and reporting.

8\. Streaming processing: handles data continuously in near real-time.

9\. Monolithic v.s. modular:
- Monolithic architecture is like a big, single building where everything is connected tightly together. Imagine a large library where all the books, computers, and study areas are in one room. This makes it easy to find everything in one place, but if you want to change something, like adding a new section, it can be very complicated and might require a lot of work. For example, if a part of the library needs repairs, the whole library might have to close down, which can be frustrating for everyone.
- On the other hand, modular architecture is like a collection of small, separate buildings that are connected by pathways. Each building serves a different purpose, like a reading room, a computer lab, or a café. If you want to make changes, like renovating the café, you can do that without affecting the other buildings. This flexibility allows for easier updates and improvements over time, making it a more efficient way to manage resources.