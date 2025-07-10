<h1 align="center">🔍 Elastic Stack & Kibana: Endpoint Monitoring and Log Analysis Lab</h1>

<p align="center">
  Practical deployment of Elastic Security using Linux & Windows endpoints with Sysmon and KQL log analysis.
</p>

<h2 align="center">📝 Lab Overview</h2>

<p align="center">
  This lab demonstrates a full <strong>Elastic Stack (ELK)</strong> deployment with <strong>Kibana</strong>, <strong>Sysmon</strong>, and agent-based log collection for cybersecurity monitoring.<br/><br/>
  It includes hands-on experience with Linux and Windows agents, Sysmon event ingestion, integration setup,<br/>
  and advanced querying using <strong>KQL</strong> (Kibana Query Language).<br/><br/>
  The lab concludes with log search filtering, dashboard customization, and session preservation in Kibana Discover.
</p>

<hr/>

<hr/>

<h2>🧪 Lab Process</h2>

<ol>
  <li>
    Setup an Elastic Search ELK security deployment.<br/>
    <img src="screenshots/step1.png" alt="Step 1 Screenshot" width="600"/>
  </li>
  <li>
    Created an agent policy to add agents.<br/>
    <img src="screenshots/step2.png" alt="Step 2 Screenshot" width="600"/>
  </li>
  <li>
    Successfully added a Kali Linux agent.<br/>
    <img src="screenshots/step3.png" alt="Step 3 Screenshot" width="600"/>
  </li>
  <li>
    Added integrations.<br/>
    <img src="screenshots/step4.png" alt="Step 4 Screenshot" width="600"/>
  </li>
  <li>
    Collected and searched logs.<br/>
    <img src="screenshots/step5.png" alt="Step 5 Screenshot" width="600"/>
  </li>
  <li>
    Removed agent, created new policy, and added a Windows 11 agent.<br/>
    <img src="screenshots/step6.png" alt="Step 6 Screenshot" width="600"/>
  </li>
  <li>
    Downloaded and ran Sysmon on the agent.<br/>
    <img src="screenshots/step7.png" alt="Step 7 Screenshot" width="600"/>
  </li>
  <li>
    Added Windows integration on the policy I made for my agent on Kibana. The integration consists of Sysmon operationals, which will collect logs from Sysmon.<br/>
    <img src="screenshots/step8.png" alt="Step 8 Screenshot" width="600"/>
  </li>
  <li>
    Searched logs with specific fields, and it successfully logged the commands I was running on the Windows 11 VM.<br/>
    <img src="screenshots/step9.png" alt="Step 9 Screenshot" width="600"/>
  </li>
  <li>
    Also logged me going on and using Microsoft Edge.<br/>
    <img src="screenshots/step10.png" alt="Step 10 Screenshot" width="600"/>
  </li>
  <li>
    Added a data filter and also used Kibana Query Language (KQL) to filter through the log searches.<br/>
    <img src="screenshots/step11.png" alt="Step 11 Screenshot" width="600"/>
  </li>
  <li>
    Saved the Kibana Discover session to finish it off.<br/>
    <img src="screenshots/step12.png" alt="Step 12 Screenshot" width="600"/>
  </li>
</ol>

<hr/>
