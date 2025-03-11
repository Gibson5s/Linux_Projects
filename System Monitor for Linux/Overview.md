## Overview of the Linux System Monitor Project

### This Project is a Bash script designed to track system resource usage in real time. It monitors CPU usage, memory consumption, and disk space utilization and generates alerts if usage exceeds predefined thresholds. This script helps users maintain system health by identifying potential performance bottlenecks.

## How It Works
### Threshold Setup: Users define CPU, memory, and disk usage limits (default is 80%).
### Monitoring Functions: The script retrieves resource usage using Linux system commands:
   - CPU Usage: Extracted from the top command.
   - Memory Usage: Derived from the free command.
   - Disk Usage: Checked using the df command.
   - Alert Mechanism: If resource consumption exceeds the threshold, the script displays a warning message.

### Credit
- LabEx.io
