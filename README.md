# Task 7: Monitor System Resources Using Netdata

## Objective
Install Netdata and visualize system and app performance metrics in real-time.

## Steps Followed
- Ran Netdata using Docker:
  ```bash
  docker run -d --name=netdata -p 19999:19999 netdata/netdata

Accessed the Netdata dashboard at http://localhost:19999

Monitored CPU, Memory, Disk, and Docker container stats

Explored alerts, charts, and logs located at /var/log/netdata





