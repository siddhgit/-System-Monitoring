#  System Monitoring Dashboard (CLI-Based)

A system monitoring dashboard built entirely through the Linux CLI on an AWS Ubuntu EC2 instance. It uses Bash to collect system stats and generates an auto-refreshing HTML report viewable via a simple web server.

---



- ✅ Collects system stats (uptime, CPU, RAM, disk, users)
- ✅ Outputs to an HTML file
- ✅ Runs automatically every 5 minutes via cron
- ✅ Viewable in your browser using Python's HTTP server
- ✅ No GUI tools required — 100% CLI-based

---


- Ubuntu (EC2)
- Bash

---

 Step-by-Step Setup Instructions
mkdir ~/sys-monitor
cd ~/sys-monitor


Create the Bash Script
nano monitor.sh


Then make it executable
chmod +x monitor.sh


Run the Script


Edit security group for the instance


finally run it on your browser
