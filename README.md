# Personalized Healthcare Assistant

A software engineering project for a **Personalized Healthcare Assistant** that helps patients manage health records, medication schedules, appointment reminders, AI-based health insights, emergency alerts, and doctor–patient communication in one integrated platform.

## Project Overview

Many patients, especially elderly people and patients with chronic illnesses, struggle to manage scattered medical records, medicine schedules, doctor appointments, lab reports, and follow-up instructions. Missing medication or appointments can worsen health conditions and create communication gaps between patients, doctors, and caregivers.

This project proposes a smart, secure, and user-friendly healthcare assistant that centralizes patient information and provides reminders, alerts, AI-driven health suggestions, and remote monitoring support.

## Main Objectives

- Store and manage digital patient health records securely.
- Send medicine reminders through notifications, SMS, or email.
- Support appointment booking, rescheduling, and reminders.
- Provide AI-based health insights and early risk warnings.
- Enable doctor, patient, and caregiver communication.
- Support emergency alerts with health summary and location details.
- Improve patient safety, treatment adherence, and healthcare accessibility.

## Key Features

### Patient Management
- User registration and login
- Profile management
- Medical history timeline
- Health records upload and categorization
- Health dashboard with visual trends

### Medication and Treatment
- Custom medicine schedule
- Medication reminder
- Refill alert
- Dosage form management
- Treatment plan tracking
- Drug conflict warning

### Appointment and Doctor Services
- Doctor search and filtering
- Specialist doctor booking
- Online and in-person appointment scheduling
- Doctor ratings and reviews
- Follow-up reminders
- Doctor queue management

### AI Health Intelligence
- AI-based health risk alerts
- Personalized health plans
- AI chatbot for basic health support
- AI-generated doctor summaries
- Health habit and lifestyle analysis
- Mental health mood check-in support

### Emergency and Caregiver Support
- SOS emergency alert
- Emergency contact notification
- Caregiver monitoring panel
- Wearable-triggered emergency alerts
- Access logs for privacy control

### Additional Services
- Pharmacy service integration
- Buy medicine feature
- Test booking
- Test result management
- Medical image viewer
- Health calendar
- Personal health journal
- Nutritionist support
- Device integration with wearables

## Proposed System Architecture

The system follows a modular client-server architecture.

```text
Users
 ├── Patients
 ├── Doctors
 ├── Caregivers
 └── Admins

Frontend
 ├── Web Application
 └── Mobile Application

Backend Services
 ├── Authentication Service
 ├── Health Record Service
 ├── Appointment Service
 ├── Medication Reminder Service
 ├── Notification Service
 ├── Communication Service
 ├── Emergency Alert Service
 └── Admin Service

AI Module
 ├── Health Risk Prediction
 ├── Chatbot
 ├── Personalized Health Suggestions
 └── Doctor Summary Generator

Database and Storage
 ├── Encrypted Health Records
 ├── User Profiles
 ├── Appointment Data
 ├── Medication Logs
 └── Audit Logs
```

## Suggested Technology Stack

| Layer | Suggested Technologies |
|---|---|
| Frontend | React, React Native, Flutter |
| Backend | Node.js, Django, Express.js |
| Database | Firebase, MongoDB, AWS DynamoDB, PostgreSQL |
| AI/ML | Python, Scikit-learn, TensorFlow/PyTorch |
| Authentication | OAuth 2.0, JWT, Multi-Factor Authentication |
| Cloud | AWS, Firebase, Google Cloud |
| Notifications | SMS, Email, Push Notification |
| Security | HTTPS, AES-256 Encryption, Role-Based Access Control |

## Software Development Model

The project uses the **Agile Software Development Model** because the system contains multiple modules and may require frequent updates based on feedback from patients, doctors, caregivers, and stakeholders.

### Agile Workflow

1. Requirements gathering
2. Sprint planning
3. UI/UX design
4. Module-based development
5. Sprint testing
6. Sprint review and demo
7. Retrospective and improvement
8. Deployment and maintenance

Agile is suitable for this project because it supports flexibility, continuous feedback, incremental delivery, and risk reduction.

## Core Modules

- Authentication Module
- Health Records Module
- Medication Reminder Module
- Appointment Scheduler
- Doctor Interaction Module
- AI Health Intelligence Module
- Emergency Alert Module
- Caregiver Integration Module
- Notification Module
- Pharmacy and Medicine Purchase Module
- Test Booking and Test Result Module
- Health Dashboard Module
- Admin Panel

## Functional Requirements Summary

