# FreelanceTN — Database Design

## 1. USERS
- id (Primary Key)
- full_name
- email (Unique)
- password
- role (FREELANCER or COMPANY)
- created_at

## 2. FREELANCER_PROFILES
- id (Primary Key)
- user_id (Foreign Key → USERS.id)
- description
- skills
- experience
- cv_url

## 3. COMPANIES
- id (Primary Key)
- user_id (Foreign Key → USERS.id)
- company_name
- website
- description

## 4. JOBS
- id (Primary Key)
- company_id (Foreign Key → COMPANIES.id)
- title
- description
- salary
- status
- created_at

## 5. APPLICATIONS
- id (Primary Key)
- job_id (Foreign Key → JOBS.id)
- freelancer_id (Foreign Key → FREELANCER_PROFILES.id)
- message
- status
- applied_at
