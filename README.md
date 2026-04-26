#cyberservice-management-system


![UML](https://img.shields.io/badge/UML-Diagrams-blue?style=for-the-badge)
![System Design](https://img.shields.io/badge/System-Design-green?style=for-the-badge)
![Business Analysis](https://img.shields.io/badge/Business-Analysis-orange?style=for-the-badge)


![Use Case](https://img.shields.io/badge/Use%20Case-Diagram-purple?style=for-the-badge)
![PlantUML](https://img.shields.io/badge/PlantUML-Modeling-red?style=for-the-badge)


Currently under development.Continuously improving business logic and system's structure.
# The goal of this project is to apply the knowledge acquired in information system structure and design, as well as to leverage AI tools to support system analysis, modeling, and documentation processes.

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
      
The system supports a full service management process:
-- 
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

Register New Client
* Primary Actor: System Administrator
* Supporting Actors: Central Database, Notification System

User Authentication
* Primary Actor: User (Any Role)
* Supporting Actors: Central Database

Role-Based Access Control
* Primary Actor: System Administrator
* Supporting Actors: Central Database

Password Recovery
* Primary Actor: User (Any Role)
* Supporting Actors: Notification System, Central Database

Update Client Profile
* Primary Actor: Client
* Supporting Actors: Central Database

Deactivate Account
* Primary Actor: System Administrator
* Supporting Actors: Central Database

Audit User Activity (View Logs)
* Primary Actor: System Administrator
* Supporting Actors: Central Database


Service Management
--

Browse Service Catalog
* Primary Actor: Client
* Supporting Actors: Central Database

Add New Service
* Primary Actor: System Administrator / Manager
* Supporting Actors: Central Database

Configure Monthly Subscriptions
* Primary Actor: System Administrator
* Supporting Actors: Central Database

Select Service Model
* Primary Actor: Client
* Supporting Actors: Central Database

Update Pricing
* Primary Actor: Finance Manager
* Supporting Actors: Central Database

Archive Service
* Primary Actor: System Administrator
* Supporting Actors: Central Database

Orders & Task Management
--

Place Service Order
* Primary Actor: Client
* Supporting Actors: Central Database

Cancel Order
* Primary Actor: Client
* Supporting Actors: Central Database, Notification System

View Active Orders
* Primary Actor: Consultant Team Manager
* Supporting Actors: Central Database

Assign Consultant
* Primary Actor: Consultant Team Manager
* Supporting Actors: Central Database, Notification System

Reassign Task
* Primary Actor: Consultant Team Manager
* Supporting Actors: Central Database

Set Task Priority
* Primary Actor: Consultant Team Manager
* Supporting Actors: Central Database

Track Process Status
* Primary Actor: Client
* Supporting Actors: Central Database

Accept Assignment
* Primary Actor: Cybersecurity Consultant
* Supporting Actors: Central Database

Update Work Progress
* Primary Actor: Cybersecurity Consultant
* Supporting Actors: Central Database

Log Technical Findings
* Primary Actor: Cybersecurity Consultant
* Supporting Actors: Central Database

Upload Supporting Documents
* Primary Actor: Cybersecurity Consultant
* Supporting Actors: Central Database

Track Time Spent
* Primary Actor: Cybersecurity Consultant
* Supporting Actors: Central Database

Complete Task
* Primary Actor: Cybersecurity Consultant
* Supporting Actors: Central Database

Reports
--

Generate Professional Report
* Primary Actor: Cybersecurity Consultant
* Supporting Actors: Report Generation System, Central Database

Review Report
* Primary Actor: Consultant Team Manager
* Supporting Actors: Central Database

Publish Report
* Primary Actor: Cybersecurity Consultant
* Supporting Actors: Notification System, Central Database

View Service History
* Primary Actor: Client
* Supporting Actors: Central Database

Download PDF Report
* Primary Actor: Client
* Supporting Actors: Central Database

Notify Report Readiness
* Primary Actor: Notification System
* Supporting Actors: Client

Payments & Billing
--

Calculate Service Fees
* Primary Actor: Finance Manager
* Supporting Actors: Central Database

Process Payment
* Primary Actor: Client
* Supporting Actors: Payment System, Central Database

Manage Subscription Billing
* Primary Actor: Finance Manager
* Supporting Actors: Payment System, Central Database

View Payment History
* Primary Actor: Client
* Supporting Actors: Central Database

Issue Receipt
* Primary Actor: Payment System
* Supporting Actors: Client, Central Database

Manual Invoicing
* Primary Actor: Finance Manager
* Supporting Actors: Central Database

Process Refund
* Primary Actor: Finance Manager
* Supporting Actors: Payment System, Central Database


Analytics & Management
--

View Business Reports
Primary Actor: Company Executive
Supporting Actors: Central Database

Analyze Employee Workload
Primary Actor: Consultant Team Manager
Supporting Actors: Central Database

Quality Control
Primary Actor: Consultant Team Manager
Supporting Actors: Central Database

Service Popularity Statistics
Primary Actor: Company Executive
Supporting Actors: Central Database

Export Business Data
Primary Actor: Company Executive
Supporting Actors: Central Database

Example Use Case: Process Payment (UC034)
--

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

The next Step is to create Use Case Diagram, using AI tools to create the correct code on PlantUML.
```
@startuml
left to right direction
skinparam packageStyle rectangle

' ===== Primary Actors (LEFT) =====
actor Client
actor "Customer Service Representative" as CSR
actor "Cybersecurity Consultant" as Consultant
actor "Consultant Team Manager" as Manager
actor "Finance Manager" as Finance
actor "System Administrator" as Admin
actor "Company Executive" as Executive

' ===== Supporting Actors (RIGHT) =====
actor "Payment System" as Payment
actor "Notification System" as Notification
actor "Report System" as ReportSystem

' ===== General Actor =====
actor User
User <|-- Client
User <|-- Consultant
User <|-- Manager
User <|-- Finance

' ===== System =====
rectangle CyberService {

  ' Authentication
  usecase "Register Client" as UC1
  usecase "Login" as UC2
  usecase "Recover Password" as UC3

  ' Services
  usecase "Browse Services" as UC4
  usecase "Select Service" as UC5
  usecase "Manage Services" as UC6

  ' Orders
  usecase "Place Order" as UC7
  usecase "Cancel Order" as UC8
  usecase "Track Status" as UC9

  ' Task Management
  usecase "Assign Consultant" as UC10
  usecase "Update Progress" as UC11
  usecase "Complete Task" as UC12

  ' Reports
  usecase "Generate Report" as UC13
  usecase "Review Report" as UC14
  usecase "Publish Report" as UC15
  usecase "Download Report" as UC16

  ' Payments
  usecase "Process Payment" as UC17
  usecase "Calculate Fees" as UC18
  usecase "Issue Receipt" as UC19
  usecase "Refund Payment" as UC20

  ' Analytics
  usecase "View Business Reports" as UC21
  usecase "Analyze Workload" as UC22
}

' ===== Connections (Primary Actors → System) =====

Client --> UC4
Client --> UC5
Client --> UC7
Client --> UC8
Client --> UC9
Client --> UC16
Client --> UC17

Consultant --> UC11
Consultant --> UC12
Consultant --> UC13

Manager --> UC10
Manager --> UC14
Manager --> UC22

Finance --> UC18
Finance --> UC20

Executive --> UC21

Admin --> UC1
Admin --> UC6

' ===== Supporting Actors (RIGHT SIDE CONNECTIONS) =====

UC17 --> Payment
UC19 --> Payment
UC20 --> Payment

UC15 --> Notification
UC8 --> Notification

UC13 --> ReportSystem

' ===== INCLUDE =====
UC7 --> UC5 : <<include>>
UC17 --> UC18 : <<include>>
UC17 --> UC19 : <<include>>
UC13 --> UC11 : <<include>>

' ===== EXTEND =====
UC8 ..> UC7 : <<extend>>
UC20 ..> UC17 : <<extend>>
UC3 ..> UC2 : <<extend>>

' ===== GENERALIZATION =====
usecase "Manage Orders" as UCO
UCO <|-- UC7
UCO <|-- UC8

usecase "Manage Payments" as UCP
UCP <|-- UC17
UCP <|-- UC20

@enduml
```
On the diagram the primary actors should be located on the left side and external support systems on the right side.


Use Case Relationships
--
include – used for actions that always happen as part of a process  
extend – used for actions that happen only in specific situations  

These relationships make the system behavior clearer and more structured.

<img width="499" height="608" alt="Снимок экрана 2026-04-26 в 08 16 38" src="https://github.com/user-attachments/assets/da9d060e-a8de-4e13-ad05-1311080f5292" />
