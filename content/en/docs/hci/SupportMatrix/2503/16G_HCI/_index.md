---
title: "Azure Local Support Matrix for 16G (2503)"
linkTitle: "16G"
weight: 7497
Description: >

---

{{< rawhtml >}}

<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>

    <style>
    table {
        border-width:1px;border-style:solid;
        border-color:black;
        border-collapse: collapse;
        width: 100%;
        margin-bottom: 20px;
        table-layout:fixed;
        overflow-wrap: break-word;
    }
    th {
        border-width:1px;
        padding:7px;
        border-style:solid;
        border-color:#0076CE;
        background-color:#0076CE;
        color:#FFFFFF;
        text-align:center;
    }
    td {
        border-width:1px;
        padding:7px;
        border-style:solid;
        border-color:#0076CE;
        text-align:center;
    }
    caption {
        padding-bottom: 10px;
        color:  #0076CE;
        font-weight: bold;
        text-align: left;
        font-size: 20px;
    }
    </style>

</head>

<body>

    <div id="content">
{{< /rawhtml >}}

### Supported Platforms
{{< rawhtml >}}
<table>
<colgroup><col/><col/></colgroup>
<tr><th>Model</th><th>Supported Operating System</th></tr>
<tr><td>AX-760</td><td>Windows Server 2022 Datacenter<br>Windows Server 2025 Datacenter<br>Azure Stack HCI-22H2<br>Azure Stack HCI-23H2</td></tr>
<tr><td>AX-660</td><td>Windows Server 2025 Datacenter<br>Azure Stack HCI-23H2</td></tr>
</table>
<br>
{{< /rawhtml >}}

### Base Components
{{< rawhtml >}}
<table>
<colgroup><col/><col/><col/><col/><col/><col/></colgroup>
<tr><th>Component</th><th>Type</th><th>Software Bundle</th><th>Minimum Supported Version</th><th>Supported Platforms</th><th>Supported OS</th></tr>
<tr><td>BIOS</td><td>Firmware DUP</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=K77XK">K77XK</a></td><td>2.5.4</td><td>AX-660<br><br>AX-760</td><td>NA</td></tr>
<tr><td>Chipset driver for 16G Intel platforms</td><td>Driver DUP</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=P7PJM">P7PJM</a></td><td>10.1.19928.8615</td><td>AX-660<br><br>AX-760</td><td>Windows Server 2022 Datacenter<br><br>Windows Server 2025 Datacenter<br><br>Azure Stack HCI-22H2<br><br>Azure Stack HCI-23H2</td></tr>
<tr><td>iDRAC9 with Lifecycle Controller</td><td>Firmware DUP</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=5MXXN">5MXXN</a></td><td>7.20.10.50</td><td>AX-660<br><br>AX-760</td><td>NA</td></tr>
<tr><td>Expander Storage Backplane</td><td>Firmware DUP</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=J9JW2">J9JW2</a></td><td>1.61</td><td>AX-760</td><td>NA</td></tr>
<tr><td>NVMe Switch Storage Backplane</td><td>Firmware DUP</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=WR74F">WR74F</a></td><td>3.32</td><td>AX-760</td><td>NA</td></tr>
<tr><td>Non-expander Storage Backplane</td><td>Firmware DUP</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=GXH37">GXH37</a></td><td>7.1</td><td>AX-760</td><td>NA</td></tr>
<tr><td>Non-expander Storage Backplane</td><td>Firmware DUP</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=6Y9X7">6Y9X7</a></td><td>7.1</td><td>AX-660</td><td>NA</td></tr>
<tr><td>iDRAC Service Module</td><td>Firmware DUP</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=258RC">258RC</a></td><td>5.4.0.0</td><td>AX-660<br><br>AX-760</td><td>NA</td></tr>
<tr><td>CPLD</td><td>Firmware DUP</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=503F0">503F0</a></td><td>1.2.6</td><td>AX-660<br><br>AX-760</td><td>NA</td></tr>
</table>
<br>
{{< /rawhtml >}}

