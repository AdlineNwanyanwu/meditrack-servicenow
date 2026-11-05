# 🏥 MediTrack — Medical Equipment Management System

### A ServiceNow Custom Application

**Project Type:** ServiceNow RiseUp Capstone Project  
**Team:** Langston Team | Group 2  
**Team Size:** 5 Members  
**My Roles:** Project Manager & Repair Request Lead  
**Platform:** ServiceNow  
**Status:** In Development

---

## 📌 Project Overview

MediTrack is a collaborative ServiceNow application designed to streamline medical equipment management within healthcare organizations.

The application focuses on equipment tracking, repair request management, preventive maintenance, and workflow automation.

MediTrack aims to provide a centralized platform where healthcare staff can report equipment issues, technical teams can coordinate repairs, and department managers can monitor maintenance activities.

## 🎯 Problem Statement

Healthcare organizations depend on medical equipment to deliver safe and efficient patient care.

When equipment maintenance processes rely on disconnected systems or manual communication, organizations may experience:

- Delayed equipment repairs
- Limited visibility into equipment status
- Inefficient repair request routing
- Missed preventive maintenance activities
- Difficulty tracking maintenance history

MediTrack is designed to address these challenges through centralized tracking and automated workflows.

## 🚀 Project Objectives

- Centralize medical equipment information
- Streamline equipment repair requests
- Support preventive maintenance scheduling
- Automate task assignments and notifications
- Implement role-based access controls
- Improve visibility through reports and dashboards
- Support efficient communication between departments

## 🛠️ Technologies & Tools

- ServiceNow Platform
- App Engine Studio
- ServiceNow Studio
- Flow Designer
- Service Catalog
- Access Control Lists (ACLs)
- Business Rules and Client Scripts
- Reports and Dashboards
- GitHub for Project Documentation

## 🏗️ Application Architecture

The planned application consists of four core tables.

| Table | Purpose |
|-------|---------|
| Equipment | Stores medical equipment information |
| Repair Request | Tracks reported equipment issues |
| Maintenance Schedule | Supports preventive maintenance |
| Work Order | Tracks assigned repair and maintenance work |

### Planned Data Relationships

- Equipment records can be associated with repair requests.
- Equipment records can have maintenance schedules.
- Repair requests can generate related work orders.
- Work orders can be assigned to technical teams.

## 👥 User Roles & Assignment Groups

### User Roles

- Reporter (Nurse/Clinician)
- Biomedical Engineer
- Facilities Technician
- Department Manager
- Administrator

### Assignment Groups

- Biomedical Engineering
- Facilities
- IT Support

Role-based access controls are planned to help ensure users can access the appropriate records and functionality.

## 🔄 Core Workflows

### 1. Equipment Repair Request

The planned repair process follows these stages:

1. Healthcare staff reports faulty equipment.
2. A repair request is created.
3. The request is reviewed and prioritized.
4. The request is assigned to the appropriate team.
5. The assigned technician performs the repair.
6. Equipment is tested and verified.
7. The repair request is closed.

### 2. Preventive Maintenance

The planned preventive maintenance process includes:

1. Register equipment maintenance requirements.
2. Define maintenance schedules.
3. Identify upcoming maintenance activities.
4. Generate reminders or maintenance tasks.
5. Assign maintenance work.
6. Record maintenance completion.

## 👩🏽‍💻 My Contributions

### Project Manager

As Project Manager for the five-member team, my responsibilities include:

- Coordinating project planning
- Defining project scope and objectives
- Organizing team responsibilities
- Tracking project milestones and deliverables
- Facilitating team communication
- Supporting integration and testing activities
- Coordinating final project documentation and presentation

### Repair Request Lead

I am also responsible for the Repair Request component.

My responsibilities include:

- Designing the Repair Request table
- Defining fields and data requirements
- Configuring forms and list views
- Developing the repair submission catalog item
- Supporting functional testing
- Documenting the repair request process

These responsibilities combine technical application development with project coordination and stakeholder-focused process design.

## 📊 Planned Reporting & Dashboards

MediTrack aims to provide visibility into:

- Equipment by operational status
- Repair requests by priority
- Open and completed repair requests
- Repair requests by department
- Average repair resolution time
- Preventive maintenance compliance

## 🔐 Security & Access Control

Planned security features include:

- Role-based access control
- Table-level and field-level ACLs
- Controlled access to repair requests
- Appropriate permissions for technicians and managers
- Administrative access for application maintenance

## 🧪 Testing Strategy

The project testing approach includes:

- Table and field validation
- Form and list configuration testing
- Catalog item submission testing
- Workflow execution testing
- Role-based access testing
- Repair request lifecycle testing
- User acceptance testing

Testing results will be documented as implementation progresses.

## 📂 Project Documentation

This repository will progressively include:

- Project requirements and scope
- Data model and table documentation
- Repair request configuration
- Workflow diagrams
- Security configurations
- Testing results
- Application screenshots
- Project management deliverables

## 📈 Project Status

**In Development**

This README describes the project's intended design and my assigned responsibilities. Implemented features, testing outcomes, and screenshots will be added as they are completed and verified.

## 🎓 Learning Outcomes

Through MediTrack, I am developing experience in:

- ServiceNow custom application development
- Data modeling and table configuration
- ITSM workflow design
- Service Catalog configuration
- Role-based security
- Testing and troubleshooting
- Agile-style team coordination
- Technical documentation
- Project management

## 👩🏽‍💻 Project Contributor

**Adline Nwanyanwu**  
Project Manager | Repair Request Lead  
ServiceNow RiseUp Program

[LinkedIn](https://www.linkedin.com/in/adline-nwanyanwu)

---

*Building practical ServiceNow solutions that connect healthcare operations, technology, and process improvement.*
