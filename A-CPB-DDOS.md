DDoS Attack Incident Response Playbook

Date: 2025/9/16

Author: Darson Lai

1\. Preparation

Preventive Controls

• Subscribe to a DDoS mitigation service (e.g., Cloudflare, Akamai, AWS
Shield).

• Configure firewalls, load balancers, and intrusion prevention systems
with rate‑limiting and anomaly detection (SonicWall).

• Establish redundant network paths and use CDNs for traffic
distribution.

Readiness

• Maintain updated contact lists for ISPs, hosting providers, and
mitigation vendors.

• Define escalation paths and communication templates.

• Conduct tabletop exercises simulating DDoS scenarios.

2\. Detection & Analysis

Indicators

• Sudden spikes in inbound traffic or bandwidth saturation.

• Legitimate services becoming slow or unreachable.

• Logs showing repeated requests from many IPs or malformed packets.

Actions

• Confirm whether the traffic surge is malicious or legitimate (e.g.,
product launch vs. attack).

• Identify the attack type:

• Volumetric (UDP floods, amplification).

• Protocol (SYN floods, fragmented packets).

• Application layer (HTTP GET/POST floods).

• Collect packet captures and NetFlow data for forensic analysis.

3\. Containment

Immediate Mitigation

• Redirect traffic through a scrubbing center or DDoS mitigation
provider.

• Apply temporary ACLs, geo‑blocking, or rate‑limiting rules.

• Enable Web Application Firewall (WAF) protections for
application‑layer attacks.

• Application-layer activity also monitored via L7.

Internal Coordination

• Notify IT, SOC, and management teams.

• Activate the incident bridge for real‑time coordination.

4\. Eradication

• Remove temporary firewall rules once the attack subsides.

• Patch and harden exposed services that were targeted.

• Update SonicWall IPS signatures and WAF rules to block similar attack
vectors.

• Maintained via vendor.

5\. Recovery

• Gradually restore normal traffic flow.

• Monitor for secondary or follow‑up attacks.

• Validate service availability with synthetic monitoring and user
feedback.

• Communicate restoration status to stakeholders and customers.

6\. Post‑Incident Activities

Lessons Learned

• Document the timeline, attack vectors, and mitigation effectiveness.

• Review gaps in monitoring, escalation, or vendor response.

Improvements

• Update the playbook with new detection rules and response steps.

• Strengthen contracts with ISPs/mitigation vendors if needed.

• Train staff on updated procedures.

7\. Communication Plan

Internal:

• Keep executives, IT, and security teams informed with regular updates.

External:

• Notify ISP/mitigation provider immediately.

• If customer‑facing, issue a factual status update via website or
social channels.

Law Enforcement: For large or repeated attacks, consider reporting to
national CERT or law enforcement agencies.
