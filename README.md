# osTicket-configuration
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
As an IT professional, I created this ticketing system project to simulate how technical support teams handle, track, and prioritize user requests in a structured and efficient way. The goal was to build a centralized solution that mirrors real-world helpdesk operations, improving visibility, accountability, and response times for IT issues.

<br>
<p>This project demonstrates my understanding of:

IT service management (ITSM) workflows

User support processes

Database and web application fundamentals

Automation and escalation logic

By building this from the ground up, I showcased both technical and operational skills — from designing the backend structure to implementing features like ticket categories, status tracking, and role-based access. It reflects my ability to support users not just technically, but through scalable, organized systems that align with industry support models.</p>


<h2>Environments and Technologies Used</h2>

- osTicket (Enterprise Ticketing System Platform)
- Microsoft Azure (Virtual Machines)
- Remote Desktop
- Internet Information Services (IIS)


<h2>Operating Systems Used </h2>

- Windows 10 Pro</b> ()

<h2>Post-Install Configuration Objectives</h2>

- Establish different roles in the system with various permission levels
- Add departments
- Implement teams 
- Add at least two real users and agents 


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

Root cause analysis and permanent fix
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

Incorrect account balances are displayed

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

MFA (multi-factor authentication) is not functioning properly

Security concerns or suspicious online activity

Workflow Summary
Customers submit tickets through web/app/phone.

Level 1 Support Team triages and resolves simple/general issues.

Tickets requiring technical investigation or platform expertise are escalated to the Online Banking Team.


</p>
<br />

_<b>2. CREATE SAMPLE USERS </b>_

<img width="1110" height="476" alt="Screenshot 2025-08-05 164357" src="https://github.com/user-attachments/assets/bcfbd1ec-abc7-44b7-b913-0bd391e78434" />

<p>These are employees who will submit tickets to the help desk</p>

<br/> 

_<b>2. CREATE SAMPLE AGENTS </b>_

<img width="1137" height="479" alt="Screenshot 2025-08-05 164224" src="https://github.com/user-attachments/assets/383d3034-3ddd-4ac7-a9b1-c92af8ec6845" />

<p>These are help desk employees that will triage tickets</p>

<br/>

Please continue to the next repository to view the ticketing system lifecycle.
[osTicket Lifecycle](https://github.com/devinpatel-osTicket-lifecycle) 


