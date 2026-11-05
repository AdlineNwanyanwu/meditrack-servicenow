
# MediTrack — Repair Request Form Configuration

## Project Information

**Application:** MediTrack  
**Platform:** ServiceNow  
**Module:** Repair Request Management  
**Role:** Repair Request Lead (Member 2)

## 1. Overview

The Repair Request form provides an interface for creating and managing medical equipment repair requests within MediTrack.

The form combines equipment identification, request details, priority assessment, assignment information, and resolution tracking.

## 2. Form Configuration

**Table:** x_1234_meditrack_repair_request  
**Parent Table:** Task  
**Interface:** ServiceNow Form  
**Example Ticket Number:** REP002092

## 3. Form Fields

### Equipment and Reporting Information

| Field | Purpose |
|-------|---------|
| Ticket Number | Identifies the repair request |
| Equipment Record | References the affected equipment |
| Department | Identifies the reporting department |
| Reported By | Identifies the reporter |
| Reported Date | Records the reporting date |

### Priority and Assignment

| Field | Purpose |
|-------|---------|
| State | Tracks repair request status |
| Impact | Captures business impact |
| Urgency | Captures urgency |
| Priority | Indicates calculated priority |
| Approval | Tracks approval status |
| Assignment group | Identifies the responsible support group |
| Assigned to | Identifies the assigned user |

### Repair and Resolution Information

| Field | Purpose |
|-------|---------|
| Short description | Summarizes the issue |
| Description | Provides detailed issue information |
| Repair Notes | Records repair activities |
| Resolution Notes | Documents the resolution |
| Resolved At | Stores resolution timestamp |
| Resolved By | Identifies the resolving user |

## 4. Mandatory Fields

The new-record form visibly marks the following fields as mandatory:

- Equipment Record
- Department
- Priority
- Short description

These fields support consistent repair request data entry.

## 5. Form Layout

The form presents:

1. Equipment and reporting information
2. Request status and priority information
3. Assignment details
4. Issue description
5. Repair notes
6. Resolution tracking

This arrangement makes important request information accessible within one form.

## 6. Business Logic Validation

The following functional tests have been recorded as passed:

- BR-001: Automatic Priority Calculation
- BR-002: Equipment-Based Auto Assignment
- BR-003: Closure Validation
- BR-004: Automatic Resolution Tracking
- BR-005: Repair Request Lifecycle

See [Business Rule Testing](business-rule-testing.md).

## 7. Technical Skills Demonstrated

- ServiceNow Form Configuration
- Custom Application Development
- Reference Fields
- Mandatory Field Configuration
- Task-Based Record Management
- Priority and Assignment Configuration
- Resolution Tracking
- Functional Testing

## 8. Supporting Evidence

A screenshot of the Repair Request new-record form documents:

- Visible form layout
- Configured fields
- Mandatory field indicators
- Default values
- Ticket numbering format

## 9. Conclusion

The Repair Request form provides the user-facing interface for reporting, assigning, and tracking medical equipment repair requests in MediTrack.

The documented form configuration demonstrates practical ServiceNow form design and task-management configuration.
