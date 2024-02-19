# Architecture Decision Record: Backend Language

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

To determine the most suitable backend language(s) for our mobile application.

### Decision

We are choosing Node.js as our backend programming language.

### Status

Decided.

## Details

### Assumptions

- Will be able to recieve data from the restaurants' inventory management systems to keep the app up to date.
- All current payment gateway options considered will not interfere with our backend.
- Location tracking data will be able to be accurate and up to date with the backend framework.

### constraints

We have a constraint on backend languages that are unusable or unoptimal with needed tools such as GPS or mass database storage.

### Positions

The following languages were considered:

- Go
- Javascript
- Next.js
- Node.js
- Typescript

### Argument

Node.js is familair with our current team and align's with the client's needs.

### Implications

Team may need to learn and use new libaries to help reach the client's needs for this mobile application.

## Related

### Related Decisions

The frontend language (currently React.js).

The descision of the app being a web hybrid.

### Related requirements

Accurate and real time updates to from the restaurants' inventory management systems

### Related artifacts

API Documentation and System Architecture Diagrams.

### Related principles

Preformance, flexibility and maintainability .

## Notes

Consider revisiting related decisions and requirements during future architecture reviews to ensure alignment with project goals and constraints.
