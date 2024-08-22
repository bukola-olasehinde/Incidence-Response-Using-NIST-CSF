# Incidence-Response-Using-NIST-CSF
<h2>Scenario:</h2>
<p>You are a cybersecurity analyst at a multimedia company that provides social media marketing, graphic design, web design services to small businesses. Recently, your organization suffered a DDoS attack that disrupted the internal network for two hours before it was resolved.</p>

<p>During the attack, your organization’s network services abruptly ceased functioning due to a surge of incoming ICMP packets. This flood of traffic prevented normal internal network operations from accessing any network resources. In response, the incident management team blocked the incoming ICMP packets, took all non-essential network services offline, and restored the critical network services.</p>

<p>The company’s cybersecurity team subsequently investigated the security incident and discovered that a malicious actor had exploited an unconfigured firewall to send a flood of ICMP pings into the network. This vulnerability enabled the attacker to launch a distributed denial of service (DDoS) attack, thereby overwhelming the company’s network.</p>
<p>To resolve this security incident, the network security team implemented:</p>
<ul>
  <li>A new firewall rule to restrict the rate of incoming ICMP packets</li>

<li>Source IP address verification on the firewall to detect spoofed IP addresses in incoming ICMP packets</li>

  <li>Network monitoring software to identify unusual traffic patterns</li>

  <li>An IDS/IPS system to filter ICMP traffic based on suspicious attributes</li>
  </ul>

<p>As a cybersecurity analyst, your task is to use this security incident to develop a plan for enhancing your company’s network security, in accordance with the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). You will leverage the CSF to guide your analysis of the incident and incorporate your findings into a comprehensive security strategy.:</p>

<ul>
  <li>Identify security risks by conducting regular audits of internal networks, devices, acess privileges and systems to uncover potential security gaps.</li>

<li>Protect internal assets by implementing policies, procedures, training, and tools designed to mitigate cybersecurity threats.</li>

<li>Detect potential security incidents and improve monitoring capabilities to increase the speed and efficiency of detections.</li>

<li>Respond with proper procedures to contain, neutralize and analyze security incidents and implement improvements to the security process.</li>

<li>Recover affected systems back to normal operation and restore systems data and assets that have been affected by an incident.</li>
  </ul>
  
<h3>Solution</h3>




  <b>Step 1: Identification of attack type and systems affected</b>
<p>
  
  Type of attack: ICMP flood attack.<br>
 
 Since the DDoS attack that disrupted the organization’s network services was caused by a flood of incoming ICMP packets, the type of denial-of-service attack was an ICMP flood attack. The only system impacted was the organization's internal network.</p> </p>
</p>

<b>Step 2: Protection of assets from compromise</b>
<p>
  <ul>
    <li>A new firewall rule should be established to control the rate of incoming ICMP packets.</li>
    <li>Source IP address verification should be implemented on the firewall to detect spoofed IP addresses in incoming ICMP packets.</li>
    <li>Install network monitoring software to identify unusual traffic patterns.</li>
    <li>An IDS/IPS system should be deployed to filter ICMP traffic based on suspicious characteristics.</li>
  </ul>
  The DDoS attack that disrupted the organization’s network services was caused by a flood of incoming ICMP packets, therefore it is classified as an ICMP flood attack. The sole system impacted was the organization's internal network. </p>
</p>

<b>Step 3 (How to detect similar incidents in the future):</b>
<p>
  By implementing all measures listed in <b>Step 2,</b> incident detection will be a lot easier since the firewalls and IPS/IDS systems would continuously monitor network traffic on network devices to check for suspicious activity, such as incoming external ICMP packets from non-trusted IP addresses attempting to pass through the organization’s network firewall. 
</p>

<b>Step 4 (Creating a response plan for future cybersecurity incidents):</b>
<p>
  After identifying the tools and methods put in place for detecting potential vulnerabilities and threats, there is need to create a response plan in the event of a future incident. This can be carried out by creating an updated security playbook so everyone on the team will understand how to go about incident response in the event of a future incident.
</p>

<b>Step 5 (Recovering from the incident):</b>
<p>
  All pending organizational services and internal or external delivery errors should be fixed and forwarded to intended recipients immediately after the incident has been resolved. With a firewall rule configured to limit the rate of incoming ICMP packets in the organization's internal network, there is minimal possibility of encountering an ICMP flood attack within the organization's network.
</p>
