Mini cyber drill is an exercise to train ability in the role of a SOC analyst
*(just like a real case)*.

On this occasion, i will share my experience worked on this exercise.
I will share the case scenario, the work i performed, and the steps taken, along with mitigation measures and recommendation.

## Case Scenario

You’ve just joined PT Nusantara Digital, a technology company
in Jakarta, as a SOC Analyst. PT Nusantara Digital has an IT infrastructure consisting of several
servers and workstations connected to the internet via a Palo Alto firewall.
On Monday morning (April 7, 2026), the SOC Manager informed you that there were several alerts from
the IDS (Intrusion Detection System) that needed to be investigated. Additionally, there was a report from HR that
an employee in the finance department received a suspicious email on the same day.
You are asked to conduct a thorough investigation using Splunk SIEM. The available logs
cover a 3-day period: April 7–9, 2026. Determine whether a security incident occurred, reconstruct
the chronology of the attack, identify all IOCs (Indicators of Compromise), and provide recommendations
for a response.

## Available log sources

- Firewall
- DNS
- IDS
- Windows
- Sysmon
- Linux
- Web

## Hostname, IP Address & Role

- FW-EDGE-01 | 203.0.113.1 / 10.10.0.1 | Edge Firewall
- WEB-SERVER-01 | 10.10.1.10 | Web Server (DMZ)
- WS-FINANCE-01 | 10.10.2.50 | Finance Workstation
- WS-HR-02 | 10.10.2.51 | HR Workstation
- DC-01 | 10.10.3.10 | Domain Controller
- DB-SERVER-01 | 10.10.3.20 | Database Server 

Next to the steps for process [here!](https://github.com/sarahwuzz/SOC-Training-Project/blob/main/Mini%20Cyber%20Drill-Investigation.md)
