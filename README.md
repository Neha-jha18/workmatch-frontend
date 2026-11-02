# workmatch-frontend
Frontend (React + TypeScript) for the  WorkMatch (Skill-to-Opportunities platform).
# Skill-to-Opportunities: Frontend

## Project Summary

Skill-to-Opportunities is a web platform designed to help students and early-career candidates showcase their skills through real-world projects and discover relevant career opportunities.

The frontend provides an intuitive interface where candidates can build their skill portfolios, explore internships and jobs, view explainable skill-match scores, identify missing skills, and apply for opportunities. Employers can manage job postings and review applications, while visitors can browse public portfolios and opportunities.

## Tech Stack

- **Frontend Framework:** React.js
- **Language:** JavaScript
- **Styling:** CSS
- **API Integration:** REST API
- **Backend:** Django
- **API Documentation:** Swagger (OpenAPI)
- **Version Control:** Git and GitHub

## Project Setup

Setup instructions will be added once the initial frontend project structure and dependencies are established.

## Environment Variables

The frontend will use environment variables to manage API configuration and other application-level settings.

Expected variables include:

| Variable | Description |
|---|---|
| `VITE_API_BASE_URL` | Base URL of the Django backend API |

A `.env.example` file will be provided as the project configuration evolves.

## How to Run

Installation instructions, dependency setup, environment configuration, and development server commands will be documented once the frontend setup is complete.

## How to Test

Frontend testing instructions and configurations will be added as the project develops.

## Core Features

### Candidate Features
- **Candidate Dashboard:** Overview of profile information, skills, applications, and opportunities.
- **Skill Portfolio:** Add, update, and manage skills.
- **Project Showcase:** Add project evidence through GitHub repositories, live demos, and Figma links.
- **Opportunity Discovery:** Browse and search available internships, jobs, and entry-level positions.
- **Skill Match Visualization:** View match scores and understand matched and missing skills.
- **Application Management:** Apply for opportunities using selected projects and track application status.

### Employer Features
- **Employer Dashboard:** Manage company information and published opportunities.
- **Opportunity Management:** Create, update, and manage job and internship postings.
- **Skill Requirements:** Define required and preferred skills for each opportunity.
- **Application Review:** View and evaluate applications submitted to the employer's own openings.
- **Candidate Profiles:** Review candidate portfolios and supporting project evidence.

### Public Features
- Browse publicly available opportunities.
- Explore public candidate portfolios.
- View platform information and features.

## UI/UX Principles

- Maintain a clean, responsive, and user-friendly interface.
- Provide intuitive navigation for candidates and employers.
- Display skill-match scores with clear explanations.
- Use consistent typography, spacing, colors, and reusable UI components.
- Provide appropriate loading, error, empty, and success states.
- Ensure accessibility across different screen sizes and devices.

## Development Principles

- Build reusable and maintainable React components.
- Maintain a modular frontend folder structure.
- Separate API services from UI components.
- Manage application state consistently.
- Implement role-based navigation and protected routes.
- Validate user inputs before submitting forms.
- Integrate frontend components with the Django REST API.
- Keep sensitive configuration outside the source code.

## Project Status

🚧 Frontend development in progress.
