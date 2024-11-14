

## Description
Jenkins uses a **Master-Slave architecture** to distribute builds across multiple machines. The **Master** coordinates job scheduling and manages build requests, while **Slaves** execute specific jobs as instructed.

## Configuration
1. Go to **Manage Jenkins > Manage Nodes and Clouds**.
2. Create a new **Node** and configure it as a **Permanent Agent**.
3. Set **Remote FS Root** to specify the root directory for the Slave.
4. Adjust the number of executors to control how many jobs can run in parallel.

## Use Cases
- **Load Distribution**: Run jobs on multiple machines to balance the workload.
- **Environment-Specific Builds**: Run builds on environments with specific configurations (e.g., OS type or software installed).

## Related Topics
- [[Jenkins Overview]]
- [[Build Jobs]]
- [[Jenkins Plugins]]
