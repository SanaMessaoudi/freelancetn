# FreelanceTN — ERD Design

## Entities
- USERS
- FREELANCER_PROFILES
- COMPANIES
- JOBS
- APPLICATIONS

## Relationships
1. USERS → FREELANCER_PROFILES: One-to-One
2. USERS → COMPANIES: One-to-One
3. COMPANIES → JOBS: One-to-Many
4. JOBS → APPLICATIONS: One-to-Many
5. FREELANCER_PROFILES → APPLICATIONS: One-to-Many

## Objective
Represent the database tables and their relationships before implementation.
