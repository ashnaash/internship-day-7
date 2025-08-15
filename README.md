# Task 7: Monitor System Resources Using Netdata

## Objective
Install Netdata and visualize system and application performance metrics in real-time.

## Tools Used
- **Netdata** (Free, open-source monitoring tool)
- **Docker**

## Deliverables
- Screenshot of the Netdata dashboard showing running metrics.

## Steps to Run

1. **Install Docker**
   - Ensure Docker is installed and running on your system.
   - [Docker Installation Guide](https://docs.docker.com/get-docker/)

2. **Run Netdata Container**
   ```bash
   docker run -d --name=netdata -p 19999:19999 netdata/netdata