### Network Adapters
{{< rawhtml >}}
<table>
<colgroup><col/><col/><col/><col/><col/><col/><col/><col/></colgroup>
<tr><th>Component</th><th>Part Number</th><th>SDDC AQ for Windows Server 2022</th><th>RDMA Protocol</th><th>Firmware Software Bundle</th><th>Firmware Minimum Supported Version</th><th>Driver Software Bundle</th><th>Driver Minimum Supported Version</th><th>Supported OS</th><th>Supported Platforms</th></tr>
<tr><td>Broadcom 5720 Dual Port 1 GbE Network LOM Mezz Card</td><td>5NN70</td><td rowspan="1">Management</td><td rowspan="1">N/A</td><td rowspan="1"><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=MGPTR">MGPTR</a></td><td rowspan="1">23.11.4</td><td rowspan="1"><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=KDMJJ">KDMJJ</a></td><td rowspan="1">221.0.7.0d</td><td rowspan="1">Windows Server 2022 Datacenter<br><br>Windows Server 2025 Datacenter<br><br>Azure Stack HCI-22H2<br><br>Azure Stack HCI-23H2</td><td rowspan="1">AX-660<br><br>AX-760</td></tr>
<tr><td>Intel E810-XXV Dual Port 25GbE SFP28 Adapter, PCIe LP</td><td>6J1N1</td><td rowspan="7">Management<br><br>Compute (Premium)<br><br>Storage (Premium)</td><td rowspan="7">iWARP,RoCEv2</td><td rowspan="7"><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=89VV2">89VV2</a></td><td rowspan="7">23.0.8</td><td rowspan="7"><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=6JHVK">6JHVK</a></td><td rowspan="7">1.15.121.0</td><td rowspan="7">Windows Server 2022 Datacenter<br><br>Azure Stack HCI-22H2<br><br>Azure Stack HCI-23H2</td><td rowspan="7">AX-660<br><br>AX-760</td></tr>
<tr><td>Intel E810-CQDA2 Dual Port 100GbE QSFP28 Adapter, PCIe FH</td><td>85F8F</td>
<tr><td>Intel E810-XXV Dual Port 25GbE SFP28 Adapter, PCIe FH</td><td>CD16M</td>
<tr><td>Intel E810-CQDA2 Dual Port 100GbE QSFP28 Adapter, PCIe LP</td><td>DWNRF</td>
<tr><td>Intel E810-XXVDA2 Dual Port 1/10/25GbE SFP28 Adapter</td><td>PWH3C</td>
<tr><td>Intel E810-XXVDA4 Quad Port 1/10/25GbE SFP28 Adapter, PCIe FH</td><td>VK88G</td>
<tr><td>Intel E810-XXVDA4 Quad Port 1/10/25GbE SFP28 Adapter</td><td>Y4VV5</td>
<tr><td>Intel E810-XXV Dual Port 25GbE SFP28 Adapter, PCIe LP</td><td>6J1N1</td><td rowspan="7">Management<br><br>Compute (Premium)<br><br>Storage (Premium)</td><td rowspan="7">iWARP,RoCEv2</td><td rowspan="7"><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=89VV2">89VV2</a></td><td rowspan="7">23.0.8</td><td rowspan="7"><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=R71XY">R71XY</a></td><td rowspan="7">1.15.302.0</td><td rowspan="7">Windows Server 2025 Datacenter</td><td rowspan="7">AX-660<br><br>AX-760</td></tr>
<tr><td>Intel E810-CQDA2 Dual Port 100GbE QSFP28 Adapter, PCIe FH</td><td>85F8F</td>
<tr><td>Intel E810-XXV Dual Port 25GbE SFP28 Adapter, PCIe FH</td><td>CD16M</td>
<tr><td>Intel E810-CQDA2 Dual Port 100GbE QSFP28 Adapter, PCIe LP</td><td>DWNRF</td>
<tr><td>Intel E810-XXVDA2 Dual Port 1/10/25GbE SFP28 Adapter</td><td>PWH3C</td>
<tr><td>Intel E810-XXVDA4 Quad Port 1/10/25GbE SFP28 Adapter, PCIe FH</td><td>VK88G</td>
<tr><td>Intel E810-XXVDA4 Quad Port 1/10/25GbE SFP28 Adapter</td><td>Y4VV5</td>
<tr><td>Mellanox ConnectX-6 Dx Dual Port 100GbE QSFP56 PCIe Adapter, FH</td><td>8P2T2</td><td rowspan="2">Management<br><br>Compute (Premium)<br><br>Storage (Premium)</td><td rowspan="2">RoCEv2</td><td rowspan="2"><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=2CMVW">2CMVW</a></td><td rowspan="2">22.41.10.00</td><td rowspan="2"><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=G6M58">G6M58</a></td><td rowspan="2">24.4.26429</td><td rowspan="2">Windows Server 2022 Datacenter<br><br>Windows Server 2025 Datacenter<br><br>Azure Stack HCI-22H2<br><br>Azure Stack HCI-23H2</td><td rowspan="2">AX-660<br><br>AX-760</td></tr>
<tr><td>Mellanox ConnectX-6 Dx Dual Port 100GbE QSFP56 PCIe Adapter, LP</td><td>F6FXM</td>
<tr><td>Nvidia ConnectX-6 Lx Dual Port 10/25GbE SFP28 Adapter, PCIe LP</td><td>6XJXK</td><td rowspan="2">Management<br><br>Compute (Premium)<br><br>Storage (Premium)</td><td rowspan="2">RoCEv2</td><td rowspan="2"><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=1H4PM">1H4PM</a></td><td rowspan="2">26.41.10.00</td><td rowspan="2"><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=G6M58">G6M58</a></td><td rowspan="2">24.4.26429</td><td rowspan="2">Windows Server 2022 Datacenter<br><br>Windows Server 2025 Datacenter<br><br>Azure Stack HCI-22H2<br><br>Azure Stack HCI-23H2</td><td rowspan="2">AX-660<br><br>AX-760</td></tr>
<tr><td>Nvidia ConnectX-6 Lx Dual Port 10/25GbE SFP28 Adapter</td><td>DN78C</td>
<tr><td>Nvidia ConnectX-6 Lx Dual Port 10/25GbE SFP28 Adapter, PCIe FH</td><td>R5WK9</td><td rowspan="1">Management<br><br>Compute (Premium)<br><br>Storage (Premium)</td><td rowspan="1">RoCEv2</td><td rowspan="1"><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=1H4PM">1H4PM</a></td><td rowspan="1">26.41.10.00</td><td rowspan="1"><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=G6M58">G6M58</a></td><td rowspan="1">24.4.26429</td><td rowspan="1">Windows Server 2022 Datacenter<br><br>Windows Server 2025 Datacenter<br><br>Azure Stack HCI-22H2<br><br>Azure Stack HCI-23H2</td><td rowspan="1">AX-760</td></tr>
</table>
<br>
{{< /rawhtml >}}

### Network Switches
{{< rawhtml >}}
<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Component</th><th>Category</th><th>Minimum Supported Version</th></tr>
<tr><td>Dell EMC Networking S4112F-ON</td><td>Network Switch</td><td>10.6.0.1.35</td></tr>
<tr><td>Dell EMC Networking S4128F-ON</td><td>Network Switch</td><td>10.6.0.1.35</td></tr>
<tr><td>Dell EMC Networking S4148F-ON</td><td>Network Switch</td><td>10.6.0.1.35</td></tr>
<tr><td>Dell EMC Networking S5212F-ON</td><td>Network Switch</td><td>10.6.0.1.35</td></tr>
<tr><td>Dell EMC Networking S5224F/S5248F-ON</td><td>Network Switch</td><td>10.6.0.1.35</td></tr>
<tr><td>Dell EMC Networking S5232F-ON</td><td>Network Switch</td><td>10.6.0.1.35</td></tr>
<tr><td>Dell EMC Networking S5448F-ON</td><td>Network Switch</td><td>10.6.0.1.35</td></tr>
</table>
<br>
{{< /rawhtml >}}

