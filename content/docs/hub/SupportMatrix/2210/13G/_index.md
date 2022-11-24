---
title: "Support Matrix for 13G - 2210"
linkTitle: "13G"
weight: 3
Description: >

---

### Dell Integrated System for Microsoft Azure Stack Hub Support Matrix for 13th Generation PowerEdge Servers - Valid from Dell 2210 release and Microsoft 2206 release

#### Abstract
This support matrix provides information about supported software and hardware configurations for Dell Integrated System for Microsoft Azure Stack Hub, based on 13G PowerEdge servers.
{{% alert title="NOTE" color="primary" %}}
The information in this manual is subject to change without notice. Contact your Dell Technologies Support representative for more information.
{{% /alert %}}

#### Introduction
The Dell EMC Integrated System for Microsoft Azure Stack Hub Support Matrix describes supported drivers, firmware, applications, and hardware for Dell EMC Integrated System for Microsoft Azure Stack Hub.

{{% alert title="NOTE" color="primary" %}}
All references to release dates refer to Dell EMC releases, unless otherwise indicated.
{{% /alert %}}

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

### 13G Scale Units - PowerEdge R730xd
{{< rawhtml >}}
<table> <colgroup><col/><col/><col/><col/><col/><col/></colgroup> <tr><th>Component</th><th>Type</th><th>Category</th><th>Dell Part Number (P/N)</th><th>Software Bundle (SWB)</th><th>Supported Version</th></tr> <tr><td>Intel C600/C610/C220/C230/C2000 Series</td><td>Driver DUP</td><td>Chipset</td><td>N/A</td><td>73TJK</td><td>10.1.17809.8096</td></tr> <tr><td>Mellanox ConnectX-3 PRO / 10GbE</td><td>Driver DUP</td><td>Network / RDMA</td><td>N/A</td><td>VMPP8</td><td>05.050.09</td></tr> <tr><td>Dell HBA330</td><td>Driver DUP</td><td>Storage - HBA</td><td>N/A</td><td>MF8G0</td><td>2.51.25.02</td></tr> <tr><td>BIOS</td><td>Firmware DUP</td><td>BIOS</td><td>N/A</td><td>02CYD</td><td>2.15.0</td></tr> <tr><td>iDRAC with LifeCycle Controller</td><td>Firmware DUP</td><td>Lifecycle Controller</td><td>N/A</td><td>DDK5R</td><td>2.83.83.83</td></tr> <tr><td>Mellanox ConnectX-3 PRO / 10GbE</td><td>Firmware DUP</td><td>Network / RDMA</td><td>N/A</td><td>H9RJP</td><td>02.42.50.58</td></tr> <tr><td>Expander Storage Backplane</td><td>Firmware DUP</td><td>Storage - Backplane</td><td>N/A</td><td>HYPYY</td><td>3.35</td></tr> <tr><td>Non-expander Storage Backplane</td><td>Firmware DUP</td><td>Storage - Backplane</td><td>N/A</td><td>HRP1V</td><td>2.25</td></tr> <tr><td>Dell HBA330</td><td>Firmware DUP</td><td>Storage - HBA</td><td>N/A</td><td>124X2</td><td>16.17.01.00</td></tr> <tr><td>HGST Aries K Plus HUS726040ALA614 - 4TB</td><td>Firmware DUP</td><td>Storage - SATA HDD </td><td>KH21H</td><td>22TC7</td><td>KN45</td></tr> <tr><td>HGST HUS726060ALE614 -6TB</td><td>Firmware DUP</td><td>Storage - SATA HDD </td><td>908XX </td><td>PWDVD</td><td>KP45</td></tr> <tr><td>Seagate ST4000NM0035-1V4107 - 4TB</td><td>Firmware DUP</td><td>Storage - SATA HDD </td><td>KRH17</td><td>R100W</td><td>DA06</td></tr> <tr><td>Seagate ST4000NM016A-2HZ130 - 4TB</td><td>Firmware DUP</td><td>Storage - SATA HDD </td><td>XPJ47</td><td>M1WWC</td><td>CAJC</td></tr> <tr><td>Seagate ST4000NM0265-2DC107 - 4TB</td><td>Firmware DUP</td><td>Storage - SATA HDD </td><td>MWHY9</td><td>M5GJ1</td><td>DB34</td></tr> <tr><td>Seagate ST6000NM0024-1HT17Z - 6TB</td><td>Firmware DUP</td><td>Storage - SATA HDD </td><td>P00JM</td><td>V8K8V</td><td>MA35</td></tr> <tr><td>Seagate ST6000NM0024-1US17Z - 6TB</td><td>Firmware DUP</td><td>Storage - SATA HDD </td><td>W1C90</td><td>NK11N</td><td>MA8H</td></tr> <tr><td>Seagate ST6000NM0115 -6TB</td><td>Firmware DUP</td><td>Storage - SATA HDD </td><td>YXTWT</td><td>5F8VF</td><td>DA25</td></tr> <tr><td>Toshiba MG04ACA600E - 6TB</td><td>Firmware DUP</td><td>Storage - SATA HDD </td><td>KP22D</td><td>WN6C3</td><td>FS7D</td></tr> <tr><td>TOSHIBA MG05ACA600E - 6TB</td><td>Firmware DUP</td><td>Storage - SATA HDD </td><td>81Y15</td><td>5H8JW</td><td>GX6D</td></tr> <tr><td>TOSHIBA MG05ACA800E - 4TB</td><td>Firmware DUP</td><td>Storage - SATA HDD </td><td>4WXV5</td><td>5H8JW</td><td>GX6D</td></tr> <tr><td>TOSHIBA MG06ACA800EY - 4TB</td><td>Firmware DUP</td><td>Storage - SATA HDD </td><td>9X09C</td><td>PT7D8</td><td>GA09</td></tr> <tr><td>TOSHIBA MG08ADA400NY - 4TB</td><td>Firmware DUP</td><td>Storage - SATA HDD </td><td>W2M9N</td><td>7NJXF</td><td>GD03</td></tr> <tr><td>Toshiba Tomcat R MG04ACA400N - 4TB</td><td>Firmware DUP</td><td>Storage - SATA HDD </td><td>4N6CY</td><td>9KX6F</td><td>FJ3D</td></tr> <tr><td>Toshiba Tomcat R MG04ACA400NY - 4TB</td><td>Firmware DUP</td><td>Storage - SATA HDD </td><td>95M6K</td><td>V47C4</td><td>FK5D</td></tr> <tr><td>Intel S4510 SSDSC2KB019T8R - 1.92TB</td><td>Firmware DUP</td><td>Storage - SATA SSD </td><td>33R2T</td><td>2674V</td><td>DL69</td></tr> <tr><td>Intel S4600 SSDSC2KG019T7R - 1.92TB</td><td>Firmware DUP</td><td>Storage - SATA SSD </td><td>MWKF2</td><td>MCR6M</td><td>DL58</td></tr> <tr><td>Intel S4610 SSDSC2KG019T8R - 1.92TB</td><td>Firmware DUP</td><td>Storage - SATA SSD </td><td>55J8H</td><td>4RM7F</td><td>DL67</td></tr> <tr><td>Intel SSDSC2BA012T4R WI SSD - 1.2TB</td><td>Firmware DUP</td><td>Storage - SATA SSD </td><td>6T6R8</td><td>KCXYV</td><td>DL2D</td></tr> <tr><td>Intel SSDSC2BX016T4R - 1.6TB</td><td>Firmware DUP</td><td>Storage - SATA SSD </td><td>2CC4N</td><td>RXYF1</td><td>DL2D</td></tr> <tr><td>Samsung MZ7KH1T9HAJR0D3 - 1.92TB</td><td>Firmware DUP</td><td>Storage - SATA SSD </td><td>71K37</td><td>3J3JR</td><td>HF58</td></tr> <tr><td>Samsung MZ7KM1T9HAJM00D3 SM863 - 1.92TB</td><td>Firmware DUP</td><td>Storage - SATA SSD </td><td>KNT26</td><td>P3C5P</td><td>GB55</td></tr> <tr><td>Samsung SM863a MZ7KM1T9HMJP0D3 - 1.92TB</td><td>Firmware DUP</td><td>Storage - SATA SSD </td><td>K5P0T</td><td>97D8J</td><td>GD57</td></tr> <tr><td>Toshiba 1.6TB THNSF81D60CSE HK4 ISE - 1.6TB</td><td>Firmware DUP</td><td>Storage - SATA SSD </td><td>DMF5Y</td><td>H3XHN</td><td>DACB</td></tr> <tr><td>Toshiba KHK6YVSE1T92 - 1.92TB</td><td>Firmware DUP</td><td>Storage - SATA SSD </td><td>0DXJ7</td><td>5NR6X</td><td>DBC3</td></tr> <tr><td>Intel  S4500 SSDSC2KB960G7R - 960GB</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot)</td><td>4T7DD</td><td>MCR6M</td><td>DL58</td></tr> <tr><td>Intel S3520 SSDSC2BB480G7R</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot)</td><td>64TMJ</td><td>CHJGV</td><td>DL43</td></tr> <tr><td>Intel S3610 SSDSC2BX400G4R - 400GB</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot)</td><td>65WJJ</td><td>RXYF1</td><td>DL2D</td></tr> <tr><td>Intel S4500 SSDSC2KB480G7R - 480GB</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot)</td><td>FH49G</td><td>MCR6M</td><td>DL58</td></tr> <tr><td>Intel S4600 SSDSC2KG480G7R - 480GB</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot)</td><td>P7KTJ</td><td>MCR6M</td><td>DL58</td></tr> <tr><td>Intel SSDSC2BA400G4R</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot)</td><td>7C7FK</td><td>KCXYV</td><td>DL2D</td></tr> <tr><td>Intel SSDSC2BB480G4R</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot)</td><td>CFPWY</td><td>XC8N4</td><td>DL16</td></tr> <tr><td>INTEL SSDSC2BG400G4R</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot)</td><td>K3TKG</td><td>RXYF1</td><td>DL2D</td></tr> <tr><td>Intel SSDSC2BX400G4R</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot)</td><td>8CDHV</td><td>RXYF1</td><td>DL2D</td></tr> <tr><td>Intel SSDSC2KB480G8R - 480GB</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot)</td><td>VPP5P</td><td>4RM7F</td><td>DL67</td></tr> <tr><td>Intel SSDSC2KB960G8R - 960GB</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot)</td><td>T50K8</td><td>4RM7F</td><td>DL67</td></tr> <tr><td>Intel SSDSC2KG480G8R - 480GB</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot)</td><td>6JGT5</td><td>4RM7F</td><td>DL67</td></tr> <tr><td>Samsung MZ7KH480HAHQ0D3 - 480GB</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot)</td><td>3KVC5</td><td>3J3JR</td><td>HF58</td></tr> <tr><td>Samsung MZ7KM400HAHP00D3</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot)</td><td>P13M2</td><td>RGXP4</td><td>GB49</td></tr> <tr><td>Samsung MZ7KM480HAHP00D3</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot)</td><td>2VH3F</td><td>P3C5P</td><td>GB55</td></tr> <tr><td>Samsung MZ7LH480HAHQ0D3 - 480GB</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot)</td><td>GYD5H</td><td>KFGG3</td><td>HE57</td></tr> <tr><td>Samsung MZ7LM480HCHP00D3</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot)</td><td>FWGFP</td><td>YJ52X</td><td>GA3A</td></tr> <tr><td>Samsung SM863a MZ7KM480HMHQ0D3 - 480GB (Boot Device)</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot)</td><td>2RGGR</td><td>97D8J</td><td>GD57</td></tr> <tr><td>Toshiba 400GB THNSF8400CCSE HK4 ISE (Boot Device)</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot)</td><td>VKT80</td><td>H3XHN</td><td>DACB</td></tr> <tr><td>Toshiba KHK6YVSE480G - 480GB</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot)</td><td>T3CX8</td><td>5NR6X</td><td>DBC3</td></tr> <tr><td>Intel S3610 SSDSC2BG800G4R SSD - 800GB</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot/Cache)</td><td>072PJ</td><td>RXYF1</td><td>DL2D</td></tr> <tr><td>Intel S3610 SSDSC2BX800G4R SSD - 800GB</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot/Cache)</td><td>C2GJT</td><td>RXYF1</td><td>DL2D</td></tr> <tr><td>Intel S3710 SSDSC2BA800G4R - 800GB</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot/Cache)</td><td>DPD14 </td><td>KCXYV</td><td>DL2D</td></tr> <tr><td>Intel S4600 SSDSC2KG960G7R   960GB</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot/Cache)</td><td>TR3MY</td><td>MCR6M</td><td>DL58</td></tr> <tr><td>Intel SSDSC2BX800G4R SSD - 800GB</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot/Cache)</td><td>9F3GY</td><td>RXYF1</td><td>DL2D</td></tr> <tr><td>Intel SSDSC2KG960G8R - 960GB</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot/Cache)</td><td>X31G3</td><td>4RM7F</td><td>DL67</td></tr> <tr><td>Samsung MZ7KH960HAJR0D3 - 960GB</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot/Cache)</td><td>YDHYX</td><td>3J3JR</td><td>HF58</td></tr> <tr><td>Samsung MZ7KM960HAHP00D3 SM863 - 960GB</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot/Cache)</td><td>3RDJV</td><td>P3C5P</td><td>GB55</td></tr> <tr><td>Samsung SM863a MZ7KM960HMJP0D3 - 960GB</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot/Cache)</td><td>DD4G0</td><td>97D8J</td><td>GD57</td></tr> <tr><td>Toshiba KHK6YVSE960G - 960GB</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot/Cache)</td><td>XW4D1</td><td>5NR6X</td><td>DBC3</td></tr> <tr><td>Toshiba THNSF8800CCSE SSD - 800GB</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot/Cache)</td><td>VCRY6</td><td>H3XHN</td><td>DACB</td></tr> <tr><td>uEFI diag</td><td>Tools-Software</td><td>Dell 64 Bit uEFI Diagnostics</td><td>N/A</td><td>JM78R</td><td>4239A37</td></tr> </table><br>
{{< /rawhtml >}}

