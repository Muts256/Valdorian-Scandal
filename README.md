<h1>Hi, I'm Michael! <br/><a href="https://www.linkedin.com/in/michael-musoke/">Cybersecurity Professional</a></h1>

<h2>👨‍💻 Sentinel Configuration, Investigations & KQL Labs</h2>

- <b> Kusto Query Language </b>
  - [KQL Investigation](https://github.com/Muts256/Valdorian-Scandal/blob/main/Valdorian%20Times%20Investigation.pdf)

Investigation into a data breach at a reputable Newspaper. On the eve of the election, Nene Leaks, the esteemed editor of The Valdorian Times, awoke to a nightmare. The Valdorian Times, the beacon of truth for the city, published a scandalous article accusing Luffy of corruption and misconduct. The article, a vile concoction of lies, was not what she had approved. 

The Valdorian Times has hired you as a cyber incident responder to investigate the incident and determine how the falsified article was published.

Summary:
  - Investigate what happened, indicate a timeline, who was involved, and what could have been done to prevent the incident.
  - Detect anomalies/unusual behaviour in the logs using KQL.
  - Report writing describing the breach.
  - Provide recommendations on how to avoid breaches in the future.

Tools and Technologies
  - Kusto Query Language (KQL)
  - MITRE ATT&CK framework

Investigation: 
  - Interview the employees to gather information.
  - Interrogate the log tables to discover what they contain.
  - Detect the devices that may have been used in the breach.
  - Build a timeline of the breach.
  - Write a report including recommendations.

Some techniques the perpetrators used can be traced back to the MITRE ATT&CK framework. These include 

MITRE ATT&CK:
  - T1566 Phishing: Phishing Email: Phishing emails are categorised under Initial Access because they are used to gain the first foothold into an environment.
  - T1041 – Exfiltration Over C2 (Command and Control) Data was stolen from an employee's device.
  - T1033 – System Owner Discovery. Commands like whoami were used to identify the username and privilege level.
  - T1082 - System Information Discovery Commands like hostname used to identify the system infromation


Lessons Learned:
  - Exploring data quickly – Using Table Name | take 10 is a fast way to inspect table structures and understand what kind of data is available.
  - Filtering and correlating events – Queries like where IP == "10.10.0.65" or filtering by distinct helped me narrow down relevant events efficiently.
  - Timeline reconstruction – Sorting and combining logs allowed me to see the sequence of attacker actions, showing how they moved through the network.
  - Identifying patterns – Using KQL operators like count or distinct helped detect repeated suspicious activities across multiple users and IPs.
  - Report writing, describing the investigation.
  - Hands-on confidence – Building queries from scratch reinforced my understanding of how to investigate breaches in a SIEM environment, preparing me for real-world scenarios.

  [PDF](https://github.com/Muts256/Valdorian-Scandal/blob/main/Valdorian%20Times%20Investigation.pdf)

<h2> 🤳 Connect with me:</h2>

[<img align="left" alt="michael-musoke | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]

[linkedin]: https://linkedin.com/in/michael-musoke
