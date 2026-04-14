# API Integration Test

This page verifies that the **Docs-as-Code** pipeline is fully functional. If you can see this, the CI/CD trigger successfully built the latest commit.

## Endpoint Overview
This is a mock representation of how we will document your API language tools.

| Endpoint | Method | Description | Focus Area |
| :--- | :--- | :--- | :--- |
| `/glossary/terms` | `GET` | Retrieve all API terms | Vocabulary |
| `/coaching/book` | `POST` | Schedule a 1:1 session | Career Growth |
| `/auth/login` | `POST` | User authentication | Security |

## Technical Writing Samples
!!! info "Documentation Standard"
    We are using **Material for MkDocs**. This allows us to use high-visibility callouts (admonitions) to separate technical data from coaching advice.

### Implementation Checklist
- [x] Create Markdown file
- [x] Push to GitHub
- [x] Automated build starts
- [x] Site updates globally