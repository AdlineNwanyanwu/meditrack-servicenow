
# MediTrack — Record Producer Submission Testing

## Project Information

**Application:** MediTrack  
**Platform:** ServiceNow  
**Component:** Report Faulty Equipment  
**Role:** Repair Request Lead (Member 2)

## 1. Test Objective

Validate that the Report Faulty Equipment Record Producer can generate a Repair Request record with the expected equipment, department, priority, and assignment information.

## 2. Test Scenario

A hospital staff member reports a malfunctioning ICU patient monitor through the Service Catalog.

The request should create a Repair Request record for tracking and repair management.

## 3. Test Results

**Test ID:** RP-001  
**Test Type:** Functional Testing  
**Generated Record:** REP002093  
**Overall Result:** PASS

| Validation | Actual Result | Status |
|------------|---------------|--------|
| Repair Request creation | REP002093 generated | PASS |
| Equipment reference | EQ0001 | PASS |
| Department | ICU | PASS |
| Impact | 1 - High | PASS |
| Urgency | 1 - High | PASS |
| Priority calculation | 1 - Critical | PASS |
| Assignment group | MediTrack Biomedical Engineering | PASS |
| Initial state | Open | PASS |

## 4. Generated Record Details

**Ticket Number:** REP002093

**Equipment Record:** EQ0001

**Department:** ICU

**Short Description:** Monitor Freezing

**Description:** Not displaying any vitals

**Impact:** 1 - High

**Urgency:** 1 - High

**Calculated Priority:** 1 - Critical

**Assignment Group:** MediTrack Biomedical Engineering

**State:** Open

## 5. Technical Validation

The generated Repair Request demonstrates:

- Successful creation of a Repair Request record
- Equipment reference association
- Department population
- Priority calculation from impact and urgency
- Assignment to the Biomedical Engineering group
- Initial request state tracking

The resulting field values were verified on the generated record.

## 6. Related Business Rule Tests

This submission supports previously documented testing of:

- BR-001: Automatic Priority Calculation
- BR-002: Equipment-Based Auto Assignment

Additional lifecycle and closure tests are documented separately.

## 7. Evidence

Supporting screenshots:

- Report Faulty Equipment Record Producer
- Catalog variables
- Catalog submission form
- Generated Repair Request REP002093

## 8. Conclusion

The Report Faulty Equipment Record Producer successfully generated Repair Request REP002093.

The generated record displayed the expected equipment reference, department, impact, urgency, calculated priority, and assignment group.

**Test Result: PASS**