### 13G Hardware Lifecycle Host - PowerEdge R430
{{< rawhtml >}}
<table> <colgroup><col/><col/><col/><col/><col/><col/></colgroup> <tr><th>Component</th><th>Type</th><th>Category</th><th>Dell Part Number (P/N)</th><th>Software Bundle (SWB)</th><th>Supported Version</th></tr> <tr><td>Intel C600/C610/C220/C230/C2000 Series</td><td>Driver DUP</td><td>Chipset</td><td>N/A</td><td>73TJK</td><td>10.1.17809.8096</td></tr> <tr><td>Intel X520 (10Gb NDC)</td><td>Driver DUP</td><td>Network</td><td>N/A</td><td>2YNFG</td><td>20.5.0</td></tr> <tr><td>PERC H330</td><td>Driver DUP</td><td>SAS HBA - Internal</td><td>N/A</td><td>N/A</td><td>Native</td></tr> <tr><td>PERC H730</td><td>Driver DUP</td><td>SAS HBA - Internal</td><td>N/A</td><td>N/A</td><td>Native</td></tr> <tr><td>BIOS</td><td>Firmware DUP</td><td>BIOS</td><td>N/A</td><td>652H4</td><td>2.15.0</td></tr> <tr><td>iDRAC plus Lifecycle controller</td><td>Firmware DUP</td><td>iDRAC plus Lifecycle Controller</td><td>N/A</td><td>DDK5R</td><td>2.83.83.83</td></tr> <tr><td>Intel X520 (10Gb NDC)</td><td>Firmware DUP</td><td>Network</td><td>N/A</td><td>3XVMN</td><td>20.5.15</td></tr> <tr><td>PERC H330</td><td>Firmware DUP</td><td>SAS HBA - Internal</td><td>N/A</td><td>NYKX7</td><td>25.5.9.0001</td></tr> <tr><td>PERC H730</td><td>Firmware DUP</td><td>SAS HBA - Internal</td><td>N/A</td><td>700GG</td><td>25.5.9.0001</td></tr> <tr><td>Backplane</td><td>Firmware DUP</td><td>Storage - Backplane</td><td>N/A</td><td>HRP1V</td><td>2.25</td></tr> <tr><td>Intel MZ7KH960HAJR0D3 - 960GB</td><td>Firmware DUP</td><td>Storage - SATA SSD  (Boot)</td><td>YDHYX</td><td>3J3JR</td><td>HF58</td></tr> <tr><td>Intel S4600 SSDSC2KG960G7R   960GB</td><td>Firmware DUP</td><td>Storage - SATA SSD  (Boot)</td><td>TR3MY</td><td>MCR6M</td><td>DL58</td></tr> <tr><td>Intel SSDSC2KB960G8R - 960GB</td><td>Firmware DUP</td><td>Storage - SATA SSD  (Boot)</td><td>T50K8</td><td>4RM7F</td><td>DL67</td></tr> <tr><td>Intel SSDSC2KG960G8R - 960GB</td><td>Firmware DUP</td><td>Storage - SATA SSD  (Boot)</td><td>X31G3</td><td>4RM7F</td><td>DL67</td></tr> <tr><td>Intel  S4500 SSDSC2KB960G7R - 960GB</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot)</td><td>4T7DD</td><td>MCR6M</td><td>DL58</td></tr> <tr><td>Intel S3610 SSD SSDSC2BG800G4R</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot)</td><td>072PJ</td><td>RXYF1</td><td>DL2D</td></tr> <tr><td>Samsung SM863a MZ7KM960HMJP0D3 - 960GB</td><td>Firmware DUP</td><td>Storage - SATA SSD (Boot)</td><td>DD4G0</td><td>97D8J</td><td>GD57</td></tr> <tr><td>uEFI diag</td><td>Tools-Software</td><td>Dell 64 Bit uEFI Diagnostics</td><td>N/A</td><td>JM78R</td><td>4239A37</td></tr> <tr><td>OpenManage Enterprise</td><td>Tools-Software</td><td>Software</td><td>N/A</td><td>N/A</td><td>3.8.2</td></tr> <tr><td>OpenManage Network Manager</td><td>Tools-Software</td><td>Software</td><td>N/A</td><td>N/A</td><td>8.0.1.66</td></tr> <tr><td>Secure Connect Gateway</td><td>Tools-Software</td><td>Software</td><td>N/A</td><td>N/A</td><td>5.12.00.00</td></tr> </table><br>
{{< /rawhtml >}}
### Switches
{{< rawhtml >}}
<table> <colgroup><col/><col/><col/><col/></colgroup> <tr><th>Platform</th><th>Type</th><th>Dell Part Number (P/N)</th><th>Supported Switch OS Version</th></tr> <tr><td>Dell EMC PowerSwitch S3048-ON</td><td>MGMT</td><td>0TWR5D</td><td>9.14.2.14</td></tr> <tr><td>Dell EMC PowerSwitch S4048-ON</td><td>ToR</td><td>08N75N</td><td>9.14.2.14</td></tr> </table><br>
{{< /rawhtml >}}
### Other Components
{{< rawhtml >}}
<table> <colgroup><col/><col/><col/><col/><col/></colgroup> <tr><th>Vendor</th><th>Platform</th><th>Component</th><th>Model</th><th>Firmware</th></tr> <tr><td>Nvidia</td><td>PowerEdge 640</td><td>GPU</td><td>T4</td><td>90.04.96.00.01</td></tr> <tr><td>Nvidia</td><td>PowerEdge 840 Dense</td><td>GPU</td><td>V100s</td><td>88.00.98.00.01</td></tr> <tr><td>Nvidia</td><td>PowerEdge 840 Dense</td><td>GPU</td><td>Mi25</td><td>N/A</td></tr> </table><br>
{{< /rawhtml >}}
### Dell Customer Tools
{{< rawhtml >}}
<table> <colgroup><col/><col/><col/></colgroup> <tr><th>Component</th><th>File Name</th><th>Supported Version</th></tr> <tr><td>Dell Customer Toolkit</td><td>AzS_DellEMC_CustomerToolkit_2-2-2210-2.zip</td><td>2-2-2210-2</td></tr> <tr><td>Dell OEM extension package for drivers and firmware updates</td><td>AzS-DellEMC-2.2.2210.2.zip</td><td>2.2.2210.2</td></tr> <tr><td>Dell HLH Rebuild to Windows Server 2019</td><td>HLH_DataDrive_2210_Redeployment_v1_COMP.zip</td><td>2210_v1</td></tr> <tr><td>Dell Patch and Update Automation Tool</td><td>Dell_EMC_Patch_and_Update_Automation_V_2.0.2210.68.exe</td><td>2.0.2210.68</td></tr> <tr><td>Dell Node Expansion scripts</td><td>DELLEMCNodeExpansion_1.19.2210.2.zip</td><td>1.19.2210.2</td></tr> </table><br>
{{< /rawhtml >}}

{{< rawhtml >}}
</div>

</body>

</html>

{{< /rawhtml >}}