### GPUs
{{< rawhtml >}}
<table>
<colgroup><col/><col/><col/><col/><col/><col/><col/><col/><col/></colgroup>
<tr><th>GPU Model</th><th>Vendor</th><th>Description</th><th>Part Number</th><th>Firmware version</th><th>Driver Version</th><th>GPU-P capable</th><th>Supported Platform</th><th>Supported OS</th></tr>
<tr><td>A16</td><td>NVIDIA</td><td>NVIDIA Ampere A16, PCIe, 250W, 64GB Passive, Double Wide, Full Height GPU,V2</td><td>D1P1T</td><td>94.07.54.00.45</td><td>553.62</td><td>Yes</td><td>AX-760</td><td>Azure Stack HCI-22H2<br>Azure Stack HCI-23H2</td></tr>
<tr><td>A2</td><td>NVIDIA</td><td>NVIDIA Ampere A2, PCIe, 60W, 16GB Passive, Single Wide, Low Profile GPU, V2</td><td>H98K0</td><td>94.07.5B.00.55</td><td>553.62</td><td>Yes</td><td>AX-660<br>AX-760</td><td>Azure Stack HCI-22H2<br>Azure Stack HCI-23H2</td></tr>
<tr><td>A2</td><td>NVIDIA</td><td>NVIDIA Ampere A2, PCIe, 60W, 16GB Passive, Single Wide, Full Height GPU, V2</td><td>MG5JX</td><td>94.07.5B.00.55</td><td>553.62</td><td>Yes</td><td>AX-660<br>AX-760</td><td>Azure Stack HCI-22H2<br>Azure Stack HCI-23H2</td></tr>
<tr><td>L4</td><td>NVIDIA</td><td>NVIDIA L4, PCIe, 72W, 24GB Passive, Single Wide Full Height GPU</td><td>NG3PY</td><td>95.04.29.00.06</td><td>553.62</td><td>Yes</td><td>AX-660<br>AX-760</td><td>Azure Stack HCI-22H2<br>Azure Stack HCI-23H2</td></tr>
<tr><td>L4</td><td>NVIDIA</td><td>NVIDIA L4, PCIe, 72W, 24GB Passive, Single Wide Low Profile GPU</td><td>V9XT2</td><td>95.04.29.00.06</td><td>553.62</td><td>Yes</td><td>AX-660<br>AX-760</td><td>Azure Stack HCI-22H2<br>Azure Stack HCI-23H2</td></tr>
<tr><td>L40</td><td>NVIDIA</td><td>NVIDIA Ampere L40, PCIe, 300W, 48GB Passive, Double Wide, Full Height, Full Length, GPU with cable</td><td>VHNWT</td><td>95.02.39.00.01</td><td>553.62</td><td>Yes</td><td>AX-760</td><td>Azure Stack HCI-22H2<br>Azure Stack HCI-23H2</td></tr>
<tr><td>L40S</td><td>NVIDIA</td><td>NVIDIA Ampere L40S, PCIe, 350W, 48GB Passive, Double Wide, Full Height, Full Length, GPU with cable</td><td>7WK28</td><td>95.02.66.00.02</td><td>553.62</td><td>Yes</td><td>AX-760</td><td>Azure Stack HCI-22H2<br>Azure Stack HCI-23H2</td></tr>
</table>

{{< /rawhtml >}}
{{% alert title="NOTE" color="primary" %}}
Dell update packages are not available for GPU cards, please download the latest driver version from NVIDIA driver download page.
{{% /alert %}}
### Storage Controllers
{{< rawhtml >}}
<table>
<colgroup><col/><col/><col/><col/><col/><col/><col/><col/></colgroup>
<tr><th>Component</th><th>Dell Part Number</th><th>Firmware Software Bundle</th><th>Firmware Minimum Supported Version</th><th>Driver Software Bundle</th><th>Driver Minimum Supported Version</th><th>Supported Platforms</th><th>Supported OS</th></tr>
<tr><td>BOSS-N1</td><td>WW56V</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=33TD2">33TD2</a></td><td>2.1.13.2033</td><td>Inbox</td><td>Inbox</td><td>AX-660<br><br>AX-760</td><td>Windows Server 2022 Datacenter<br><br>Windows Server 2025 Datacenter<br><br>Azure Stack HCI-22H2<br><br>Azure Stack HCI-23H2</td></tr>
<tr><td>HBA355i</td><td>K6MCJ</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=Y99R5">Y99R5</a></td><td>24.15.14.00</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=M2P63">M2P63</a></td><td>2.61.48.00</td><td>AX-660<br><br>AX-760</td><td>Windows Server 2022 Datacenter<br><br>Windows Server 2025 Datacenter<br><br>Azure Stack HCI-22H2<br><br>Azure Stack HCI-23H2</td></tr>
</table>
<br>
{{< /rawhtml >}}


### SATA M.2 SSD Boot Only
{{< rawhtml >}}
<table>
<colgroup><col/><col/><col/><col/><col/><col/><col/><col/><col/><col/><col/><col/></colgroup>
<tr><th>Type</th><th>Drive Type</th><th>Form Factor</th><th>Endurance</th><th>Vendor</th><th>Series</th><th>Model</th><th>Device Part Number (P/N)</th><th>Firmware Software Bundle</th><th>Firmware Minimum Supported Version</th><th>Capacity</th><th>Use</th></tr>
<tr><td>NVMe</td><td>PCIe</td><td>M.2</td><td>Read Intensive</td><td>Micron</td><td>7400</td><td>MTFDKBA960TDZ</td><td>PRV6C</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=N71F4">N71F4</a></td><td>1.6.0</td><td>960GB</td><td>Boot</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>M.2</td><td>Read Intensive</td><td>Micron</td><td>7400</td><td>MTFDKBG960TDZ</td><td>0V8F7</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=N71F4">N71F4</a></td><td>1.6.0</td><td>960GB</td><td>Boot</td></tr>
</table>
<br>
{{< /rawhtml >}}

