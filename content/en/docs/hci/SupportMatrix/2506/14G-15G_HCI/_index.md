---
title: "Azure Local Support Matrix for 14G-15G (2506)"
linkTitle: "14G-15G"
weight: 7494
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

{{% alert title="NOTE" color="primary" %}}
The Dell AX System for Azure Local AX-640, AX-740xd, AX-650, AX-750, AX-7525, and AX-6515 now supports upgrades from Azure Stack HCI operating system 22H2 to Azure Stack HCI operating system 23H2. The cluster must have firmware and drivers updated to the levels listed in this support matrix prior to starting the upgrade process.

Please see the following knowledge base article for procedure details and known issues:<br>
[Upgrade Azure Stack HCI operating system 22H2 to Azure Stack HCI operating system 23H2](https://www.dell.com/support/kbdoc/en-us/000259175/upgrade-azure-local-version-22h2-to-azure-local-version-23h2)
{{% /alert %}}

### Supported Platforms
{{< rawhtml >}}
<table>
<colgroup><col/><col/></colgroup>
<tr><th>Model</th><th>Supported Operating System</th></tr>
<tr><td>AX-4510c</td><td>Windows Server 2022 Datacenter<br>Windows Server 2025 Datacenter<br>Azure Stack HCI-23H2<br>Azure Stack HCI-24H2</td></tr>
<tr><td>AX-4520c</td><td>Windows Server 2022 Datacenter<br>Windows Server 2025 Datacenter<br>Azure Stack HCI-23H2<br>Azure Stack HCI-24H2</td></tr>
</table>
<br>
{{< /rawhtml >}}

### Base Components
{{< rawhtml >}}
<table>
<colgroup><col/><col/><col/><col/><col/><col/></colgroup>
<tr><th>Component</th><th>Type</th><th>Software Bundle</th><th>Minimum Supported Version</th><th>Supported Platforms</th><th>Supported OS</th></tr>
<tr><td>BIOS</td><td>Firmware DUP</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=YR56G">YR56G</a></td><td>1.18.2</td><td>AX-4510c<br><br>AX-4520c</td><td>NA</td></tr>
<tr><td>iDRAC9 with Lifecycle Controller</td><td>Firmware DUP</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=WN31M">WN31M</a></td><td>7.20.30.50</td><td>AX-4510c<br><br>AX-4520c</td><td>NA</td></tr>
<tr><td>Chipset driver for 15G Intel platforms</td><td>Driver DUP</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=C2MC3">C2MC3</a></td><td>10.1.19928.8615</td><td>AX-4510c<br><br>AX-4520c</td><td>Windows Server 2022 Datacenter<br><br>Windows Server 2025 Datacenter<br><br>Azure Stack HCI-23H2<br><br>Azure Stack HCI-24H2</td></tr>
<tr><td>iDRAC Service Module</td><td>Firmware DUP</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=258RC">258RC</a></td><td>5.4.0.0</td><td>AX-4510c<br><br>AX-4520c</td><td>NA</td></tr>
<tr><td>Chassis Manager</td><td>Firmware DUP</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=WC84H">WC84H</a></td><td>5</td><td>AX-4510c<br><br>AX-4520c</td><td>NA</td></tr>
<tr><td>CPLD</td><td>Firmware DUP</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=G1YRC">G1YRC</a></td><td>1.0.5</td><td>AX-4510c<br><br>AX-4520c</td><td>NA</td></tr>
</table>
<br>
{{< /rawhtml >}}

### Network Adapters
{{< rawhtml >}}
<table>
<colgroup><col/><col/><col/><col/><col/><col/><col/><col/></colgroup>
<tr><th>Component</th><th>Part Number</th><th>SDDC AQ for Windows Server 2022</th><th>RDMA Protocol</th><th>Firmware Software Bundle</th><th>Firmware Minimum Supported Version</th><th>Driver Software Bundle</th><th>Driver Minimum Supported Version</th><th>Supported OS</th><th>Supported Platforms</th></tr>
<tr><td>Broadcom 57504 Quad Port 10/25GbE SFP28 Adapter, PCIe FH</td><td>J3D14</td><td rowspan="1">Management<br><br>Compute (Premium)<br><br>Storage (Premium)</td><td rowspan="1">RoCEv2</td><td rowspan="1"><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=DRJDR">DRJDR</a></td><td rowspan="1">23.21.14.14</td><td rowspan="1"><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=J3MP2">J3MP2</a></td><td rowspan="1">232.1.141.4</td><td rowspan="1">Windows Server 2025 Datacenter<br><br>Azure Stack HCI-24H2</td><td rowspan="1">AX-4520c</td></tr>
<tr><td>Intel E823</td><td>KJMHJ</td><td rowspan="1">Management<br><br>Compute (Premium)<br><br>Storage (Premium)</td><td rowspan="1">iWARP,RoCEv2</td><td rowspan="1"><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=N11TD">N11TD</a></td><td rowspan="1">24.0.5</td><td rowspan="1"><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=J4YG9">J4YG9</a></td><td rowspan="1">24</td><td rowspan="1">Windows Server 2022 Datacenter<br><br>Windows Server 2025 Datacenter<br><br>Azure Stack HCI-23H2<br><br>Azure Stack HCI-24H2</td><td rowspan="1">AX-4510c<br><br>AX-4520c</td></tr>
<tr><td>Intel E810-CQDA2 Dual Port 100GbE QSFP28 Adapter, PCIe FH</td><td>85F8F</td><td rowspan="2">Management<br><br>Compute (Premium)<br><br>Storage (Premium)</td><td rowspan="2">iWARP,RoCEv2</td><td rowspan="2"><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=N11TD">N11TD</a></td><td rowspan="2">24.0.5</td><td rowspan="2"><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=J4YG9">J4YG9</a></td><td rowspan="2">24</td><td rowspan="2">Windows Server 2022 Datacenter<br><br>Windows Server 2025 Datacenter<br><br>Azure Stack HCI-23H2<br><br>Azure Stack HCI-24H2</td><td rowspan="2">AX-4520c</td></tr>
<tr><td>Intel E810-XXV Dual Port 25GbE SFP28 Adapter, PCIe FH</td><td>CD16M</td>
<tr><td>Mellanox ConnectX-6 Dx Dual Port 100GbE QSFP56 PCIe Adapter, FH</td><td>8P2T2</td><td rowspan="1">Management<br><br>Compute (Premium)<br><br>Storage (Premium)</td><td rowspan="1">RoCEv2</td><td rowspan="1"><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=975XG">975XG</a></td><td rowspan="1">22.44.10.36</td><td rowspan="1"><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=3G71F">3G71F</a></td><td rowspan="1">25.1</td><td rowspan="1">Windows Server 2022 Datacenter<br><br>Windows Server 2025 Datacenter<br><br>Azure Stack HCI-23H2<br><br>Azure Stack HCI-24H2</td><td rowspan="1">AX-4520c</td></tr>
<tr><td>Nvidia ConnectX-6 Lx Dual Port 10/25GbE SFP28 Adapter, PCIe FH</td><td>R5WK9</td><td rowspan="1">Management<br><br>Compute (Premium)<br><br>Storage (Premium)</td><td rowspan="1">RoCEv2</td><td rowspan="1"><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=K65HP">K65HP</a></td><td rowspan="1">26.44.10.36</td><td rowspan="1"><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=3G71F">3G71F</a></td><td rowspan="1">25.1</td><td rowspan="1">Windows Server 2022 Datacenter<br><br>Windows Server 2025 Datacenter<br><br>Azure Stack HCI-23H2<br><br>Azure Stack HCI-24H2</td><td rowspan="1">AX-4520c</td></tr>
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
<tr><td>A2</td><td>NVIDIA</td><td>NVIDIA Ampere A2, PCIe, 60W, 16GB Passive, Single Wide, Full Height GPU, V2</td><td>MG5JX</td><td>94.07.5B.00.55</td><td>528.89 WHQL</td><td>Yes</td><td>AX-4520c</td><td>Azure Stack HCI-23H2</td></tr>
<tr><td>L4</td><td>NVIDIA</td><td>NVIDIA L4, PCIe, 72W, 24GB Passive, Single Wide Full Height GPU</td><td>NG3PY</td><td>95.04.29.00.06</td><td>528.89 WHQL</td><td>Yes</td><td>AX-4520c</td><td>Azure Stack HCI-23H2</td></tr>
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
<tr><td>BOSS-N1</td><td>M88HH</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=VXX8P">VXX8P</a></td><td>2.1.13.2033</td><td>Inbox</td><td></td><td>AX-4510c<br><br>AX-4520c</td><td>Windows Server 2022 Datacenter<br><br>Windows Server 2025 Datacenter<br><br>Azure Stack HCI-23H2<br><br>Azure Stack HCI-24H2</td></tr>
</table>
<br>
{{< /rawhtml >}}


### NVMe 2.5" Capacity Only
{{< rawhtml >}}
<table>
<colgroup><col/><col/><col/><col/><col/><col/><col/><col/><col/><col/><col/><col/></colgroup>
<tr><th>Type</th><th>Drive Type</th><th>Form Factor</th><th>Endurance</th><th>Vendor</th><th>Series</th><th>Model</th><th>Device Part Number (P/N)</th><th>Firmware Software Bundle</th><th>Firmware Minimum Supported Version</th><th>Capacity</th><th>Use</th></tr>
<tr><td>NVMe</td><td>PCIe</td><td>M.2</td><td>Read Intensive</td><td>Micron</td><td>7400</td><td>MTFDKBG1T9TDZ</td><td>G18YX</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=N71F4">N71F4</a></td><td>1.6.0</td><td>1.92TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>M.2</td><td>Read Intensive</td><td>Micron</td><td>7400</td><td>MTFDKBG3T8TDZ</td><td>2RN2N</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=N71F4">N71F4</a></td><td>1.6.0</td><td>3.84TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>M.2</td><td>Read Intensive</td><td>Hynix</td><td>PE8010</td><td>HFS960GDC8X099N</td><td>21GXV</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=R2TTT">R2TTT</a></td><td>1.3.0</td><td>960GB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>M.2</td><td>Mixed Use</td><td>Hynix</td><td>PE8030</td><td>HFS800GDC8X088N</td><td>31XDY</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=R2TTT">R2TTT</a></td><td>1.3.0</td><td>800GB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>M.2</td><td>Mixed Use</td><td>Micron</td><td>7450</td><td>MTFDKBA800TFS</td><td>F9MKX</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=HNW5G">HNW5G</a></td><td>1.1.0</td><td>800GB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>M.2</td><td>Mixed Use</td><td>Hynix</td><td>PE9030</td><td>HFS800GDJ8X167N</td><td>FYWN9</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=8G62T">8G62T</a></td><td>1.1.0</td><td>800GB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>M.2</td><td>Read Intensive</td><td>Hynix</td><td>PE9010</td><td>HFS960GDJ8X167N</td><td>XN5KG</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=CDKNW">CDKNW</a></td><td>1.1.0</td><td>960GB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>M.2</td><td>Read Intensive</td><td>Hynix</td><td>PE9010</td><td>HFS960GEJ8X167N</td><td>4H05X</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=88JVY">88JVY</a></td><td>1.0.0</td><td>960GB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>M.2</td><td>Read Intensive</td><td>Micron</td><td>7450</td><td>MTFDKBA960TFR</td><td>PH7J6</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=HNW5G">HNW5G</a></td><td>1.1.0</td><td>960GB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>M.2</td><td>Read Intensive</td><td>Micron</td><td>7450</td><td>MTFDKBG1T9TFR</td><td>J927V</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=HNW5G">HNW5G</a></td><td>1.1.0</td><td>1.92TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>M.2</td><td>Read Intensive</td><td>Hynix</td><td>PE8110 </td><td>HFS1T9GDE0X088N</td><td>MY5M4</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=19H08">19H08</a></td><td>1.1.0</td><td>1.92TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>M.2</td><td>Read Intensive</td><td>Micron</td><td>7450</td><td>MTFDKBG3T8TFR</td><td>5FP33</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=HNW5G">HNW5G</a></td><td>1.1.0</td><td>3.84TB</td><td>Capacity</td></tr>
<tr><td>NVMe</td><td>PCIe</td><td>M.2</td><td>Read Intensive</td><td>Hynix </td><td>PE8110 </td><td>HFS3T8GDE0X088N</td><td>5JR5H</td><td><a href="https://www.dell.com/support/home/en-us/drivers/driversdetails?driverid=19H08">19H08</a></td><td>1.1.0 </td><td>3.84TB</td><td>Capacity</td></tr>
</table>
<br>
{{< /rawhtml >}}

{{< rawhtml >}}
</div>

</body>

</html>


{{< /rawhtml >}}

