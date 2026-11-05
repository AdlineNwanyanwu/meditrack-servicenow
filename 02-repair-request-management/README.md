
# MediTrack — Repair Request Management

## My Role: Repair Request Lead (Member 2)

**Platform:** ServiceNow  
**Application:** MediTrack  
**Team:** Langston Team — Group 2  
**Role:** Repair Request Lead

## Overview

As Repair Request Lead, I worked on the development, configuration, and functional testing of the Repair Request Management component within MediTrack.

The component supports medical equipment repair reporting, request tracking, assignment, prioritization, and resolution management.

## My Technical Contributions

### 1. Custom Table Configuration
- Configured the Repair Request table extending Task.
- Worked with custom fields and reference relationships.
- Connected repair requests to Medical Equipment records.

[View Table Configuration](repair-request-table-configuration.md)

### 2. Form Configuration
- Configured the Repair Request form.
- Organized equipment, reporting, priority, assignment, and resolution fields.
- Configured mandatory fields for data entry.

[View Form Configuration](repair-request-form-configuration.md)

### 3. List Configuration
- Configured the Repair Request list view.
- Displayed ticket numbers, priorities, states, assignments, and descriptions.
- Supported record search, filtering, and navigation.

[View List Configuration](repair-request-list-configuration.md)

### 4. Business Rule Testing

Validated five functional scenarios:

| Test ID | Feature | Result |
|---------|---------|--------|
| BR-001 | Automatic Priority Calculation | PASS |
| BR-002 | Equipment-Based Auto Assignment | PASS |
| BR-003 | Closure Validation | PASS |
| BR-004 | Automatic Resolution Tracking | PASS |
| BR-005 | Repair Request Lifecycle | PASS |

**Results: 5/5 Passed**

[View Business Rule Testing](business-rule-testing.md)

### 5. Service Catalog Implementation

Configured the **Report Faulty Equipment** Record Producer.

Features include:
- Six catalog variables
- Equipment reference selection
- Department and issue details
- Impact and urgency selection
- Links to supporting knowledge articles
- Integration with the Repair Request table

[View Service Catalog Implementation](service-catalog-implementation.md)

### 6. Record Producer Submission Testing

Successfully generated Repair Request **REP002093**.

Verified:
- Equipment Record: EQ0001
- Department: ICU
- Impact: 1 - High
- Urgency: 1 - High
- Priority: 1 - Critical
- Assignment Group: MediTrack Biomedical Engineering

**Test Result: PASS**

[View Submission Test](record-producer-submission-testing.md)

## ServiceNow Skills Demonstrated

- Custom Table Configuration
- Task Table Inheritance
- Forms and Lists
- Reference Fields
- Service Catalog
- Record Producers
- Business Rule Testing
- Priority Calculation
- Assignment Routing
- Functional Testing
- Technical Documentation

## Project Status

Repair Request component configuration and documented functional tests completed.

Additional integration testing and final application validation may be performed as the overall MediTrack project progresses.