### SAS 3.5" HDD Capacity Only
{{< rawhtml >}}
<table>
<colgroup><col/><col/><col/><col/><col/><col/><col/><col/><col/><col/><col/><col/></colgroup>
<tr><th>Type</th><th>Drive Type</th><th>Form Factor</th><th>Endurance</th><th>Vendor</th><th>Series</th><th>Model</th><th>Device Part Number (P/N)</th><th>Firmware Software Bundle</th><th>Firmware Minimum Supported Version</th><th>Capacity</th><th>Use</th></tr>
<tr><td>HDD</td><td>SAS</td><td>3.5</td><td>NA</td><td>HGST</td><td>Vela-A</td><td>HUS726T4TALS200</td><td>NT1X2</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=J5K8G">J5K8G</a></td><td>PU09</td><td>4 TB</td><td>Capacity</td></tr>
<tr><td>HDD</td><td>SAS</td><td>3.5</td><td>NA</td><td>Toshiba</td><td>MG10</td><td>MG10SDA400NY</td><td>9VN79</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=99TKP">99TKP</a></td><td>EP02</td><td>4 TB</td><td>Capacity</td></tr>
<tr><td>HDD</td><td>SAS</td><td>3.5</td><td>NA</td><td>HGST</td><td>Vela-AP</td><td>HUS728T8TAL5200</td><td>44YFV</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=8GM6M">8GM6M</a></td><td>RS09</td><td>8 TB</td><td>Capacity</td></tr>
<tr><td>HDD</td><td>SAS</td><td>3.5</td><td>NA</td><td>Toshiba</td><td>MG06</td><td>MG06SCA800EY</td><td>FV725</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=4G5GY">4G5GY</a></td><td>EH0D</td><td>8 TB</td><td>Capacity</td></tr>
<tr><td>HDD</td><td>SAS</td><td>3.5</td><td>NA</td><td>HGST</td><td>Leo-A He12</td><td>HUH721212AL5200</td><td>9HXK6</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=04PM5">04PM5</a></td><td>NS11</td><td>12 TB</td><td>Capacity</td></tr>
<tr><td>HDD</td><td>SAS</td><td>3.5</td><td>NA</td><td>WD</td><td>Paris-C</td><td>WUH721816AL5200</td><td>VF206</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=441CN">441CN</a></td><td>US07</td><td>16 TB</td><td>Capacity</td></tr>
<tr><td>HDD</td><td>SAS</td><td>3.5</td><td>NA</td><td>Seagate</td><td>Cimarron BP</td><td>ST4000NM019B</td><td>10N7R</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=3P5N0">3P5N0</a></td><td>LW0B</td><td>4 TB</td><td>Capacity</td></tr>
<tr><td>HDD</td><td>SAS</td><td>3.5</td><td>NA</td><td>Seagate</td><td>Cimarron BP</td><td>ST8000NM024B</td><td>C5HD0</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=NM6GP">NM6GP</a></td><td>LS0C</td><td>8 TB</td><td>Capacity</td></tr>
<tr><td>HDD</td><td>SAS</td><td>3.5</td><td>NA</td><td>Toshiba</td><td>MG08SD</td><td>MG08SDA400NY</td><td>FN2YX</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=GTG81">GTG81</a></td><td>EK06</td><td>4 TB</td><td>Capacity</td></tr>
<tr><td>HDD</td><td>SAS</td><td>3.5</td><td>NA</td><td>Seagate</td><td>Evans BP</td><td>ST12000NM006J</td><td>M1C0T</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=92VPG">92VPG</a></td><td>PSLB</td><td>12 TB</td><td>Capacity</td></tr>
<tr><td>HDD</td><td>SAS</td><td>3.5</td><td>NA</td><td>Seagate</td><td>Evans BP</td><td>ST16000NM006J</td><td>41DXR</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=92VPG">92VPG</a></td><td>PSLB</td><td>16 TB</td><td>Capacity</td></tr>
<tr><td>HDD</td><td>SAS</td><td>3.5</td><td>NA</td><td>Toshiba&#160;</td><td>MG08SD</td><td>MG08SDA800EY</td><td>NJWMG</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=1RCYJ">1RCYJ</a></td><td>EL01</td><td>8 TB</td><td>Capacity</td></tr>
<tr><td>HDD</td><td>SAS</td><td>3.5</td><td>Read Intensive</td><td>Seagate</td><td>LongsPeak</td><td>ST20000NM004D</td><td>R3G03</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=56HWT">56HWT</a></td><td>GS07</td><td>20 TB</td><td>Capacity</td></tr>
<tr><td>HDD</td><td>SAS</td><td>3.5</td><td>NA</td><td>Toshiba&#160;</td><td>MG10SD</td><td>MG10SDA800EY</td><td>VJDMM</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=99TKP">99TKP</a></td><td>EP02</td><td>8 TB</td><td>Capacity</td></tr>
<tr><td>HDD</td><td>SAS</td><td>3.5</td><td>NA</td><td>Seagate</td><td>CimarronBP(EWP)</td><td>DL4000NM019B</td><td>F7DTR</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=M7PKX">M7PKX</a></td><td>LBW4</td><td>4 TB</td><td>Capacity</td></tr>
<tr><td>HDD</td><td>SAS</td><td>3.5</td><td>NA</td><td>Toshiba</td><td>MG09</td><td>MG09SCA12TEY</td><td>0N96X</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=8829H">8829H</a></td><td>EM05</td><td>12 TB</td><td>Capacity</td></tr>
<tr><td>HDD</td><td>SAS</td><td>3.5</td><td>NA</td><td>Seagate</td><td>Summit</td><td>ST12000NM007H</td><td>FN7VR</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=W6DKH">W6DKH</a></td><td>SWS8</td><td>12 TB</td><td>Capacity</td></tr>
<tr><td>HDD</td><td>SAS</td><td>3.5</td><td>NA</td><td>Toshiba</td><td>MG09</td><td>MG09SCA16TEY</td><td>MXC46</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=8829H">8829H</a></td><td>EM05</td><td>16 TB</td><td>Capacity</td></tr>
<tr><td>HDD</td><td>SAS</td><td>3.5</td><td>NA</td><td>Seagate</td><td>Summit</td><td>ST16000NM007H</td><td>R0G8W</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=MGW24">MGW24</a></td><td>SYS8</td><td>16 TB</td><td>Capacity</td></tr>
<tr><td>HDD</td><td>SAS</td><td>3.5</td><td>NA</td><td>Toshiba</td><td>MG10</td><td>MG10SCA20TEY</td><td>NT45N</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=0H3CX">0H3CX</a></td><td>EN04</td><td>20 TB</td><td>Capacity</td></tr>
<tr><td>HDD</td><td>SAS</td><td>3.5</td><td>NA</td><td>WD</td><td>Paris-D PR2</td><td>WUH722020BL5200</td><td>1D4CR</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=YH8C3">YH8C3</a></td><td>VS18</td><td>20 TB</td><td>Capacity</td></tr>
<tr><td>HDD</td><td>SAS</td><td>3.5</td><td>NA</td><td>Seagate</td><td>Summit</td><td>ST20000NM007H</td><td>R5KP7</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=MGW24">MGW24</a></td><td>SYS8</td><td>20 TB</td><td>Capacity</td></tr>
<tr><td>HDD</td><td>SAS</td><td>3.5</td><td>NA</td><td>WD</td><td>London DP</td><td>WUH722420AL5200</td><td>MTTCF</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=FN2N1">FN2N1</a></td><td>YS01</td><td>20 TB</td><td>Capacity</td></tr>
</table>
<br>
{{< /rawhtml >}}

