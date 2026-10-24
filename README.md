# University Admission Management System using Salesforce

## 📌 Project Overview

The **University Admission Management System** is a Salesforce-based application designed to simplify and manage the overseas university admission process. It centralizes student records, university and course details, admission applications, supporting documents, payments, counselor assignments, and admission decisions in one platform.

## 🎯 Problem Statement

Managing overseas university admissions involves handling multiple student applications, documents, payments, university details, and counselor reviews. When these activities are managed separately, tracking application progress and maintaining accurate records becomes difficult.

## 💡 Proposed Solution

This project uses Salesforce CRM to connect admission-related activities through custom objects, record relationships, and centralized dashboards. Administrators manage student applications and payments, assign counselors after payment, and track document verification and admission decisions. Counselors review applications, communicate acceptance or rejection decisions to students through email, and record outcomes in counselor reports.

## ✨ Key Features

- **Student Management:** Create and maintain student records.
- **University Management:** Store and manage university information.
- **Course Management:** Maintain course details associated with universities.
- **Admission Application Tracking:** Manage multiple applications for students across universities and courses.
- **Document Management:** Track application documents and verification status.
- **Payment Tracking:** Record payment amounts, dates, types, and statuses.
- **Counselor Assignment:** Assign counselors to applications after payment.
- **Document Verification:** Enable counselors to review submitted documents and student details.
- **Admission Decision Management:** Record acceptance or rejection decisions and communicate outcomes through email.
- **Reports and Dashboards:** Monitor applications, course selections, payments, and counselor workload.

## 🛠️ Technologies Used

- Salesforce CRM
- Salesforce Custom Objects and Fields
- Salesforce Tabs
- Page Layouts and Compact Layouts
- Lightning App Builder
- Salesforce Reports and Dashboards
- Salesforce Email Communication

## 🗂️ Salesforce Components

The project includes the following metadata components:

| Component | Count |
|---|---:|
| Custom Objects | 8 |
| Custom Fields | 78 |
| Custom Tabs | 8 |
| Page Layouts | 16 |
| Compact Layouts | 16 |
| Lightning Record Pages | 1 |
| Dashboard Components | 4 |

### Custom Objects

1. Student
2. Admission Application
3. Application Document
4. Payment
5. Counselor Assignment
6. Counselor Report
7. University
8. Course

## 🔄 Admission Workflow

1. **Student Registration:** The administrator creates and maintains student records.
2. **Application Submission:** Applications are associated with the relevant student, university, and course. Students can have multiple applications.
3. **Document Submission:** Supporting documents are recorded against each application.
4. **Payment Processing:** Payment details and payment status are recorded.
5. **Counselor Assignment:** After payment, the administrator assigns a counselor to the application.
6. **Document Verification:** The counselor reviews the submitted documents and student information.
7. **Admission Decision:** The counselor communicates the acceptance or rejection decision to the student through email.
8. **Counselor Reporting:** The counselor records the verified application and its decision in the Counselor Report.

## 📊 Reports and Dashboards

The project includes reports and dashboard components to support admission monitoring and decision-making.

- **University-Counselor Report:** Summarizes application records by university and counselor.
- **Applications by University:** Displays application counts for each university.
- **Course Selection by Students:** Shows application and course records grouped by course.
- **Application by Course Report:** Tracks application counts across courses and universities.
- **Counselor Workload Report:** Displays records assigned to each counselor.
- **Payments by Status:** Summarizes payment records by status.

## 🧪 Testing and Validation

The main admission workflow is validated through the following scenarios:

- Create a student record with all required information.
- Link an admission application to the correct student, university, and course.
- Create application document records and update their status.
- Record payment details and verify their association with the relevant application and student.
- Assign a counselor to an admission application.
- Record an admission decision and create a counselor report.
- Verify that application information can be monitored through reports.

## ✅ Project Outcomes

- Centralized student and admission application information.
- Organized tracking of application documents and payments.
- Clear counselor assignment and document verification processes.
- Recorded admission decisions and student communication.
- Improved visibility into applications, course selections, payment status, and counselor workload.

## 🚀 Future Enhancements

- Automate additional admission-processing activities using Salesforce Flow.
- Introduce a student self-service portal for application tracking.
- Implement automated application-status notifications.
- Enhance dashboards for admission trends and performance analysis.

## 👨‍💻 Project Information

**Project Name:** University Admission Management System  
**Platform:** Salesforce CRM  
**Domain:** Education Technology and Overseas Admissions  
**Project Type:** Salesforce Administration and Application Management

**My Role:** Product Owner

**Responsibilities:** Contributing to project planning, defining requirements, coordinating team activities, and supporting the delivery of the admission management solution.

## 📝 Conclusion

The University Admission Management System demonstrates how Salesforce can streamline overseas university admissions through connected records, structured application tracking, counselor coordination, payment monitoring, and centralized reporting. It provides an organized approach to managing the admission journey from student registration to the final admission decision.
