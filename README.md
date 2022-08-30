<h1>Log File Cleaner Automation with Powershell</h1>



<h2>Description</h2>
This is a simple Powershell automation script that automates the cleanup of log files older than a certain date via a scheduled task.
A csv file is created to specify the log locations and the number of days before the log cleaner runs and for different files.This is to
help prevent log files locations from filling up with log files from applications and services.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Windows Task Scheduler</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Specify Directory list in a csv file: <br/>
<<img src="https://imgur.com/LaALQhC.png" height="80%" width="80%"/>
<br />
<br />
Create a Scheduled Task: <br/>
<img src="https://imgur.com/koplAV5.png" height="80%" width="80%"/>
<br />
<br />
Set Trigger Time and Run:  <br/>
<img src="https://imgur.com/bSDc3C3.png" height="80%" width="80%"/>
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