The system includes major functional requirements such as:

- User registration and secure login
- Medicine schedule creation
- Appointment booking
- Doctor search and specialist consultation
- Health record upload and version control
- AI health risk alerts
- Emergency SOS system
- Secure doctor–patient communication
- Caregiver permission management
- Wearable device integration
- Test booking and result management
- Health calendar and reminders
- Medical expense tracking
- Multi-language support
- Integration with external health services where allowed

## Non-Functional Requirements Summary

The system focuses on:

- Security and privacy of health data
- High availability and reliability
- Fast response time
- Accessibility for elderly and disabled users
- Scalability for many users
- Data backup and recovery
- Real-time notifications
- Encrypted communication
- Role-based access control
- Compliance with healthcare data protection standards

## Testing Approach

The project follows a **Black Box Testing** approach. Testing is performed from the user's perspective to verify that the system works correctly without checking the internal code.

### Testing Areas

- User registration and login
- Medicine reminder
- Appointment booking
- Health record upload
- Specialist doctor booking
- Device integration
- Accessibility
- Legal and privacy controls
- Mental health support
- Test booking
- Test result management
- Medical history timeline
- Health dashboard

### Testing Goals

- Verify that all major features work properly.
- Check system security and privacy.
- Ensure good usability across devices.
- Detect bugs before deployment.
- Validate system behavior under real-life healthcare scenarios.

## Project Management

The report includes project management planning such as:

- Work Breakdown Structure (WBS)
- Timeline chart
- Gantt chart
- COCOMO effort estimation
- Earned Value Analysis (EVA)
- Risk Management and Mitigation Plan

### COCOMO Summary

| Metric | Value |
|---|---|
| Estimated Size | 21,400 SLOC |
| Project Type | Organic |
| Estimated Effort | 59.86 person-months |
| Estimated Development Time | 11.84 months |
| Estimated Staffing | 5 persons |

### EVA Summary

| Metric | Value |
|---|---|
| BAC | 300 person-days |
| BCWP | 73.5 |
| BCWS | 104.5 |
| ACWP | 78 |
| SPI | 0.7033 |
| CPI | 0.9423 |
| Schedule Variance | -31 person-days |
| Cost Variance | -4.5 person-days |

## Risk Management

Important risks considered in this project include:

- Security breaches
- Performance bottlenecks
- Backup failure
- Emergency alert delay
- Communication failure
- Third-party API delay
- Incorrect AI health advice
- Inaccessible or confusing UI
- Unauthorized data access
- Device integration failure
- Regulatory and privacy issues

Mitigation strategies include encryption, multi-factor authentication, cloud backup, fallback alert channels, modular design, usability testing, monitoring, and Agile sprint reviews.

## UI/UX Pages

The proposed UI/UX design includes:

- Home Page
- Sign-Up Page
- Login Page
- Profile Page
- Dashboard
- Appointment Booking Page
- Payment Page
- Confirmation Page
- Notifications Page

## Team Members

This project was prepared as an academic software engineering project by a five-member group from the Department of Computer Science, American International University-Bangladesh.

| Name | Contribution |
|---|---|
| Abdullah Al Tasnim Mahim | Project planning, requirements, UI/UX, testing, WBS, timeline, risk analysis |
| Md. Arshad Islam | Background, Agile model, requirements, sequence diagram, testing, risk analysis |
| Mahamodol Hasan Taj | Proposed solution, project management, requirements, class diagram, test plan, COCOMO |
| Md. Omar Faruk | Target group, process model, requirements, use case diagram, EVA, risk analysis |
| Omar Faruq Mirdha | Existing solutions, design specification, requirements, case study, testing, risk analysis |

## Academic Information

- **Institution:** American International University-Bangladesh (AIUB)
- **Department:** Computer Science
- **Faculty:** Faculty of Science & Technology
- **Course Type:** Software Engineering Project
- **Semester:** Fall 2024–2025
- **Section:** M
- **Group:** 5

## Future Improvements

- Develop a working mobile application prototype.
- Connect the system with real wearable devices.
- Improve AI prediction accuracy using validated medical datasets.
- Add stronger privacy compliance features.
- Integrate with pharmacy, hospital, and national health systems.
- Improve multilingual and accessibility support.
- Conduct real user testing with patients, doctors, and caregivers.

## Disclaimer

This project is an academic software engineering design and planning project. It is not a certified medical product and should not be used as a replacement for professional medical advice, diagnosis, or treatment.

## License

This repository is intended for academic and learning purposes.
