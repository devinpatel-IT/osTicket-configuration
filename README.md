# osTicket-configuration
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- osTicket (Enterprise Ticketing System Platform)
- Microsoft Azure (Virtual Machines)
- Remote Desktop
- Internet Information Services (IIS)


<h2>Operating Systems Used </h2>

- Windows 10 Pro</b> ()

<h2>Post-Install Configuration Objectives</h2>

- Establish different roles in system with various permission levels
- Add departments
- Implement teams 
- Add atleast two real users and agents 


<h2>Configuration Steps</h2>

_<b>1. ROLE BASED ACCESS PERMISSIONS CONFIGURATION</b>_

<p>
<img <img width="1041" height="501" alt="Screenshot 2025-08-05 164305" src="https://github.com/user-attachments/assets/d41fb3c1-7035-4c2f-846d-c4d92bb57cd5" />

</p>

<p>
Role-based access control configured – Demonstrates roles with distinct permissions applied within the ticketing system. This will be very useful when assigning permissions to different users and groups.
</p>
<br />

_<b>2. ESTABLISHED TICKETING SYSTEM DEPARTMENTS (explanation below)</b>_

<p>
<img width="1109" height="402" alt="Screenshot 2025-08-05 164248" src="https://github.com/user-attachments/assets/f6c201f1-ebd7-4228-9323-d6014c327c2b" />

</p>
<p>

_<strong>1. Support Department</span></strong>_


Primary Role: Acts as the first point of contact for end-users. Handles general user inquiries, basic troubleshooting, and routine support requests.

Ticket Tier Coverage:

Tier 1 (Level 1):

Password resets

Account access issues

Basic software/application guidance

FAQs and how-to requests

Tier 2 (Level 2) (limited):

Escalated issues that require moderate technical knowledge

Troubleshooting known system issues using documented procedures

_<strong>2. System Administrators</span></strong>_

Primary Role: Manages back-end systems and infrastructure. Handles advanced technical issues, system configuration, security, and escalated tickets from the Support Department.

Ticket Tier Coverage:

Tier 2 (Level 2):

Configuration changes

Internal system diagnostics

Network or server-level issues

Tier 3 (Level 3):

Complex incidents requiring code/database access

Security breaches or system failures

Root cause analysis and permanent fixe
</p>
<br />

_<b>2. ESTABLISHED TEAMS (explanation below)</b>_

<p>
<img width="1112" height="421" alt="Screenshot 2025-08-05 164236" src="https://github.com/user-attachments/assets/89db05df-6540-4a28-921d-03485a471e2c" />
</p>

_<strong>1. Level 1 suppport team</span></strong>_

<p>
Purpose:
The Level 1 Support Team acts as the first line of defense for all incoming support tickets. They handle common issues, provide general assistance, and triage requests before escalation.

Key Responsibilities:
Receive and respond to initial customer inquiries or issues.

Perform basic troubleshooting for banking services (e.g., login issues, account access problems).

Categorize, prioritize, and document tickets clearly.

Resolve low-complexity issues or known problems using standard procedures.

Escalate complex or specialized cases to the appropriate teams (e.g., Online Banking Team, IT, or Level 2 support).

Monitor open tickets to ensure timely responses and customer satisfaction.

Ticket Examples:
Password reset requests

Unable to access mobile/online banking

Incorrect account balances displayed

Help navigating the banking portal

_<strong>2. Online Banking Team</span></strong>_

Purpose:
The Online Banking Team is a specialized technical group that manages and supports issues specifically related to the bank’s online banking platform. They are responsible for maintaining a secure, functional, and reliable user experience across the digital banking ecosystem.

Key Responsibilities:
Handle tickets escalated from Level 1 involving online banking functionality.

Investigate and resolve platform-specific bugs or outages.

Support backend operations of mobile apps, internet banking, and digital account services.

Coordinate with developers, cybersecurity teams, and infrastructure teams as needed.

Test and validate fixes for reported issues before deployment.

Provide feedback and documentation to help the Level 1 team better resolve recurring issues.

Ticket Examples:
Failed funds transfer through online banking

Online bill payment issues

Errors during account registration via the website/app

MFA (multi-factor authentication) not functioning properly

Security concerns or suspicious online activity

Workflow Summary
Customers submit tickets through web/app/phone.

Level 1 Support Team triages and resolves simple/general issues.

Tickets requiring technical investigation or platform expertise are escalated to the Online Banking Team.


</p>
<br />
