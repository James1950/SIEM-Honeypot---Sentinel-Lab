<h1>SIEM-Honeypot---Sentinel-Lab</h1>
<h2>Description</h2>
<b>I created a hacker map with analytics using Microsoft Sentinel and other resources. I set up Azure Sentinel, which is a cloud-based SIEM as well as Virtual Machine in the cloud. The VM is the honeypot, and I made it vulnerable to the Internet. We can monitor and log attacks from different IP addresses and different countries. We are then able to collect the data and display it on a map and bar graph so you can see where all the attacks are coming from.
</b>
<br />
<br />
The script is used in this demo where I set up Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot.
We will observe live attacks (RDP Brute Force) from all around the world. I will use a custom PowerShell script to
Look up the attackers' Geolocation information and plot it on an Azure Sentinel Map!
<br />
<br />
<img width="960" alt="ipaddress geo" src="https://github.com/James1950/SIEM-Honeypot---Sentinel-Lab/assets/112421154/2cec211b-3124-4c91-9510-7e89259e97ee">


<h2>Languages Used</h2>

- <b>PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewer 

<h2>Utilities Used</h2>

- <b>ipgeolocation.io:</b> IP Address to Geolocation API

<h2>Attacks from Russian Federation coming in; Custom logs being output with geodata</h2>
<img width="954" alt="russia" src="https://github.com/James1950/SIEM-Honeypot---Sentinel-Lab/assets/112421154/8477e9dc-cd76-426a-8a80-72d7ed6a01b0">

<h2>World map of incoming attacks after a couple hours (built custom logs including geodata)</h2>
<img width="556" alt="map" src="https://github.com/James1950/SIEM-Honeypot---Sentinel-Lab/assets/112421154/baa3ad1f-c365-47d3-a91a-f51febf78f8c">

<h2>Bar graph comparing origins</h2>
<img width="788" alt="chart" src="https://github.com/James1950/SIEM-Honeypot---Sentinel-Lab/assets/112421154/fd48fd7a-efd8-49c6-b5a9-c186114ae7df">
