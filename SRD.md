
### `SRD.md`

```md
# SOFTWARE REQUIREMENTS DOCUMENT (SRD)

## Professional Development Portfolio Platform

**Project:** Engr. Mathias Akuma Sarverun Professional Portfolio  
**Document Type:** Software Requirements Document  
**Version:** 1.0  
**Status:** Proposed  
**Primary Platform:** Responsive Web Application

---

# 1. INTRODUCTION

## 1.1 Purpose

This Software Requirements Document defines the functional, non-functional, technical and operational requirements for developing a professional digital portfolio platform for Engr. Mathias Akuma Sarverun.

The system shall transform professional information contained in the source CV and portfolio materials into an interactive, structured and maintainable digital platform.

---

# 2. PRODUCT VISION

The product shall function as more than an online résumé.

It shall provide a structured professional evidence platform capable of communicating:

- professional identity;
- technical qualifications;
- career experience;
- engineering competencies;
- development projects;
- community interventions;
- leadership;
- international exposure;
- awards;
- professional memberships; and
- future professional publications.

---

# 3. BUSINESS OBJECTIVES

The system shall:

### BO-01

Improve presentation of professional credentials.

### BO-02

Make professional experience easier to discover.

### BO-03

Convert project experience into structured case studies.

### BO-04

Present documented community-development interventions.

### BO-05

Provide a credible professional interface for institutional stakeholders.

### BO-06

Create a platform that can be continuously updated without redesigning the entire website.

---

# 4. SCOPE

## 4.1 In Scope

The first release shall include:

- Home page
- Professional profile
- Biography
- Education
- Experience
- Expertise
- Projects
- Community impact
- Leadership
- International exposure
- Awards
- Professional memberships
- Gallery
- Contact
- Administrative content management

## 4.2 Out of Scope for MVP

Unless specifically added during implementation:

- e-commerce
- social networking
- online payment
- public user registration
- recruitment marketplace
- discussion forums
- complex CRM
- unrestricted public document upload

---

# 5. USERS

## 5.1 Public Visitor

Permissions:

- View public content
- Browse projects
- View professional information
- View photographs
- Submit contact enquiry

## 5.2 Administrator

Permissions:

- Login
- Create content
- Edit content
- Publish/unpublish content
- Upload media
- Manage projects
- Manage awards
- Manage education records
- Manage experience
- Manage profile information

## 5.3 System Administrator

Permissions:

- Manage administrator accounts
- Configure system
- Manage security
- Manage backups
- Review audit logs

---

# 6. FUNCTIONAL REQUIREMENTS

## FR-001 — Homepage

The system shall display:

- Professional name
- Professional designation
- Primary professional positioning
- Profile photograph
- Short biography
- Key expertise
- Selected projects
- Selected impact indicators
- Contact call-to-action

---

## FR-002 — Professional Profile

The system shall provide a detailed professional profile containing:

- Name
- Credentials
- Professional designation
- Biography
- Vision
- Professional positioning
- Areas of expertise

---

## FR-003 — Education Management

The administrator shall be able to:

- Add qualification
- Edit qualification
- Delete qualification
- Specify institution
- Specify year
- Specify field/specialization
- Display qualifications chronologically

The initial content shall include the documented B.Eng., M.Eng. and Master of Public Policy qualifications.

---

## FR-004 — Employment Management

The administrator shall be able to manage:

- Organization
- Position
- Start date
- End date
- Location
- Responsibilities
- Achievements
- Supporting evidence

The source CV records Federal Ministry of Agriculture and Food Security experience from 2013 to date.

---

## FR-005 — Expertise

The system shall provide structured expertise categories:

- Agricultural Engineering
- Farm Power and Machinery
- Rural Infrastructure
- Public Policy
- Project Management
- Community Development
- Agricultural Development
- Stakeholder Engagement
- Public Administration
- Procurement
- PPP
- Monitoring and Evaluation

---

## FR-006 — Project Management

Each project record shall contain:

```text
Project ID
Project Title
Sector
Location
Project Type
Role
Start Date
End Date
Problem
Intervention
Scope
Stakeholders
Outputs
Impact
Project Value
Evidence
Images
Documents
Status