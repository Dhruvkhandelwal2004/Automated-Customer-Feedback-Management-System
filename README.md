AI-Powered Customer Feedback Management System


Overview


This project is an automated Customer Feedback Management System built using n8n.


The workflow simulates how modern organizations manage customer feedback by automating feedback classification, ticket generation, customer communication, team notifications, and complaint tracking.


The system processes customer submissions and automatically routes them to the appropriate workflow based on the feedback type.



 Features


1. Feedback Classification

Automatically classifies customer feedback into:

* Complaint
* Compliment
* Improvement Request



2. Ticket Management

Generates unique tracking IDs for every submission.

Examples:

* CMP-XXXXXXXX
* COM-XXXXXXXX
* IMP-XXXXXXXX



3. Date & Time Tracking

Records submission date and time for:

* Tracking
* Reporting
* Audit purposes



4. Repository Management

Stores feedback in dedicated Google Sheets repositories:

* Complaint Repository
* Compliment Repository
* Improvement Repository



5.  Notifications

Automatically sends Slack notifications to relevant teams.



6. Customer Communication

Automatically sends:

* Complaint Acknowledgement Emails
* Compliment Acknowledgement Emails
* Improvement Request Acknowledgement Emails



7. Complaint Follow-up System

The workflow:

1. Waits for a defined period
2. Checks complaint status
3. Sends appropriate updates



8. Resolution Management

When a complaint is resolved:

* Customer receives resolution notification
* Ticket lifecycle is completed



Workflow Architecture



Customer Feedback Form
          ↓
Feedback Classification Agent
          ↓
Ticket Generation & Timestamp Creation
          ↓
Intelligent Routing
          ↓
Repository Storage
          ↓
Slack Notification
          ↓
Customer Acknowledgement
          ↓
Status Monitoring
          ↓
Follow-up / Resolution Notification




Technology Stack

* n8n
* Google Sheets
* Slack
* Gmail
* JavaScript
* AI Agent




Key Learning Outcomes

* Workflow Automation
* Business Process Design
* Ticket Management
* Customer Experience Operations
* Automated Notifications
* Process Monitoring
* Operational Workflow Development



Future Improvements

* SLA Tracking
* Priority-Based Routing
* Escalation Workflows
* Analytics Dashboard
* CRM Integration
* Multi-Agent Support System



Author : Dhruv Khandelwal

Built as a practical workflow automation project to understand how customer feedback systems operate in real-world organizations.
