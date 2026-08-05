# Research Notes

# 1. Security Operations Center (SOC)?

## What is a Security Operations Center (SOC)?

A Security Operations Centre (SOC) is a team of cybersecurity professionals whose main job is to protect an organisation's computers, networks, and data from cyber threats. They continuously monitor systems, look for unusual activity, investigate alerts, and respond to security incidents before they become bigger problems.

For example, a SOC is like the security control room in a shopping mall or an airport. Security guards monitor CCTV cameras and alarms to ensure everything is safe. If they notice something suspicious, they investigate and take action. In the same way, a SOC watches over an organisation's digital environment instead of a physical building.

## Purpose

A SOC helps reduce the impact of cyberattacks by identifying suspicious activity early. 
Instead of waiting until a hacker causes serious damage, the SOC tries to detect the warning signs and stop the attack before it spreads.

## Responsibilities

The SOC team has several important responsibilities, including:

- Monitoring computers, servers, and networks for unusual or suspicious activity.
- Investigating security alerts to determine whether they are real threats or false alarms.
- Responding to security incidents such as malware infections, phishing attacks, or unauthorised access.
- Collecting and analysing logs from different systems to understand what happened during an incident.
- Reporting security incidents and recommending ways to improve security and prevent similar attacks in the future.
  
These responsibilities help keep the organisation's systems secure and reduce the risk of future attacks.

## Team Structure

Different team members and responsibilities.
**Tier 1 (Level 1) SOC Analyst** is the first person to review security alerts. They monitor systems, investigate basic alerts, and decide whether an issue needs further investigation.
**Tier 2 (Level 2) SOC Analyst** handles more complex incidents. They investigate suspicious activity in greater detail and work to contain security incidents.
**Tier 3 (Level 3) SOC Analyst** is the most experienced technical analyst. They deal with advanced threats, perform deeper investigations, and help improve detection methods.
**SOC Manager** leads the team, assigns work, ensures incidents are handled properly, and helps improve the overall security operations.

## My Understanding

A Security Operations Center is like the central security team for an organisation. Their job is not just to watch for attacks but also to investigate problems, respond quickly, and continuously improve the organisation's security. Without a SOC, it would be much harder for a company to detect cyber threats before they cause serious damage.


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# 2. SIEM

## What is SIEM?

When I first came across the term SIEM, it sounded complicated. After researching it, I learned that SIEM stands for **Security Information and Event Management**. It is a security tool that collects information from different computers, servers, and devices, then helps security teams find suspicious activity.

I think of a SIEM like a control room that receives information from many places at the same time. Instead of checking every computer one by one, a SOC analyst can look at one central dashboard to see what is happening across the whole network.

Without a SIEM, security teams would have to check thousands of logs manually, which would take a lot of time and make it easy to miss important signs of an attack.

---

## Log Collection

A log is simply a record of something that happened on a computer or network. For example, a user logging in, opening a program, or a failed password attempt can all create logs.

A SIEM collects these logs from different sources such as Windows computers, Linux servers, firewalls, antivirus software, and network devices. Instead of keeping the logs on separate systems, the SIEM stores them in one place where they are easier to search and analyse.

---

## Correlation

Collecting logs is only the first step. A SIEM also compares information from different devices to find patterns that may indicate an attack. This process is called **correlation**.

For example, if someone fails to log in several times and then successfully logs in from another computer a few minutes later, the SIEM can connect those events and recognise that something unusual may be happening. Looking at a single log might not seem suspicious, but when several related events are connected, it becomes much more meaningful.

---

## Alerting

When the SIEM detects something suspicious, it creates an alert to notify the security team.

Not every alert means there is an attack, so analysts investigate the alert to decide whether it is a real security issue or just normal activity. The purpose of alerts is to help security teams respond quickly instead of discovering problems much later.

---

## Detection

Detection is the process of identifying possible security threats by analysing the collected logs and alerts.

For example, a SIEM may detect repeated failed login attempts, malware activity, or someone trying to access files they should not have permission to use. Once a threat is detected, the SOC team investigates and decides what action to take.

---

## My Understanding

After researching SIEM, I understand that it is one of the most important tools used in a Security Operations Center. It saves time by collecting logs into one place, helps analysts connect related events, creates alerts when something looks suspicious, and supports the detection of cyber threats. I think of it as the "eyes and ears" of a SOC because it helps security teams see what is happening across an organisation's systems.




