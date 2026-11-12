# DriveNow — Database Design Assignment

## Student Information

- **Name:** Mahmoud Mohamed Elsafty

- **Group:** G1

---

## Project Overview

This repository contains the Database Design assignment for the **DriveNow Car Rental System**.

The assignment covers the analysis and design of the database based on the provided Software Requirements Specification (SRS).

The design is divided into four main parts:

- **Part A — ERD:** Entity Relationship Diagram using Chen notation.
- **Part B — Schema Mapping:** Mapping the ERD into relational database tables.
- **Part C — Questions, Assumptions & Contradictions:** Documenting questions, design assumptions, and conflicting requirements found in the SRS.
- **Part D — Business Rules:** Identifying business rules that cannot be enforced using basic database constraints alone.

---

## Repository Structure

```text
DriveNow/
│
├── README.md
├── DriveNow.drawio
│
└── exports/
    ├── 1-ERD-*.png
    ├── 2-Schema-*.png
    ├── 3-Questions-Assumptions.png
    └── 4-Business-Rules.png
```

---

## Project Deliverables

### Part A — Entity Relationship Diagram (ERD)

- Designed using Chen notation.
- Includes entities, attributes, and relationships.
- Identifies primary keys, composite attributes, and multivalued attributes.
- Specifies relationship cardinalities and participation constraints.

### Part B — Relational Schema Mapping

- Maps entities and relationships into relational tables.
- Identifies primary keys and foreign keys.
- Specifies NULL and NOT NULL constraints.
- Includes additional constraints where required.
- Shows foreign key references between tables.

### Part C — Questions, Assumptions & Contradictions

- Documents questions raised while analyzing the SRS.
- Records design assumptions and their related SRS sections.
- Identifies contradictions between different SRS sections.

### Part D — Business Rules Beyond Constraints

- Identifies business rules that cannot be enforced using basic database constraints alone.
- Explains why basic constraints are insufficient.
- Suggests enforcement using triggers, stored procedures, or application logic.

---

## Files and Exports

- `DriveNow.drawio` is the main editable diagram file containing all assignment pages.
- The `exports/` directory contains PNG exports of the individual diagram pages.

---

## Tools Used

- **draw.io (diagrams.net):** Creating and editing ER diagrams and relational schema diagrams.
- **Git & GitHub:** Version control and repository management.

---

## Notes

- The database design is based on the provided DriveNow SRS.
- Any additional design decisions or assumptions are documented in Part C.
- Business rules requiring logic beyond basic database constraints are documented in Part D.