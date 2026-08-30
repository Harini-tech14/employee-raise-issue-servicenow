# Employee Raise Issue – ServiceNow

## Record Producer & Service Portal Integration

A ServiceNow-based Employee Issue Management solution that provides employees with a simple and structured way to raise workplace-related issues through the Employee Center portal.

## 📌 Project Overview

The Employee Raise Issue project is developed using ServiceNow to provide a centralized platform for employees to submit workplace-related issues.

The solution allows employees to:

- Access the Employee Center portal
- Open the Raise Employee Issue form
- Enter issue details
- Select a Category and relevant Subcategory
- Submit the issue
- Store the submitted information in a custom Employee Raise Issue table

## 🎯 Problem Statement

Employees may raise workplace-related issues through emails or informal communication channels. This can lead to:

- Lack of standardized data collection
- Delays in issue resolution
- Limited visibility into issue status
- Manual effort for HR and support teams
- Inconsistent issue categorization
- Difficulty in tracking employee requests

This project provides a centralized and structured ServiceNow-based solution for raising and managing employee issues.

## 🎯 Objectives

- Create a custom scoped ServiceNow application
- Create an Employee Raise Issue custom table
- Configure required fields
- Implement UI Policies
- Configure Category–Subcategory dependency
- Create a Record Producer
- Create and configure an Employee Center portal
- Develop custom Service Portal widgets
- Integrate the Record Producer with the portal
- Test the complete end-to-end workflow

## 🛠️ Technologies & ServiceNow Components

| Component | Purpose |
|---|---|
| ServiceNow PDI | Development and testing |
| ServiceNow Studio | Scoped application development |
| Custom Application | Contains the Employee Raise Issue solution |
| Custom Table | Stores submitted employee issues |
| UI Policies | Controls field behavior and validation |
| Field Dependency | Implements Category–Subcategory dependency |
| Record Producer | Provides the issue submission form |
| Employee Center | Employee-facing portal |
| Service Portal Designer | Portal page configuration |
| Service Portal Widgets | Customized portal functionality |
| HTML & CSS | Widget design and styling |
| Client Script | Widget navigation and actions |
| Reference Fields | Links users and assignment groups |

## 🏗️ Implementation Phases

### Phase 1 – Creating a Custom Application
Created the scoped ServiceNow application for the Employee Raise Issue solution.

### Phase 2 – Creating Custom Table and Fields
Created the Employee Raise Issue custom table and configured fields such as Requester, Category, Subcategory, State, Priority, and Assignment Group.

### Phase 3 – Creating UI Policies and Dependency
Configured UI Policies, field restrictions, and Category–Subcategory dependency.

### Phase 4 – Creating a Record Producer
Created the Raise Employee Issue Record Producer and configured the required variables and field mappings.

### Phase 5 – Creating the Service Portal
Configured the Employee Center portal and homepage for employee access.

### Phase 6 – Creating Custom Widgets
Created and configured custom Service Portal widgets and added them to the Employee Center homepage.

### Phase 7 – Testing and Validation
Tested the complete workflow from accessing the portal to verifying the backend record creation.

### Phase 8 – Conclusion
Successfully implemented and validated the Employee Raise Issue solution in ServiceNow.

## 🔄 End-to-End Workflow

Employee Center  
↓  
Raise Employee Issue  
↓  
Enter Requester and Issue Details  
↓  
Select Category  
↓  
Select Relevant Subcategory  
↓  
Submit Issue  
↓  
Record Created in Employee Raise Issue Table

## ✅ Testing

The following major scenarios were validated:

- Employee Center portal loading
- Raise Employee Issue form access
- Requester selection
- Category selection
- Subcategory dependency
- Issue description entry
- Issue submission
- Backend record creation

All major functional components were successfully validated.

## 📄 Project Documentation

Detailed project documentation, configuration steps, implementation screenshots, and testing details are available in:

**[EMPLOYEE RAISE ISSUE - HARINI N.pdf](./EMPLOYEE%20RAISE%20ISSUE%20-%20HARINI%20N.pdf)**

## 👩‍💻 Author

**Harini N**

B.Tech Information Technology  
K. Ramakrishnan College of Technology  
Academic Year: 2026–2027
