# Security Information and Event Management (SIEM)

The following research was conducted in 2022, focusing on Security Information and Event Management (SIEM) and its processes. The aim was to comprehend the fundamental concepts of this specific cybersecurity management process.

## SIEM Process

**Step 1. Collection of Data from Various Sources** 
Collection of data through multiple mediums such as network devices, servers, domain controllers etc. 

**Step 2. Normalise and aggregate collected data** 
With the data collected, we would be able to process and aggregate the collected data for the purpose of analysing data and detecting threats.

**Step 3. Analyse the data to discover and detect threats**
Through the cleaning of the data, we can identify potential threats.

**Step 4. Pinpoint Security Breaches and Enable Organizations to Investigate Alerts**
When we identify a potential threat, we will be able to pinpoint which areas where the vulnerability was found  and  investigate such alerts to keep our organisation safe.

## Research Materials 

Initially, the landscape of IT security tools was limited, featuring essentials like perimeter firewalls alongside intrusion detection systems (IDSs) and antivirus solutions (AVSs) for host monitoring. Each tool boasted its own unique vendor-specific interface. However, with the increasing adoption and proliferation of these tools, two distinct challenges emerged:

           1. There were too many user interfaces to manage, and 
           2. There were no tools to correlate events across different security tools.

SIEM systems aggregate events from various sources, each potentially using a vendor-specific schema, normalise these disparate schemas into a unified representation, and then store these normalised events. Their rule engine triggers alerts based on stored events, enabling correlation of events from different sensors. Additionally, SIEM systems incorporate supplementary contextual information, such as real-time data on enterprise assets, to craft more informed, context-aware rules and prioritise alerts.

The primary strength of SIEM systems lies in their capability to cross-reference logs from diverse sources using shared attributes to delineate significant attack patterns and scenarios. When these patterns occur, they promptly alert security analysts (SAs). Thus, SIEM systems function akin to radar, swiftly detecting potential threats. Furthermore, their capacity for long-term event retention proves invaluable for retrospective forensic analysis and uncovering slow or stealthy attacks, including advanced persistent threats (APTs) (Bhatt et al., 2014).

## References 
Bhatt, S., Manadhata, P. K., & Zomlot, L. (2014). The operational role of security information and event management systems. IEEE Security & Privacy, 12(5), 35–41. https://doi.org/10.1109/msp.2014.103

