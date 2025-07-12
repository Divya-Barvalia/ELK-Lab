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
  </li>
  <li>
    Created an agent policy to add Linux agents, and added integrations into the policy for monitoring.<br/>
    <img src="Screenshots/Linux-AgentPolicy.png" width="600"/>
  </li>
  <li>
    Successfully added a Kali Linux agent.<br/>
    <img src="Screenshots/Linux-Agent-Command.png" width="400"/><img src="Screenshots/Kali-Agent.png" width="800"/><img src="Screenshots/KaliOnFleet.png" width="800"/>
  </li>
  <li>
    Collected and searched logs.<br/>
    <img src="Screenshots/LinuxAgentLogs.png" width="800"/>
  </li>
  <li>
    Removed agent, created new policy, and added a Windows 11 agent.<br/>
    <img src="Screenshots/AgentPolicy2.png" width="800"/><img src="Screenshots/Win-Agent-NewPolicy.png" width="800"/>
  </li>
  <li>
    Downloaded and ran Sysmon on the agent.<br/>
    <img src="Screenshots/SysmonInstall-WinAgent.png" width="600"/>
  </li>
  <li>
    Added Windows integration on the policy I made for my Windows agent on Kibana. The integration consists of Sysmon operationals, which will collect logs from Sysmon.<br/>
  </li>
  <li>
    Searched logs with specific fields, and it successfully logged the commands I was running on the Windows 11 VM.<br/>
    <img src="Screenshots/CommandsRan-WinAgent.png" width="600"/><img src="Screenshots/Win-Logs.png" width="1000"/>
  </li>
  <li>
    Added a data filter and also used Kibana Query Language (KQL) to filter through the log searches.<br/>
    <img src="Screenshots/Data-Filter.png" width="800"/><img src="Screenshots/Results.png" width="800"/>
  </li>
  <li>
    Saved the Kibana Discover session to finish it off.<br/>
  </li>
</ol>

<hr/>
