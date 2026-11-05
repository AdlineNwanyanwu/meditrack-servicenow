
# MediTrack — Business Rule Testing

## Project Information

**Project:** MediTrack — Medical Equipment Management  
**Platform:** ServiceNow  
**Module:** Repair Request Management  
**Role:** Repair Request Lead (Member 2)  
**Team:** Langston Team — Group 2  
**Testing Status:** Completed — 5 Test Cases Passed

## 1. Overview

This document records functional testing performed on the Repair Request Management component of MediTrack.

Testing focused on business logic, automatic field updates, assignment routing, validation requirements, and repair request lifecycle transitions.

## 2. Test Objectives

- Verify automatic priority calculation.
- Validate equipment-based assignment.
- Prevent closure without resolution documentation.
- Confirm automatic resolution tracking.
- Validate repair request state transitions.

## 3. Test Results Summary

| Test ID | Feature | Expected Behavior | Result |
|---------|---------|-------------------|--------|
| BR-001 | Automatic Priority Calculation | Priority calculated from Impact and Urgency | PASS |
| BR-002 | Equipment-Based Auto Assignment | Biomedical equipment routes to Biomedical Engineering | PASS |
| BR-003 | Closure Validation | Prevent closure without Resolution Notes | PASS |
| BR-004 | Automatic Resolution Tracking | Populate Resolved At and Resolved By | PASS |
| BR-005 | Repair Request Lifecycle | In Progress → Resolved → Closed | PASS |

**Total Test Cases:** 5  
**Passed:** 5  
**Failed:** 0  
**Pass Rate:** 100%

## 4. Detailed Test Cases

### BR-001 — Automatic Priority Calculation

**Objective:** Verify that repair request priority is calculated automatically.

**Expected Result:**
Priority is determined based on Impact and Urgency.

**Actual Result:**
The priority calculation behaved as expected during testing.

**Status:** PASS

### BR-002 — Equipment-Based Auto Assignment

**Objective:** Verify that repair requests are assigned to the appropriate support group based on equipment classification.

**Expected Result:**
Biomedical equipment is automatically routed to the Biomedical Engineering assignment group.

**Actual Result:**
The assignment behavior matched the expected routing.

**Status:** PASS

### BR-003 — Closure Validation

**Objective:** Ensure repair requests cannot be closed without required resolution documentation.

**Expected Result:**
The system prevents closure when Resolution Notes are missing.

**Actual Result:**
Closure validation behaved as expected.

**Status:** PASS

### BR-004 — Automatic Resolution Tracking

**Objective:** Validate automatic population of resolution tracking fields.

**Expected Result:**
The system populates:
- Resolved At
- Resolved By

**Actual Result:**
Both resolution tracking fields were populated as expected.

**Status:** PASS

### BR-005 — Repair Request Lifecycle

**Objective:** Verify the repair request lifecycle.

**Expected Result:**
A repair request transitions through:

In Progress → Resolved → Closed

**Actual Result:**
The expected lifecycle transitions were successfully tested.

**Status:** PASS

## 5. Testing Outcome

All five reported test cases passed.

The results demonstrate successful functional validation of:

- Priority calculation logic
- Equipment-based assignment routing
- Closure requirements
- Resolution tracking
- Repair request lifecycle transitions

These results represent the documented test scenarios and do not constitute complete end-to-end application acceptance testing.

## 6. Skills Demonstrated

- ServiceNow Business Rule Testing
- Functional Testing
- Workflow Validation
- Data Validation
- Assignment Group Routing
- Record Lifecycle Management
- Troubleshooting
- Technical Documentation

## 7. Supporting Evidence

Screenshots and additional testing evidence may be added to demonstrate:

- Priority calculation results
- Biomedical Engineering assignment
- Closure validation behavior
- Resolution tracking fields
- Repair request state transitions

## 8. Conclusion

As Repair Request Lead, I validated five functional scenarios within MediTrack's Repair Request Management component.

All five test cases passed, demonstrating that the tested business logic and lifecycle behavior met their defined expectations.