### SATA 2.5" SSD Capacity Only
{{< rawhtml >}}
<table>
<colgroup><col/><col/><col/><col/><col/><col/><col/><col/><col/><col/><col/><col/></colgroup>
<tr><th>Type</th><th>Drive Type</th><th>Form Factor</th><th>Endurance</th><th>Vendor</th><th>Series</th><th>Model</th><th>Device Part Number (P/N)</th><th>Firmware Software Bundle</th><th>Firmware Minimum Supported Version</th><th>Capacity</th><th>Use</th></tr>
<tr><td>SSD</td><td>SATA</td><td>2.5</td><td>Read Intensive</td><td>Intel</td><td>S4520</td><td>SSDSC2KB019TZR</td><td>6J65H</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=VJPKG">VJPKG</a></td><td>DL7C</td><td>1.92TB</td><td>Capacity</td></tr>
<tr><td>SSD</td><td>SATA</td><td>2.5</td><td>Read Intensive</td><td>SK Hynix</td><td>SE5110</td><td>HFS1T9G3H2X069N</td><td>962FP</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=7XTPF">7XTPF</a></td><td>DZ03</td><td>1.92TB</td><td>Capacity</td></tr>
<tr><td>SSD</td><td>SATA</td><td>2.5</td><td>Read Intensive</td><td>Samsung</td><td>PM883a</td><td>MZ7LH1T9HALT0D3</td><td>9F9Y6</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=107CV">107CV</a></td><td>HG60</td><td>1.92TB</td><td>Capacity</td></tr>
<tr><td>SSD</td><td>SATA</td><td>2.5</td><td>Read Intensive</td><td>Samsung</td><td>PM893</td><td>MZ7L31T9HBLTAD3</td><td>0KYP4</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=537XV">537XV</a></td><td>HJ62</td><td>1.92TB</td><td>Capacity</td></tr>
<tr><td>SSD</td><td>SATA</td><td>2.5</td><td>Read Intensive</td><td>Samsung</td><td>PM893a</td><td>MZ7L31T9HELAAD3</td><td>PTD53</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=NF72T">NF72T</a></td><td>HL56</td><td>1.92TB</td><td>Capacity</td></tr>
<tr><td>SSD</td><td>SATA</td><td>2.5</td><td>Read Intensive</td><td>Micron</td><td>5300</td><td>MTFDDAK1T9TDS</td><td>GYGVV</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=KT63Y">KT63Y</a></td><td>J008</td><td>1.92TB</td><td>Capacity</td></tr>
<tr><td>SSD</td><td>SATA</td><td>2.5</td><td>Read Intensive</td><td>Micron</td><td>5400</td><td>MTFDDAK1T9TGA-1BC1ZABDA</td><td>KXNX5</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=RJ0WY">RJ0WY</a></td><td>K003</td><td>1.92TB</td><td>Capacity</td></tr>
<tr><td>SSD</td><td>SATA</td><td>2.5</td><td>Read Intensive</td><td>Intel</td><td>S4520</td><td>SSDSC2KB038TZR</td><td>KM4C4</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=VJPKG">VJPKG</a></td><td>DL7C</td><td>3.84TB</td><td>Capacity</td></tr>
<tr><td>SSD</td><td>SATA</td><td>2.5</td><td>Read Intensive</td><td>SK Hynix</td><td>SE5110</td><td>HFS3T8G3H2X069N</td><td>3GDK0</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=7XTPF">7XTPF</a></td><td>DZ03</td><td>3.84TB</td><td>Capacity</td></tr>
<tr><td>SSD</td><td>SATA</td><td>2.5</td><td>Read Intensive</td><td>Samsung</td><td>PM883a</td><td>MZ7LH3T8HALT0D3</td><td>5TVXD</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=107CV">107CV</a></td><td>HG60</td><td>3.84TB</td><td>Capacity</td></tr>
<tr><td>SSD</td><td>SATA</td><td>2.5</td><td>Read Intensive</td><td>Samsung</td><td>PM893</td><td>MZ7L33T8HBLTAD3</td><td>GCN5W</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=537XV">537XV</a></td><td>HJ62</td><td>3.84TB</td><td>Capacity</td></tr>
<tr><td>SSD</td><td>SATA</td><td>2.5</td><td>Read Intensive</td><td>Samsung</td><td>PM893a</td><td>MZ7L33T8HELAAD3</td><td>D7V89</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=NF72T">NF72T</a></td><td>HL56</td><td>3.84TB</td><td>Capacity</td></tr>
<tr><td>SSD</td><td>SATA</td><td>2.5</td><td>Read Intensive</td><td>Micron</td><td>5300</td><td>MTFDDAK3T8TDT</td><td>4H1RX</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=R9YDC">R9YDC</a></td><td>J408</td><td>3.84TB</td><td>Capacity</td></tr>
<tr><td>SSD</td><td>SATA</td><td>2.5</td><td>Read Intensive</td><td>Micron</td><td>5400</td><td>MTFDDAK3T8TGA-1BC1ZABDA</td><td>CHF46</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=JTW3W">JTW3W</a></td><td>K403</td><td>3.84TB</td><td>Capacity</td></tr>
<tr><td>SSD</td><td>SATA</td><td>2.5</td><td>Mixed Use</td><td>Intel</td><td>S4620</td><td>SSDSC2KG019TZR</td><td>6XW3M</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=VJPKG">VJPKG</a></td><td>DL7C</td><td>1.92TB</td><td>Capacity</td></tr>
<tr><td>SSD</td><td>SATA</td><td>2.5</td><td>Mixed Use</td><td>SK Hynix</td><td>SE5130</td><td>HFS1T9G3E2X149N</td><td>HCR09</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=4T2FN">4T2FN</a></td><td>DG00</td><td>1.92TB</td><td>Capacity</td></tr>
<tr><td>SSD</td><td>SATA</td><td>2.5</td><td>Mixed Use</td><td>SK Hynix</td><td>SE5031</td><td>HFS1T9G32FEH-BA10A</td><td>GKTF1</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=2CY65">2CY65</a></td><td>DD02</td><td>1.92TB</td><td>Capacity</td></tr>
<tr><td>SSD</td><td>SATA</td><td>2.5</td><td>Mixed Use</td><td>Samsung</td><td>PM897a</td><td>MZ7L31T9HENAAD3</td><td>GR4WN</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=KHC8M">KHC8M</a></td><td>HK56</td><td>1.92TB</td><td>Capacity</td></tr>
<tr><td>SSD</td><td>SATA</td><td>2.5</td><td>Mixed Use</td><td>Samsung</td><td>PM897</td><td>MZ7L31T9HBNAAD3</td><td>RRR7M</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=Y4WVW">Y4WVW</a></td><td>HH62</td><td>1.92TB</td><td>Capacity</td></tr>
<tr><td>SSD</td><td>SATA</td><td>2.5</td><td>Mixed Use</td><td>Micron</td><td>5300</td><td>MTFDDAK1T9TDT</td><td>MMCDY</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=KT63Y">KT63Y</a></td><td>J008</td><td>1.92TB</td><td>Capacity</td></tr>
<tr><td>SSD</td><td>SATA</td><td>2.5</td><td>Mixed Use</td><td>Micron</td><td>5400</td><td>MTFDDAK1T9TGB-1BC1ZABDA</td><td>XRXX2</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=RJ0WY">RJ0WY</a></td><td>K003</td><td>1.92TB</td><td>Capacity</td></tr>
</table>
<br>
{{< /rawhtml >}}

