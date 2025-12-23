<h1>🚨 Incident Response Case Studies</h1>

<h2>🎯 Objective</h2>
<p>
The <b>Incident Response Case Studies</b> project was developed to demonstrate a structured
and methodical approach to investigating, analyzing, and documenting security incidents
from a Security Operations Center (SOC) perspective.
</p>
<p>
This repository simulates real-world SOC alert investigations, applies the incident response
lifecycle, and produces clear, professional incident reports. The focus is on analytical
thinking, log correlation, and effective communication of technical findings.
</p>

<hr>

<h2>🧠 Skills Learned</h2>
<ul>
  <li>End-to-end execution of the incident response lifecycle</li>
  <li>SOC alert triage and severity classification</li>
  <li>Deep analysis of endpoint, authentication, and network logs</li>
  <li>Timeline reconstruction and event correlation</li>
  <li>Identification, validation, and enrichment of IOCs</li>
  <li>Root cause analysis and attacker behavior profiling</li>
  <li>MITRE ATT&CK technique mapping</li>
  <li>Clear and structured SOC incident reporting</li>
</ul>

<hr>

<h2>🛠️ Tools Used</h2>
<ul>
  <li><b>SIEM Platform:</b> Splunk (alerting, log analysis, correlation)</li>
  <li><b>Endpoint Telemetry:</b> Windows Security Logs, Sysmon</li>
  <li><b>Network Analysis:</b> Wireshark</li>
  <li><b>Threat Intelligence:</b> OSINT sources (IP/domain reputation)</li>
  <li><b>Frameworks & Standards:</b> MITRE ATT&CK, Incident Response Lifecycle</li>
</ul>

<hr>

<h2>🧪 Steps Performed</h2>

<h3>🔹 Step 1: Alert Detection & Initial Triage</h3>
<ul>
  <li>Alert type</li>
  <li>Severity</li>
  <li>Affected assets</li>
  <li>Potential impact</li>
</ul>
<p><b>Alerts investigated:</b></p>
<ul>
  <li>Suspicious PowerShell execution</li>
  <li>Brute-force login attempts</li>
  <li>Malware beaconing network traffic</li>
</ul>

<h3>🔹 Step 2: Scope Identification & Data Collection</h3>
<ul>
  <li>Impacted hosts and user accounts</li>
  <li>Relevant investigation time window</li>
  <li>Associated data sources</li>
</ul>
<p><b>Logs collected:</b></p>
<ul>
  <li>Windows authentication logs</li>
  <li>Process creation and command-line logs</li>
  <li>Network traffic logs</li>
</ul>


<h3>🔹 Step 3: Detailed Log Analysis</h3>
<ul>
  <li>Authentication attempt analysis</li>
  <li>PowerShell execution and obfuscation review</li>
  <li>Network connection pattern analysis</li>
  <li>Cross-log event correlation</li>
</ul>


<h3>🔹 Step 4: Timeline Construction</h3>
<ul>
  <li>Initial detection time</li>
  <li>Attacker activity sequence</li>
  <li>Persistence or escalation attempts</li>
  <li>End of malicious activity</li>
</ul>


<h3>🔹 Step 5: IOC Identification & Enrichment</h3>
<ul>
  <li>Malicious IP addresses</li>
  <li>Suspicious domains</li>
  <li>File hashes and command-line artifacts</li>
</ul>
<p><b>IOC enrichment:</b></p>
<ul>
  <li>Reputation analysis</li>
  <li>Known malicious activity</li>
  <li>Campaign association</li>
</ul>


<h3>🔹 Step 6: Root Cause Analysis</h3>
<ul>
  <li>Initial access method</li>
  <li>Weak controls or misconfigurations</li>
  <li>Attacker techniques and objectives</li>
</ul>

<h3>🔹 Step 7: Incident Documentation & Reporting</h3>
<ul>
  <li>Incident summary</li>
  <li>Detection details</li>
  <li>Timeline analysis</li>
  <li>Indicators of Compromise</li>
  <li>Impact assessment</li>
  <li>Final verdict (True Positive / False Positive)</li>
  <li>Remediation recommendations</li>
  <li>Lessons learned</li>
</ul>


<hr>

<h2>📌 Included Case Studies</h2>
<ul>
  <li><b>Suspicious PowerShell Execution</b> – T1059.001</li>
  <li><b>Brute-Force Login Attempts</b> – T1110</li>
  <li><b>Malware Beaconing Traffic</b> – T1071</li>
</ul>

<hr>

<h2>📌 MITRE ATT&CK Mapping</h2>
<table>
  <tr>
    <th>Technique</th>
    <th>ID</th>
  </tr>
  <tr>
    <td>Brute Force</td>
    <td>T1110</td>
  </tr>
  <tr>
    <td>PowerShell</td>
    <td>T1059.001</td>
  </tr>
  <tr>
    <td>Command and Control</td>
    <td>T1071</td>
  </tr>
</table>

<hr>

<h2>📊 Outcome</h2>
<ul>
  <li>Investigated multiple simulated SOC alerts</li>
  <li>Improved detection and analysis of malicious behavior</li>
  <li>Strong hands-on SOC documentation experience</li>
  <li>Developed a repeatable SOC investigation methodology</li>
</ul>

<hr>

<h2>🚀 Future Improvements</h2>
<ul>
  <li>Simulate containment and remediation actions</li>
  <li>Integrate automated IOC enrichment using Python</li>
  <li>Add phishing and ransomware incident scenarios</li>
  <li>Expand correlation logic for advanced detection</li>
</ul>

<h2>👤 Author</h2>
<p>
<b>Parvathy Krishnan</b><br>
