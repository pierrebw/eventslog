<h1>Track Windows Events Log using Splunk</h1>


<h2>Description</h2>
Set up a system to track and analyze Windows Event Logs using Splunk. I configured it to collect logs from my VM in one place, created easy-to-read reports and dashboards to monitor important security events.
<br />


<h2>Tools Used</h2>

- <b>Parallels</b> 
- <b>Splunk</b> 

<h2>Program walk-through:</h2>

<p align="center">
Started the Universal Forwarder and confirmed the forwarder is active.<br/>
<img src="https://i.imgur.com/fq7Kiw6.png" height="80%" width="80%"/>
<br />
<br />
Internal logs from my VM are coming in Splunk.<br/>
<img src="https://i.imgur.com/nd0sozV.png" height="80%" width="80%"/>
<br />
<br />
I intentionally tried to log into my virtual machine with the wrong password to confirm that an incorrect password attempt would be recorded in the logs.<br/>
<img src="https://i.imgur.com/CT1FBEx.png" height="80%" width="80%"/>
<br />
<br />
Here configured the inputs.conf to reflect index changes.<br/>
<img src="https://i.imgur.com/ARMMGUM.png" height="80%" width="80%"/>
<br />
