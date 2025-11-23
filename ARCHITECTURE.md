# Lewis Instructional Software Architecture — Solo Phase 1

## 1. Overview
A client-heavy single page React application demonstrating the core UI flows: Lions, Tigers, Bears. Deployed as a static website via Azure Static Web Apps. All source code in a GitHub repo. CI/CD deploys automatically on push to `main`.

## 2. Architecture Diagram

```mermaid
flowchart LR
  Dev[Your Laptop] --> GitHub[GitHub Repo]
  GitHub --> Azure[Azure Static Web App CI/CD]
  Azure --> Browser[User Browser]