### SAS 2.5" SSD Cache or Capacity
{{< rawhtml >}}
<table>
<colgroup><col/><col/><col/><col/><col/><col/><col/><col/><col/><col/><col/><col/></colgroup>
<tr><th>Type</th><th>Drive Type</th><th>Form Factor</th><th>Endurance</th><th>Vendor</th><th>Series</th><th>Model</th><th>Device Part Number (P/N)</th><th>Firmware Software Bundle</th><th>Firmware Minimum Supported Version</th><th>Capacity</th><th>Use</th></tr>
<tr><td>SSD</td><td>SAS</td><td>2.5</td><td>Mixed Use</td><td>Samsung</td><td>PM1655</td><td>MZILG800HCHQAD3</td><td>3CHC8</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=7MTXM">7MTXM</a></td><td>DWG9</td><td>800 GB</td><td>Cache,Capacity</td></tr>
<tr><td>SSD</td><td>SAS</td><td>2.5</td><td>Mixed Use</td><td>Samsung</td><td>PM1655</td><td>MZILG1T6HCJRAD3</td><td>5RJND</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=7MTXM">7MTXM</a></td><td>DWG9</td><td>1.6 TB</td><td>Cache,Capacity</td></tr>
<tr><td>SSD</td><td>SAS</td><td>2.5</td><td>Mixed Use</td><td>Kioxia</td><td>PM7</td><td>KPM7XVUG1T60</td><td>4TRHM</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=T21WT">T21WT</a></td><td>C10E</td><td>1.6 TB</td><td>Cache,Capacity</td></tr>
<tr><td>SSD</td><td>SAS</td><td>2.5</td><td>Mixed Use</td><td>Kioxia</td><td>PM6</td><td>KPM6XVUG800G</td><td>NNGV4</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=NGPR2">NGPR2</a></td><td>BA48</td><td>800 GB</td><td>Cache,Capacity</td></tr>
<tr><td>SSD</td><td>SAS</td><td>2.5</td><td>Mixed Use</td><td>Kioxia</td><td>PM7</td><td>KPM7XVUG800G</td><td>X96H8</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=T21WT">T21WT</a></td><td>C10E</td><td>800 GB</td><td>Cache,Capacity</td></tr>
</table>
<br>
{{< /rawhtml >}}

### SAS 2.5" SSD Capacity Only
{{< rawhtml >}}
<table>
<colgroup><col/><col/><col/><col/><col/><col/><col/><col/><col/><col/><col/><col/></colgroup>
<tr><th>Type</th><th>Drive Type</th><th>Form Factor</th><th>Endurance</th><th>Vendor</th><th>Series</th><th>Model</th><th>Device Part Number (P/N)</th><th>Firmware Software Bundle</th><th>Firmware Minimum Supported Version</th><th>Capacity</th><th>Use</th></tr>
<tr><td>SSD</td><td>SAS</td><td>2.5</td><td>Read Intensive</td><td>Samsung</td><td>PM1653</td><td>MZILG1T9HCJRAD3</td><td>NRR34</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=3MV58">3MV58</a></td><td>DSG9</td><td>1.92 TB</td><td>Capacity</td></tr>
<tr><td>SSD</td><td>SAS</td><td>2.5</td><td>Read Intensive</td><td>Samsung</td><td>PM1653</td><td>MZILG3T8HCLSAD3</td><td>9N32F</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=3MV58">3MV58</a></td><td>DSG9</td><td>3.84 TB</td><td>Capacity</td></tr>
<tr><td>SSD</td><td>SAS</td><td>2.5</td><td>Read Intensive</td><td>Samsung</td><td>PM1653</td><td>MZILG7T6HBLAAD3</td><td>Y8H7M</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=3MV58">3MV58</a></td><td>DSG9</td><td>7.68 TB</td><td>Capacity</td></tr>
<tr><td>SSD</td><td>SAS</td><td>2.5</td><td>Read Intensive</td><td>Kioxia</td><td>PM7</td><td>KPM7XRUG1T92</td><td>6K35K</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=T21WT">T21WT</a></td><td>C10E</td><td>1.92 TB</td><td>Capacity</td></tr>
<tr><td>SSD</td><td>SAS</td><td>2.5</td><td>Read Intensive</td><td>Kioxia</td><td>PM7</td><td>KPM7XRUG3T84</td><td>MT0R5</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=T21WT">T21WT</a></td><td>C10E</td><td>3.84 TB</td><td>Capacity</td></tr>
<tr><td>SSD</td><td>SAS</td><td>2.5</td><td>Read Intensive</td><td>Kioxia</td><td>PM7</td><td>KPM7XRUG7T68</td><td>7N1WT</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=T21WT">T21WT</a></td><td>C10E</td><td>7.68 TB</td><td>Capacity</td></tr>
</table>
<br>
{{< /rawhtml >}}

