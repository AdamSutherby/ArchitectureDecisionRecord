# Architecture Decision Record: Permissions

Contents:

- Summary
  - Issue
  - Decision
  - Status
- Details
  - Assumptions
  - Constraints
  - Positions
  - Argument
  - Implications
- Related
  - Related decisions
  - Related requirements
  - Related artifacts
  - Related principles
- Notes

## Summary

### Issue

To determine what permissions the user will have to enable to use the application.

### Decision

We will need the user's location (GPS).

### Status

Decided.

## Details

### Assumptions

- Users are comfortable sharing their location data.
- Location data is essential for providing accurate delivery services.

### constraints

- Privacy concerns regarding the collection of location data.
- Compliance with data protection regulations (e.g., GDPR).

### Positions

The following permissions were considered:

- Location (GPS)
- Camera (for scanning QR codes, if applicable)
- Storage (for saving preferences or caching data)
- Network (for accessing the internet)

### Argument

Location permission is crucial for providing efficient and accurate food delivery services. It enables features such as real-time order tracking and optimizing delivery routes.

### Implications

Potential privacy concerns and the need for transparent data handling policies.

## Related

### Related Decisions

None

### Related requirements

The application must have access to the user's and drivers location to provide delivery services effectively.

### Related artifacts

Privacy policy

### Related principles

Principle of least privilege: Only request permissions necessary for the app's functionality.

## Notes

Location data should be handled securely and only used for providing delivery services. Regular audits of data handling practices are recommended to ensure compliance and build trust with users.
