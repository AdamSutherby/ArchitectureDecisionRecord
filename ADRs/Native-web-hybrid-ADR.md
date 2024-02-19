# Architecture Decision Record: Native, Web or Hybrid

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

We have a constraint on backend languages that are unusable with

### Positions

The following languages were considered:

- Go
- Javascript
- Next.js
- Typescript

### Argument

Node.js is familair with our current team and align's with the client's needs.

### Implications

Team may need to learn and use new libaries to help reach the client's needs for this mobile application.

## Related

### Related Decisions

### Related requirements

### Related artifacts

### Related principles

## Notes