### NVMe 2.5" Cache or Capacity
{{< rawhtml >}}
<table>
<colgroup><col/><col/><col/><col/><col/><col/><col/><col/><col/><col/><col/><col/></colgroup>
<tr><th>Type</th><th>Drive Type</th><th>Form Factor</th><th>Endurance</th><th>Vendor</th><th>Series</th><th>Model</th><th>Device Part Number (P/N)</th><th>Firmware Software Bundle</th><th>Firmware Minimum Supported Version</th><th>Capacity</th><th>Use</th></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Mixed Use</td><td>Samsung</td><td>PM1735 SP 3WPD, SSD, NVMe, 2.5, 512e, ISE </td><td>MZWLJ1T6HBJR-00AD3</td><td>6GK00</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=5CM3G">5CM3G</a></td><td>2.5.0</td><td>1.6 TB</td><td>Cache, Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Mixed Use</td><td>Samsung</td><td>PM1735 SP 3WPD, SSD, Gen4 NVMe, 2.5, 512e, ISE</td><td>MZWLJ3T2HBJRAD3</td><td>15TVC</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=5CM3G">5CM3G</a></td><td>2.5.0</td><td>3.2TB</td><td>Cache,Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Mixed Use</td><td>Samsung</td><td>PM1735 SP 3WPD, SSD, Gen4 NVMe, 2.5, 512e, ISE</td><td>MZWLJ6T4HALAAD3</td><td>F6V5P</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=5CM3G">5CM3G</a></td><td>2.5.0</td><td>6.4TB</td><td>Cache,Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Mixed Use</td><td>Kioxia</td><td>CM6 SP</td><td>KCM6XVUL3T20</td><td>97GR0</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=GMM6V">GMM6V</a></td><td>2.2.2</td><td>3.2 TB</td><td>Cache, Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Mixed Use</td><td>Kioxia</td><td>CM6 SP</td><td>KCM6XVUL6T40</td><td>K916X</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=GMM6V">GMM6V</a></td><td>2.2.2</td><td>6.4 TB</td><td>Cache, Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Mixed Use</td><td>Samsung</td><td>PM1735 V2 SP 3WPD</td><td>MZWLR3T2HBLS-00AD3</td><td>V69W3</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=5V3P7">5V3P7</a></td><td>2.5.0</td><td>3.2 TB</td><td>Cache, Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Mixed Use</td><td>Samsung</td><td>PM1735 V2 SP 3WPD</td><td>MZWLR6T4HALA-00AD3</td><td>H8D5M</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=5V3P7">5V3P7</a></td><td>2.5.0</td><td>6.4 TB</td><td>Cache, Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Mixed Use</td><td>Samsung</td><td>PM1735a</td><td>MZWLR1T6HCJRAD3</td><td>H8GHV</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=28J8R">28J8R</a></td><td>1.1.1</td><td>1.6 TB</td><td>Cache,Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Mixed Use</td><td>Samsung</td><td>PM1735a</td><td>MZWLR3T2HCLSAD3</td><td>617H6</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=28J8R">28J8R</a></td><td>1.1.1</td><td>3.2 TB</td><td>Cache,Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Mixed Use</td><td>Samsung</td><td>PM1735a</td><td>MZWLR6T4HBLAAD3</td><td>9F6Y3</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=28J8R">28J8R</a></td><td>1.1.1</td><td>6.4 TB</td><td>Cache,Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Mixed Use</td><td>Kioxia</td><td>CM7</td><td>KCM7XVUG1T60</td><td>MP4F2</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=5JJFF">5JJFF</a></td><td>2.0.0 </td><td>1.6 TB</td><td>Cache, Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Mixed Use</td><td>Kioxia</td><td>CM7</td><td>KCM7XVUG3T20</td><td>XFNX0</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=5JJFF">5JJFF</a></td><td>2.0.0 </td><td>3.2 TB</td><td>Cache, Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Mixed Use</td><td>Kioxia</td><td>CM7</td><td>KCM7XVUG6T40</td><td>8RJJ9</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=5JJFF">5JJFF</a></td><td>2.0.0 </td><td>6.4 TB</td><td>Cache, Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Mixed Use</td><td>Hynix</td><td>PS1030</td><td>HFS1T6GEJVX171N</td><td>1HYKD</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=9M65G">9M65G</a></td><td>1.2.0</td><td>1.6 TB</td><td>Cache, Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Mixed Use</td><td>Hynix</td><td>PS1030</td><td>HFS3T2GEJVX171N</td><td>9VWPD</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=9M65G">9M65G</a></td><td>1.2.0</td><td>3.2 TB</td><td>Cache, Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Mixed Use</td><td>Hynix</td><td>PS1030</td><td>HFS6T4GEJVX171N</td><td>PYMY6</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=9M65G">9M65G</a></td><td>1.2.0</td><td>6.4 TB</td><td>Cache, Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Mixed Use</td><td>Samsung</td><td>PM1745</td><td>MZWLO1T6HCJR-00AD3</td><td>FVC2P</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=V7V0K">V7V0K</a></td><td>1.0.0</td><td>1.6 TB</td><td>Cache, Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Mixed Use</td><td>Samsung</td><td>PM1745</td><td>MZWLO3T2HCLS-00AD3</td><td>FDNHD</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=V7V0K">V7V0K</a></td><td>1.0.0</td><td>3.2 TB</td><td>Cache, Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Mixed Use</td><td>Samsung</td><td>PM1745</td><td>MZWLO6T4HBLA-00AD3</td><td>64K9C</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=V7V0K">V7V0K</a></td><td>1.0.0</td><td>6.4 TB</td><td>Cache, Capacity</td></tr>
</table>
<br>
{{< /rawhtml >}}

