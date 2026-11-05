
# MediTrack — Repair Request List Configuration

## Project Information

**Application:** MediTrack  
**Platform:** ServiceNow  
**Module:** Repair Request Management  
**Role:** Repair Request Lead (Member 2)  
**Team:** Langston Team — Group 2

## 1. Overview

The Repair Request list provides a centralized view of medical equipment repair requests within MediTrack.

It enables users to review repair records, monitor priorities, identify assigned technicians, and track request status.

## 2. List Configuration

**Table:** x_1234_meditrack_repair_request  
**Interface:** ServiceNow List View

The visible list includes the following columns:

| Column | Purpose |
|--------|---------|
| Ticket Number | Unique repair request identifier |
| Priority | Displays repair request priority |
| State | Displays current request status |
| Assigned to | Identifies the assigned technician |
| Short description | Summarizes the equipment issue |
| Task type | Identifies the record type |

## 3. Priority Visibility

The list displays multiple priority levels, including:

- 1 - Critical
- 2 - High
- 3 - Moderate
- 4 - Low
- 5 - Planning

This supports visibility into the urgency and relative importance of repair requests.

## 4. Request Status Tracking

The screenshot confirms repair requests in the following states:

- Open
- Resolved
- Closed

These states support monitoring repair requests through their lifecycle.

## 5. Assignment Tracking

The Assigned to column identifies the technician responsible for a repair request.

The screenshot shows both assigned and unassigned records.

This provides visibility into assignment status and supports identification of requests requiring attention.

## 6. Search and Navigation

The list interface includes:

- Column-based search
- Filter controls
- Sortable columns
- Record navigation
- List configuration options
- New record creation

These capabilities help users locate and manage repair requests efficiently.

## 7. Sample Test Records

The list contains repair requests representing different equipment-related scenarios, including:

- ICU patient monitor issues
- Ventilator alarm failures
- Patient monitoring equipment malfunctions
- HVAC cooling problems
- Network connectivity issues
- Infusion pump assignment testing

These sample records provide data for functional testing and demonstration.

## 8. Related Testing

The Repair Request component has documented passing test results for:

- Automatic priority calculation
- Equipment-based assignment
- Closure validation
- Resolution tracking
- Repair request lifecycle

See [Business Rule Testing](business-rule-testing.md).

## 9. Skills Demonstrated

- ServiceNow List Configuration
- Task Management
- Record Navigation
- Priority Tracking
- Assignment Tracking
- Functional Testing
- Technical Documentation

## 10. Supporting Evidence

A screenshot of the Repair Request list demonstrates:

- Configured list columns
- Sample repair records
- Multiple priority levels
- Request states
- Assigned and unassigned records
- Search and filtering interface

## Conclusion

The Repair Request list provides a structured interface for reviewing and tracking equipment repair requests.

Its configuration supports request visibility, assignment monitoring, and operational tracking within MediTrack.
