
# MediTrack — Repair Request Table Configuration

## Project Information

**Application:** MediTrack  
**Platform:** ServiceNow  
**Module:** Repair Request Management  
**Role:** Repair Request Lead (Member 2)  
**Team:** Langston Team — Group 2

## 1. Overview

The Repair Request table supports the reporting, assignment, tracking, and resolution of faulty medical equipment requests.

As Repair Request Lead, my technical work focuses on configuring and validating this component within the MediTrack application.

## 2. Table Configuration

| Property | Value |
|----------|-------|
| Table Label | Repair Request |
| Table Name | x_1234_meditrack_repair_request |
| Application | MediTrack |
| Extends Table | Task |
| Dictionary Entries | 83 |

## 3. Table Inheritance

The Repair Request table extends the ServiceNow Task table.

This enables the application to reuse standard task-management functionality, including:

- Task numbering
- Assignment management
- Priority and urgency
- State tracking
- Work notes and comments
- Record lifecycle tracking

Extending Task reduces duplication and supports consistent task-management behavior.

## 4. MediTrack-Specific Fields

The following fields are visible in the Repair Request table configuration.

| Field | Type | Reference |
|-------|------|-----------|
| Department | Choice | — |
| Equipment Record | Reference | Medical Equipment |
| Medical Equipment | Choice | — |
| Repair Notes | Journal Input | — |
| Reported By | Reference | User |
| Reported Date | Date/Time | — |
| Resolution Notes | String | — |
| Resolved At | Date/Time | — |
| Resolved By | Reference | User |

## 5. Equipment Relationship

The Equipment Record field references the Medical Equipment table.

This relationship allows repair requests to be associated with equipment records.

It supports equipment-based repair tracking and provides a foundation for assignment automation.

## 6. Assignment and Priority

The table includes standard Task fields such as:

- Assigned to
- Assignment group
- Impact
- Urgency
- Priority
- State

These fields support repair request prioritization, routing, and lifecycle management.

## 7. Business Logic Testing

Five functional test cases were completed successfully:

| Test ID | Functionality | Result |
|---------|---------------|--------|
| BR-001 | Automatic Priority Calculation | PASS |
| BR-002 | Equipment-Based Auto Assignment | PASS |
| BR-003 | Closure Validation | PASS |
| BR-004 | Automatic Resolution Tracking | PASS |
| BR-005 | Repair Request Lifecycle | PASS |

See [Business Rule Testing](business-rule-testing.md) for detailed results.

## 8. Access Control Configuration

The Repair Request table displays five access control records.

Visible operations include:

- Create
- Read
- Write
- Delete

An additional create access control is also present.

Further validation is required to document role requirements, rule conditions, and effective permissions.

## 9. Technical Skills Demonstrated

- ServiceNow Custom Table Configuration
- Task Table Inheritance
- Dictionary Configuration
- Reference Fields
- Data Modeling
- Assignment Management
- Business Rule Testing
- Record Lifecycle Validation
- Technical Documentation

## 10. Evidence

Configuration screenshots show:

- Repair Request table properties
- Table inheritance
- Dictionary entries and field types
- Equipment reference relationship
- Resolution tracking fields
- Access control records

## Conclusion

The Repair Request table provides the data foundation for MediTrack's equipment repair management functionality.

The documented configuration and functional test results demonstrate the use of ServiceNow table inheritance, reference relationships, task management fields, and business logic validation.