### NVMe 2.5" Capacity Only
{{< rawhtml >}}
<table>
<colgroup><col/><col/><col/><col/><col/><col/><col/><col/><col/><col/><col/><col/></colgroup>
<tr><th>Type</th><th>Drive Type</th><th>Form Factor</th><th>Endurance</th><th>Vendor</th><th>Series</th><th>Model</th><th>Device Part Number (P/N)</th><th>Firmware Software Bundle</th><th>Firmware Minimum Supported Version</th><th>Capacity</th><th>Use</th></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Samsung</td><td>PM1733 V2</td><td>MZWLR3T8HBLS-00AD3</td><td>G5N65</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=5V3P7">5V3P7</a></td><td>2.5.0</td><td>3.84 TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Samsung</td><td>PM1733 V2</td><td>MZWLR7T6HALA-00AD3</td><td>DX74Y</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=5V3P7">5V3P7</a></td><td>2.5.0</td><td>7.68 TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Samsung</td><td>PM1733a</td><td>MZWLR3T8HCLSAD3</td><td>RJKM5</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=28J8R">28J8R</a></td><td>1.1.1</td><td>3.84 TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Samsung</td><td>PM1733a</td><td>MZWLR7T6HBLAAD3</td><td>R1J8J</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=28J8R">28J8R</a></td><td>1.1.1</td><td>7.68 TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Samsung</td><td>PM1733a</td><td>MZWLR15THBLAAD3</td><td>D4CJG</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=28J8R">28J8R</a></td><td>1.1.1</td><td>15.36 TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Kioxia</td><td>CM6</td><td>KCM6XRUL1T92</td><td>N0VK0</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=GMM6V">GMM6V</a></td><td>2.2.2</td><td>1.92 TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Kioxia</td><td>CM6</td><td>KCM6XRUL3T84</td><td>8W2G5</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=GMM6V">GMM6V</a></td><td>2.2.2</td><td>3.84 TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Kioxia</td><td>CM6</td><td>KCM6XRUL7T68</td><td>VD0JX</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=GMM6V">GMM6V</a></td><td>2.2.2</td><td>7.68 TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Kioxia</td><td>CM6</td><td>KCM6XRUL15T3</td><td>J91CR</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=GMM6V">GMM6V</a></td><td>2.2.2</td><td>15.36 TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Mixed Use</td><td>Kioxia</td><td>CM7</td><td>KCM7XRUG1T92</td><td>M8YW0</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=5JJFF">5JJFF</a></td><td>2.0.0 </td><td>1.92 TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Mixed Use</td><td>Kioxia</td><td>CM7</td><td>KCM7XRUG3T84</td><td>XHYGF</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=5JJFF">5JJFF</a></td><td>2.0.0 </td><td>3.84 TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Mixed Use</td><td>Kioxia</td><td>CM7</td><td>KCM7XRUG7T68</td><td>VV2M7</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=5JJFF">5JJFF</a></td><td>2.0.0 </td><td>7.68 TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Mixed Use</td><td>Kioxia</td><td>CM7</td><td>KCM7XRUG15T3</td><td>DX2PD</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=5JJFF">5JJFF</a></td><td>2.0.0 </td><td>15.36 TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Kioxia</td><td>CD8</td><td>KCD8XRUG3T84</td><td>N1MK1</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=HV8P1">HV8P1</a></td><td>2.0.1</td><td>3.84 TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Hynix</td><td>PS1010</td><td>HFS1T9GEJVX171N</td><td>7GGK1</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=9M65G">9M65G</a></td><td>1.2.0</td><td>1.92 TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Hynix</td><td>PS1010</td><td>HFS3T8GEJVX171N</td><td>J4TDK</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=9M65G">9M65G</a></td><td>1.2.0</td><td>3.84 TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Hynix</td><td>PS1010</td><td>HFS7T6GEJVX171N</td><td>2533N</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=9M65G">9M65G</a></td><td>1.2.0</td><td>7.68 TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Hynix</td><td>PS1010</td><td>HFS15T3EJVX171N</td><td>8TY8G</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=9M65G">9M65G</a></td><td>1.2.0</td><td>15.36 TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Hynix</td><td>PE8010</td><td>HFS960GECTX088N</td><td>WR2FG</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=T1XKD">T1XKD</a></td><td>1.3.0</td><td>960 GB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Kioxia</td><td>CD8</td><td>SDF1E86DAB</td><td>YNGYD</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=HV8P1">HV8P1</a></td><td>2.0.1</td><td>960 GB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Micron</td><td>7450</td><td>MTFDKCC960TFR-1BC1ZABDA</td><td>KXT48</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=RPTG2">RPTG2</a></td><td>1.3.0</td><td>960 GB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Micron</td><td>7500</td><td>MTFDKCC960TGP-1BK1JABDA</td><td>G7NCH</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=HW0R3">HW0R3</a></td><td>1.1.0</td><td>960 GB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Samsung</td><td>PM9A3</td><td>MZQL2960HCJR-00AD3</td><td>6HYWM</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=XMFKX">XMFKX</a></td><td>1.1.1</td><td>960 GB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Samsung</td><td>PM1733a</td><td>MZWLR1T9HCJR-00AD3</td><td>8PMRM</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=28J8R">28J8R</a></td><td>1.1.1</td><td>1.92 TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Samsung</td><td>PM1733 V2</td><td>MZWLR1T9HBJR-00AD3</td><td>WPR17</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=5V3P7">5V3P7</a></td><td>2.5.0</td><td>1.92 TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Samsung</td><td>PM9A3</td><td>MZQL21T9H</td><td>TGYF5</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=XMFKX">XMFKX</a></td><td>1.1.1</td><td>1.92TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Micron</td><td>7450</td><td>MTFDKCC1T9TFR</td><td>JH61J</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=RPTG2">RPTG2</a></td><td>1.3.0</td><td>1.92 TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Micron</td><td>7500</td><td>MTFDKCC1T9TGP</td><td>M7RHM</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=HW0R3">HW0R3</a></td><td>1.1.0</td><td>1.92 TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Hynix</td><td>PE8110</td><td>HFS1T9GEETX099N</td><td>147DR</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=TDGKY">TDGKY</a></td><td>1.1.0</td><td>1.92 TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Micron</td><td>7450</td><td>MTFDKCC3T8TFR-1BC1ZABDA</td><td>NDK2D</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=RPTG2">RPTG2</a></td><td>1.3.0</td><td>3.84 TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Kioxia</td><td>CD7</td><td>KCD7XRUG3T84</td><td>RFYP9</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=K6597">K6597</a></td><td>2.0.1</td><td>3.84 TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Hynix</td><td>PE8010</td><td>HFS3T8GECTX088N</td><td>V6WP5</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=T1XKD">T1XKD</a></td><td>1.3.0</td><td>3.84 TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Samsung</td><td>PM9A3</td><td>MZQL23T8HCLSAD3</td><td>P7G03</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=XMFKX">XMFKX</a></td><td>1.1.1</td><td>3.84 TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Micron</td><td>7500</td><td>MTFDKCC3T8TGP-1BK1JABDA</td><td>GT3F3</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=HW0R3">HW0R3</a></td><td>1.1.0</td><td>3.84 TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Intel</td><td>Arbordale Plus R P5316</td><td>SSDPF2NV307TZ</td><td>4KCVT</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=4XT8T">4XT8T</a></td><td>1.6.0</td><td>30.72 TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Samsung</td><td>PM1743</td><td>MZWLO3T8HCLS-00AD3</td><td>9GXVF</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=V7V0K">V7V0K</a></td><td>1.0.0 </td><td>3.84 TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Samsung</td><td>PM1743</td><td>MZWLO7T6HBLA-00AD3</td><td>DNPR4</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=V7V0K">V7V0K</a></td><td>1.0.0</td><td>7.68 TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Kioxia</td><td>CD8</td><td>KCD8XRUG1T92</td><td>NNKCT</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=HV8P1">HV8P1</a></td><td>2.0.1</td><td>1.92 TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Samsung</td><td>PM9A3</td><td>MZQL27T6HBLAAD3</td><td>30FX3</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=XMFKX">XMFKX</a></td><td>1.1.1</td><td>7.68TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Micron</td><td>7450</td><td>MTFDKCC7T6TFR-1BC1ZABDA</td><td>91KYJ</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=RPTG2">RPTG2</a></td><td>1.3.0</td><td>7.68TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Micron</td><td>7500</td><td>MTFDKCC7T6TGP-ABK1JABYYES</td><td>RTJFW</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=HW0R3">HW0R3</a></td><td>1.1.0</td><td>7.68TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Kioxia</td><td>CD8</td><td>KCD8XRUG7T68</td><td>MXD8J</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=HV8P1">HV8P1</a></td><td>2.0.1</td><td>7.68TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>SK Hynix</td><td>PE8110</td><td>HFS960GEETX099N</td><td>26WJ0</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=TDGKY">TDGKY</a></td><td>1.1.0</td><td>960GB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Samsung</td><td>PM1743</td><td>MZWLO1T9HCJR-00AD3</td><td>G64N5</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=V7V0K">V7V0K</a></td><td>1.0.0</td><td>1.92TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>SK Hynix</td><td>PE8110</td><td>HFS3T8GEETX099N</td><td>2V97V</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=TDGKY">TDGKY</a></td><td>1.1.0</td><td>3.84TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>2.5</td><td>Read Intensive</td><td>Samsung</td><td>PM1743</td><td>MZWLO15THBLA-00AD3</td><td>VPWMR</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=V7V0K">V7V0K</a></td><td>1.0.0</td><td>15.36TB</td><td>Capacity</td></tr>
</table>
<br>
{{< /rawhtml >}}

{{< rawhtml >}}
</div>

</body>

</html>


{{< /rawhtml >}}

