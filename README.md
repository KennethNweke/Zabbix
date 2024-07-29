# Zabbix Network Monitoring Project
Zabbix Network Monitoring Project

## Objective
This project involved setting up a comprehensive network monitoring system using VMWare Workstation Player. The network, assigned the IP range 192.168.244.0/24, included multiple virtual machines running different operating systems, all monitored by a dedicated network monitoring tool.

- To monitor network traffic across the virtual network.
- To track the system uptime of each virtual machine.
- To measure CPU utilization for each guest OS.

## Setup and Configuration
- IP Range: 192.168.244.0/24
- Windows 10 - Guest OS
- Linux Ubuntu - Guest OS
- Zabbix Appliance - Network Monitor
<a href="https://github.com/user-attachments/assets/5b73ad30-ae1c-46b3-afe6-0b9cf2e9a7cf" target="_blank">
  <img src="https://github.com/user-attachments/assets/5b73ad30-ae1c-46b3-afe6-0b9cf2e9a7cf" alt="image" width="400" />
</a>

## Tools and Technologies
- VMWare Workstation Player: Virtualization software used to create and manage the virtual machines.
- Zabbix Appliance: Deployed as the primary network monitoring tool to gather and display data on network traffic, system uptime, and CPU utilization.


## Implementation Details
Virtual Machine Setup:
- Configured Windows 10 and Linux Ubuntu as guest operating systems within the VMWare Workstation Player.
- Installed necessary software and tools on both guest OSes to facilitate monitoring and data collection.

Zabbix Appliance Configuration:
- Deployed the Zabbix Appliance within the same IP range.
- Configured Zabbix to monitor and log network traffic, system uptime, and CPU utilization from both Windows 10 and Linux Ubuntu guest OSes.
- Set up necessary agents on each guest OS to communicate with the Zabbix server.


Monitoring and Data Collection:
- Network Traffic: Monitored using Zabbix's built-in capabilities to track incoming and outgoing data packets.
- System Uptime: Logged to ensure the virtual machines maintained high availability and stability.
- CPU Utilization: Tracked to analyze the performance and resource usage of each guest OS.


## Results
- Successfully monitored network traffic within the 192.168.244.0/24 IP range.
- System uptime and CPU utilization data collected and visualized using Zabbix, providing valuable insights into the performance and reliability of each virtual machine.

## Conclusion
This project demonstrated the effective use of VMWare Workstation Player and Zabbix Appliance to create a robust network monitoring setup. The system provided comprehensive data on network traffic, system uptime, and CPU utilization, aiding in the maintenance and optimization of virtual environments.


## Skills Demonstrated
- Virtualization with VMWare Workstation Player
- Network monitoring and management
- Configuration and deployment of Zabbix Appliance
- Data analysis and visualization



## Watch the video on youtube | [View on LinkedIn](https://www.linkedin.com/posts/kenneth-nweke-4a9456185_unlock-the-power-of-monitoring-with-zabbix-activity-7222518512160772097-0cDa?utm_source=share&utm_medium=member_desktop)
[![Link to YouTube Video](https://img.youtube.com/vi/g3N7bcDuzYU/0.jpg)](https://www.youtube.com/watch?v=g3N7bcDuzYU)


## Resources
Full Resource Files
  - VMWare Workstation Player - Hypervisor
  - Windows 10 - Guest OS
  - Linux Ubuntu - Guest OS
  - Zabbix - Network Monitor
