# Research Notes

# 1. Security Operations Center (SOC)?

## What is a Security Operations Center (SOC)?

A Security Operations Centre (SOC) is a team of cybersecurity professionals whose main job is to protect an organisation's computers, networks, and data from cyber threats. 

They continuously monitor systems, look for unusual activity, investigate alerts, and respond to security incidents before they become bigger problems.

For example, a SOC is like the security control room in a shopping mall or an airport. Security guards monitor CCTV cameras and alarms to ensure everything is safe. 

If they notice something suspicious, they investigate and take action. In the same way, a SOC watches over an organisation's digital environment instead of a physical building.

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

SIEM stands for **Security Information and Event Management**. 

It is a security tool that collects information from different computers, servers, and devices, then helps security teams find suspicious activity.

SIEM is like a control room that receives information from many places at the same time. Instead of checking every computer one by one, a SOC analyst can look at one central dashboard to see what is happening across the whole network.

Without a SIEM, security teams would have to check thousands of logs manually, which would take a lot of time and make it easy to miss important signs of an attack.

## Log Collection

A log is simply a record of something that happened on a computer or network. 

For example, a user logging in, opening a program, or a failed password attempt can all create logs.

SIEM collects these logs from different sources such as Windows computers, Linux servers, firewalls, antivirus software, and network devices. Instead of keeping the logs on separate systems, the SIEM stores them in one place where they are easier to search and analyse.

## Correlation

Collecting logs is only the first step. SIEM also compares information from different devices to find patterns that may indicate an attack. This process is called **correlation**.

For example, if someone fails to log in several times and then successfully logs in from another computer a few minutes later, the SIEM can connect those events and recognise that something unusual may be happening. Looking at a single log might not seem suspicious, but when several related events are connected, it becomes much more meaningful.

## Alerting

When the SIEM detects something suspicious, it creates an alert to notify the security team.

Not every alert means there is an attack, so analysts investigate the alert to decide whether it is a real security issue or just normal activity. The purpose of alerts is to help security teams respond quickly instead of discovering problems much later.

## Detection

Detection is the process of identifying possible security threats by analysing the collected logs and alerts.

For example, SIEM may detect repeated failed login attempts, malware activity, or someone trying to access files they should not have permission to use. Once a threat is detected, the SOC team investigates and decides what action to take.

## My Understanding

SIEM is one of the most important tools used in a Security Operations Center.

It saves time by collecting logs into one place, helps analysts connect related events, creates alerts when something looks suspicious, and supports the detection of cyber threats. 

It's the "eyes and ears" of a SOC because it helps security teams see what is happening across an organisation's systems.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# 3. Blue Team vs Red Team

## What are Blue Team and Red Team?

Blue Team and Red Team are two different cybersecurity teams with different roles but the same goal: improving security.

The **Blue Team** is responsible for defending an organisation's systems. They monitor networks, investigate alerts, respond to incidents, and work to prevent attacks.

The **Red Team** acts like an attacker. Their job is to test the organisation's security by trying to find weaknesses before real hackers do. They perform controlled attacks and then report what they discovered so the Blue Team can improve the organisation's security.

For example, a football team during training. The attackers (Red Team) try to score goals, while the defenders (Blue Team) try to stop them. Both teams work together to make the whole team stronger.

## Objectives

The main objective of the **Blue Team** is to protect systems, detect threats, and respond to security incidents as quickly as possible.

The main objective of the **Red Team** is to identify security weaknesses by safely simulating real cyberattacks. Their goal is not to cause damage but to help improve security before a real attacker finds those weaknesses.

## Skills

A Blue Team member needs skills such as monitoring security alerts, analysing logs, investigating incidents, understanding Windows and Linux systems, networking, and using security tools like SIEM.

A Red Team member needs skills such as ethical hacking, penetration testing, vulnerability assessment, scripting, and understanding how attackers think and operate.

Although the skills are different, both teams need a good understanding of computers, networking, and cybersecurity.

## Responsibilities

The Blue Team is responsible for monitoring systems, investigating suspicious activity, responding to incidents, updating security controls, and helping prevent future attacks.

The Red Team is responsible for testing security by performing authorised attacks, identifying vulnerabilities, writing reports, and recommending ways to improve security.

Both teams share information so security can continuously improve.

## Career Paths

Someone interested in the Blue Team may become a SOC Analyst, Incident Responder, Digital Forensics Analyst, Threat Hunter, or Security Engineer.

Someone interested in the Red Team may become a Penetration Tester, Ethical Hacker, Red Team Operator, or Security Consultant.

## My Understanding

Blue Team and Red Team work together to improve an organisation's security. The Blue Team focuses on defence, while the Red Team focuses on testing security by thinking like an attacker. Learning Blue Team skills first will help me understand how organisations defend themselves before learning how attackers operate.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# 4. Virtual Machines

## What is a Virtual Machine?

VM is like having another computer running inside a real computer. It has its own operating system, files, and settings, but it uses my computer's hardware to run.

For example, It's like having a practice room inside my house. I can experiment, make mistakes, and learn without affecting the rest of the house.

## Isolation

One of the biggest advantages of a virtual machine is isolation. This means the virtual machine is separated from my real computer.

If something goes wrong inside the VM, such as installing the wrong software or changing important settings, my main computer is usually not affected. This makes it much safer to learn and experiment.

## Safe Testing

Cybersecurity often involves testing new software, security tools, or system configurations. Doing this on my personal computer could cause problems if something does not work as expected.

Using a virtual machine allows me to test these things in a safe environment. If I make a mistake, I can simply delete the VM or restore it without affecting my real computer.

## Malware Analysis

Studying malware to understand how it works and how to defend against it. 

Virtual machine provides a safer place to analyse suspicious files because it is isolated from the main operating system. Although extra precautions are still needed, using a VM reduces the risk of infecting my personal computer.

## Snapshots

A snapshot is like saving the current state of the virtual machine.

If I make changes that cause problems, I can restore the snapshot and return the VM to the exact state it was in before. I think of a snapshot like a save point in a video game. If something goes wrong, I don't have to start again from the beginning.

## Lab Environment

Virtual machines make it possible to build a complete cybersecurity lab on one physical computer.

For example, I can create multiple virtual machines, such as Windows 11, Windows Server, Ubuntu Linux, or security tools like Wazuh, and connect them together to practise different cybersecurity scenarios.

This allows me to gain practical experience without needing several physical computers.

## My Understanding

Virtual machines are so important in cybersecurity. They provide a safe place to learn, practise, and experiment without putting my real computer at risk.
