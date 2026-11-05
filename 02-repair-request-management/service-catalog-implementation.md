
# MediTrack — Service Catalog Implementation

## Project Information

**Application:** MediTrack  
**Platform:** ServiceNow  
**Component:** Report Faulty Equipment  
**Implementation Type:** Record Producer  
**Role:** Repair Request Lead (Member 2)

## 1. Overview

The Report Faulty Equipment Record Producer provides a user-facing interface for submitting medical equipment repair requests.

It is configured within the MediTrack application and targets the custom Repair Request table.

## 2. Record Producer Configuration

| Property | Value |
|----------|-------|
| Name | Report Faulty Equipment |
| Application | MediTrack |
| Type | Record Producer |
| Target Table | Repair Request |
| State | Published |
| Active | Yes |
| Owner | Adline Nwanyanwu |
| Redirect | Generated task record |
| Variables | 6 |

## 3. Purpose

The Record Producer provides a structured way for users to report damaged or malfunctioning hospital equipment.

It collects equipment details, issue descriptions, and priority-related information to support repair request processing.

## 4. Catalog Variables

| Variable | Internal Name | Type | Order |
|----------|---------------|------|-------|
| Equipment Record | equipment_record | Reference | 100 |
| Department | department | Single Line Text | 200 |
| Short Description | short_description | Single Line Text | 300 |
| Description | description | Multi Line Text | 400 |
| Impact | impact | Select Box | 500 |
| Urgency | urgency | Select Box | 600 |

## 5. Target Table Integration

The Record Producer is configured to generate records in:

`x_1234_meditrack_repair_request`

The target table extends the ServiceNow Task table.

Variable-to-field mapping and successful record creation will be documented through submission testing.

## 6. Knowledge Base Integration

The Record Producer description includes links to MediTrack knowledge articles:

- How to report faulty equipment
- Patient monitor basic troubleshooting
- What happens after you submit a repair request

These resources provide guidance before users submit repair requests.

## 7. User Experience

The Record Producer is designed to:

1. Provide a clear equipment reporting interface.
2. Collect relevant repair request information.
3. Capture impact and urgency.
4. Direct users to supporting knowledge articles.
5. Generate a Repair Request record upon successful submission and mapping.

## 8. Technical Skills Demonstrated

- ServiceNow Service Catalog
- Record Producer Configuration
- Catalog Variables
- Reference Variables
- Select Box Variables
- Custom Table Integration
- Knowledge Base Linking
- Technical Documentation

## 9. Verification Status

Confirmed from configuration screenshots:

- Record Producer exists
- Record Producer is published and active
- Target table is Repair Request
- Six variables are configured
- Knowledge article links are included
- Redirect is set to Generated task record

Pending verification:

- Variable-to-field mappings
- Successful submission
- Generated record field values
- Post-submission behavior

## 10. Conclusion

The Report Faulty Equipment Record Producer provides a structured catalog-based entry point for medical equipment repair reporting within MediTrack.

Its configuration demonstrates ServiceNow Record Producer setup, catalog variable design, and integration with a custom task-based application.
