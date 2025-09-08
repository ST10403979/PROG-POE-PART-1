# PROG-POE-PART-1
Contract Monthly Claim System - Prototype
Project Overview
The Contract Monthly Claim System is a WPF (.NET Core) application designed to streamline the process of submitting, reviewing, and approving monthly claims for contract lecturers at educational institutions. This prototype focuses on establishing a user-friendly interface and workflow without backend functionality at this stage.

Key Features:

Role-based access (Lecturers, Programme Coordinators, Academic Managers)

Intuitive claim submission with document upload capability

Transparent approval workflow with status tracking

Clean, professional interface designed for academic environments

Technology Stack
Frontend: WPF (.NET Core 6.0)

Architecture: MVVM (Model-View-ViewModel) pattern

Version Control: Git with GitHub

Documentation: Microsoft Word, UML diagrams

Project Structure
text
ContractClaimSystem/
├── Models/
│   ├── User.cs
│   ├── Claim.cs
│   ├── Document.cs
│   └── ApprovalHistory.cs
├── Views/
│   ├── LoginView.xaml
│   ├── DashboardView.xaml
│   ├── ClaimSubmissionView.xaml
│   ├── ApprovalView.xaml
│   └── StatusTrackingView.xaml
├── ViewModels/
│   ├── LoginViewModel.cs
│   ├── DashboardViewModel.cs
│   ├── ClaimSubmissionViewModel.cs
│   └── ApprovalViewModel.cs
├── Resources/
│   └── Images/
├── Documentation/
│   ├── UML_Diagram.png
│   └── Project_Report.docx
└── ContractClaimSystem.sln
Installation and Setup
Prerequisites
Visual Studio 2022 with .NET Desktop Development workload

.NET 6.0 SDK or later

Git for version control

Getting Started
Clone the repository:

bash
git clone https://github.com/yourusername/ContractClaimSystem-POE.git
cd ContractClaimSystem-POE
Open the solution in Visual Studio:

Launch Visual Studio 2022

Select "Open a project or solution"

Navigate to the project directory and open ContractClaimSystem.sln

Build the solution:

In Visual Studio, go to Build > Build Solution (Ctrl+Shift+B)

Ensure there are no build errors

Run the application:

Press F5 or go to Debug > Start Debugging

Usage Guide
For Lecturers
Login: Select "Lecturer" role and enter your credentials

Dashboard: Access options to submit new claims or view existing ones

Submit Claim:

Select month and year

Enter hours worked

Upload supporting documents

Submit for approval

Track Status: View the progress of your claims through the approval process

For Programme Coordinators
Login: Select "Programme Coordinator" role

Dashboard: View pending claims requiring your attention

Review Claims:

Examine claim details and supporting documents

Approve or reject with comments

Forward to Academic Manager when appropriate

For Academic Managers
Login: Select "Academic Manager" role

Dashboard: Review claims approved by coordinators

Final Approval:

Make final approval decisions

View complete approval history

Monitor claim status across the institution

Development Timeline
Day	Focus Area	Key Tasks
1	Setup & Requirements	Project initialization, environment setup, GitHub repository
2	Database Design	UML class diagram, initial documentation
3	Login & Dashboard	Role-based authentication UI, dashboard layouts
4	Claim Submission	Form design, document upload interface
5	Approval Workflow	Approval interface, status tracking visualization
6	Integration & Polish	UI consistency, navigation, styling refinement
7	Documentation	Final report, testing, submission preparation
Version Control History
This project follows a structured commit history with five descriptive commits:

"Project setup and initial documentation"

Solution structure creation

README initialization

Requirements analysis documentation

"Database design and documentation"

UML class diagram implementation

Design rationale documentation

Assumptions and constraints outline

"Login and dashboard UI implementation"

Login interface with role selection

Role-specific dashboard layouts

Navigation framework

"Claim submission UI components"

Claim form with month/year selection

Hours input field with validation indicators

Document upload interface

"Approval workflow UI components"

Approval interface for coordinators/managers

Status tracking visualization

Final UI polish and integration

Design Decisions
UI/UX Approach
Consistency: Standardized button sizes, spacing, and typography throughout

Intuitiveness: Designed for minimal learning curve with clear navigation paths

Accessibility: Color choices consider contrast requirements and color blindness

Feedback: Visual indicators for all user actions

Architectural Patterns
MVVM Pattern: Separation of concerns for maintainability and testability

Role-Based Access: Clear separation of functionality based on user roles

Modular Design: Components are independent and reusable

Database Design
The UML class diagram includes four main entities:

User: Stores information about lecturers, coordinators, and managers

Claim: Contains claim details including hours, dates, and status

Document: Manages supporting documents attached to claims

ApprovalHistory: Tracks the complete approval workflow for audit purposes

Assumptions and Constraints
Assumptions
Users have basic computer literacy

Supporting documents are in standard formats (PDF, DOC, DOCX, JPEG, PNG)

Internet connectivity is available for GitHub version control

Screen resolution is at least 1024x768 pixels

Constraints
Non-functional prototype: No backend logic or data persistence

Word count limit: Documentation limited to 400-500 words

Time constraint: 7-day development timeline

Version control: Minimum of 5 commits with descriptive messages

Testing
Although this is a non-functional prototype, the following aspects have been validated:

Navigation: All screens connect properly with correct workflow

Layout: UI elements display correctly at different resolutions

Usability: Intuitive flow with clear action paths

Consistency: Uniform styling across all screens

Future Enhancements
When moving to a functional implementation, consider:

Database Integration: Connect to a SQL Server database

Authentication: Implement secure login functionality

File Handling: Add actual document upload/download capability

Notifications: Email alerts for claim status changes

Reporting: Generate claim history and financial reports

Mobile Access: Responsive design for mobile devices

Contributing
As this is a academic project, contributions are not currently being accepted. However, the development approach followed can serve as a reference for similar projects.

License
This project was created for academic purposes as part of a Portfolio of Evidence (POE) assignment. All rights reserved by the educational institution.

Contact
For questions about this prototype, please contact Me.

