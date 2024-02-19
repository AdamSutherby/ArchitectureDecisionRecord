# Architecture Decision Record: Data Storage

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

To determine the most suitable method for storing the variety of data collected by this app

### Decision

We are choosing an Microsoft Azure Database

### Status

Decided.

## Details

### Assumptions

- The amount of data will be within the limits of of the database
- The budget will allow the prolong use of the database
- Private infomation will be secure using the database

### constraints

The database must be able to recieve and store mass amounts of data effieciently.

### Positions

The following database providers were considered:

- Amazon Aurora
- Google Cloud SQL
- Microsoft Azure

### Argument

Microsoft Azure currently aligns with the estimated needs of data storage based on possible user base.

### Implications

May have to follow certain restrictions when publishing the App with the inclsuion on this database.

## Related

### Related Decisions

The descision of the app being a web hybrid.

### Related requirements

Accurate and real time updates to from the restaurants' inventory management systems.

### Related artifacts

Data model Diagram.

### Related principles

Data security and performance.

## Notes
