<h1>Azure Sentinel Map</h1>


<h2>Description</h2>
I set up Azure Sentinel and connected it to a VM acting as a honeypot. PowerShell script was used to look up Geolocation information from login attempts and plot it on a map. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Azure Sentinel</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>

<h2>Proof of Concept:</h2>

<p align="center">
 <b>Powershell script and sample log of failed login attempts:</b> <br/>
<img src="https://i.imgur.com/ik7AGVj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 <b>Parsed sample output into custom fields:</b>  <br/>
<img src="https://i.imgur.com/UOpRfxL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />
<br />
 <b>Map output after 24 hours:</b>  <br/>
<img src="https://i.imgur.com/H7PI70A.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
