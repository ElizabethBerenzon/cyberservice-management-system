#cyberservice-management-system

Currently under development.Continuously improving business logic and system's structure

Course Project : Information Systems Analysis and Design
CyberService - Cyber Security Services Management System
--
CyberService is an information system designed to manage the business operations of a company providing information security (cyber) services, including customer management, services, workflows, reports, and payments.  
The system enables full management of the cyber service delivery process, starting from the service order, through execution by a consultant, and ending with report generation and payment.

Target Audience
--
The system is designed for companies providing services to small and medium-sized businesses, which usually do not maintain an internal information security department and require external services.  

Project Goals
--
For the Company:
* Streamline and automate business workflows
* Improve control over services and employees
* Centralize business data
* Increase revenue via services and subscriptions
* Optimize resource allocation

For the Client:
--
* Easy and intuitive service ordering
* Full transparency of service progress
* Access to personal dashboard:
    * Service history
    * Reports
    * Status tracking
    * PaymentsGeneral Overview of the Process
--
The system supports a full service management process:  
* Service Ordering: Placed by the customer.  
* Consultant Assignment: Performed by a manager.  
* Execution: Performing the service and updating the status.  
* Reporting: Generating a professional report.  
* Personal Area: Viewing the report in a private portal.  
* Payment: Paying for the service.  
Core Mechanisms and Components
--
The functional components of the system include:  
* User & Permissions Management.  
* Customer Management: Including personal customer files.  
* Service Catalog Management.  
* Orders & Tasks Management.  
* Employee Allocation.  
* Process Status Tracking.  
* Report Generation.  
* Payment System.  
* Notification System.  
* Centralized Database.
* The system supports both one-time services and monthly subscriptions.

Actors
--
* Client – orders services and tracks progress
* Customer Service Representative – supports clients
* Cybersecurity Consultant – performs cybersecurity tasks
* Consultant Team Manager – assigns and manages work
* Finance Manager – handles billing and payments
* System Administrator – manages system access and security
* Company Executive – views business insights and reports

External Systems:
--
* Payment System
* Notification System
* Report Generation System
* Central Database

Key Features (Business-Oriented)
--
* User Authentication & Role-Based Access Control
* Client Profile Management
* Service Catalog & Subscription Management
* Order Management
* Task Assignment & Workload Distribution
* Progress Tracking & Status Updates
* Professional Report Generation
* Payment Processing & Billing
* Notification & Alerts System
* Business Analytics & Reporting
  
Core Business Workflow
--
1. Client registers and logs into the system
2. Client browses and selects a cybersecurity service
3. Client places an order
4. Consultant Team Manager assigns a consultant
5. Consultant performs the service and updates progress
6. System generates a professional report
7. Client reviews/downloads the report
8. Client completes payment
   
Use Case Structure
--

The system includes business-focused Use Cases only, where each action represents an interaction between a user (Actor) and the system.

User & Access Management
--

* Register New Client
* Authenticate User
* Recover Password
* Manage User Roles (Admin only)

Service Management
--

* Browse Service Catalog (Client)
* Manage Services (Admin/Manager)
* Configure Subscriptions

Orders & Task Management
--

* Place Service Order
* Cancel Order
* Assign Consultant (Team Manager)
* Set Task Priority
* Track Service Status (Client)
* Update Work Progress (Consultant)
* Complete Task

Reports
--

* Generate Professional Report
* Review Report (Team Manager)
* Publish Report
* View & Download Reports (Client)

Payments & Billing
--

* Calculate Service Fees
* Process Payment (Client)
* View Payment History
* Issue Receipt
* Manage Subscription Billing
* Process Refund (Finance Manager)

Business Analytics
--

* View Business Reports (Company Executive)
* Analyze Employee Workload
* Service Popularity Analysis
* Export Business Data



Example Use Case: Process Payment (UC034)

Goal
--

Enable a client to securely pay for a cybersecurity service.

Main Flow
--
1. Client views unpaid orders
2. Client selects an order
3. System displays payment options
4. Client enters payment details
5. System validates input
6. Payment is processed via external provider
7. Order is marked as paid
8. Receipt is generated
9. Client receives confirmation

Alternative Flows
--

* Invalid input → user corrects details
* Payment declined → order remains unpaid
* Connection error → payment marked as pending
* User cancels payment

Postconditions
--

* Payment recorded
* Order updated
* Receipt generated
* Transaction stored



System Design Principles
--

* All Use Cases represent user–system interactions
* No internal technical processes are modeled as Use Cases
* Clear separation between:
    * Business roles
    * Technical roles
* Role-Based Access Control (RBAC) enforced



Non-Functional Requirements
--

Security
--

* Encrypted communication (TLS 1.3)
* Secure payment handling
* Audit logging of all actions

Performance
--

* Report generation under 10 seconds

Reliability
--

* 99.9% availability

Usability
--

* Responsive and mobile-friendly interface



Architecture Components
--

* Central Database
* Payment System Integration
* Notification System
* Report Generation System
* RBAC Mechanism


Additional Features
--

* Multi-language support (Hebrew / English)
* Full audit trail
* Subscription-based services
* Clean separation between business and system logic

Project Type
--

Business Analysis & System Design Project

* Use Case Modeling
* Functional Requirements
* Process Thinking
