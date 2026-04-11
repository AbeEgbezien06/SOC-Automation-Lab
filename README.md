# SOC-Automation-Lab
🚀 Building My SOC Automation Lab (SIEM + SOAR + Case Management)

I recently completed a hands-on cybersecurity project where I built a fully functional SOC (Security Operations Center) automation lab in the cloud. This project allowed me to simulate a real-world security environment, combining monitoring, detection, response, and case management into one workflow.

🧠 Project Overview

The goal of this project was to design and implement a SOC automation pipeline that can:

Detect security threats
Trigger alerts
Automate incident response
Manage cases like a real SOC team

To achieve this, I integrated three major tools:

Wazuh – for threat detection and monitoring
TheHive – for case management
Shuffle – for automation and orchestration

The entire lab was deployed on DigitalOcean using Infrastructure-as-a-Service (IaaS).

⚙️ What I Worked On

This project involved several key stages:

Designing the SOC architecture in a cloud environment
Deploying and configuring security tools (Wazuh & TheHive)
Setting up alert rules for threat detection
Generating attack telemetry (simulating real threats)
Integrating SOAR automation using Shuffle
Automating alert handling and notifications
🔍 How the System Works

Here’s how the entire SOC pipeline operates:

Threat Simulation
I generated telemetry related to Mimikatz, a known credential-dumping tool used by attackers.
Detection (SIEM/XDR)
Wazuh monitors system activity
A custom alert rule detects suspicious behavior linked to Mimikatz
Once detected, an alert is triggered
Automation (SOAR)
The alert is sent to Shuffle
Shuffle automates the response workflow
Case Management
The alert is forwarded to TheHive
A case is automatically created
This allows tracking of incidents, just like in a real SOC team
Notification System
I configured automatic email alerts
Every triggered alert sends detailed information directly to me

👉 The purpose of sending alerts to TheHive is to track incident ownership and response progress, which is exactly how real SOC teams operate.

🛠️ Technologies Used
Cloud Platform: DigitalOcean
SIEM/XDR: Wazuh
Case Management: TheHive
SOAR: Shuffle
Attack Simulation: Mimikatz
⚠️ Challenges I Faced

Like any real-world project, this wasn’t without obstacles:

System Errors
Some services failed to start or behaved unexpectedly during setup
Firewall Misconfigurations
Incorrect network rules initially blocked communication between components
Script Writing Mistakes
Errors in automation scripts caused workflow failures

💡 How I handled them:
I consistently debugged, researched, and tested different solutions until everything worked correctly. This process improved my troubleshooting and problem-solving skills significantly.

🎯 Key Takeaways
Built a realistic SOC environment from scratch
Gained hands-on experience with SIEM, SOAR, and incident response tools
Learned how to detect, automate, and manage security incidents
Strengthened my debugging and system integration skills
