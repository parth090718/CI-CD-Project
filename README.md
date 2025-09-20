# CI-CD-Project

# Overview---------------------------
This repository outlines an automated CI/CD pipeline using leading DevOps tools to streamline code integration, quality assurance, security scanning, containerization, and deployment�.
-------------------------------------------------------------------------------------------------------------------
# Pipeline Workflow---------------------------
1.GitHub Commit
Developers commit code changes to GitHub, triggering the pipeline via webhook.
2. Jenkins Automation
Jenkins orchestrates the workflow and initiates the process when a commit is detected.
3. Build & Unit Tests (Maven)
Jenkins uses Maven to compile the source code and run unit tests for validation. 
4. Code Quality Check (SonarQube)
SonarQube performs static code analysis and ensures code quality and standards compliance.
5. Security Scan (Dependency-Check)
Dependency-Check scans for security vulnerabilities in project dependencies. 
6. Docker Build & Publish (Maven + Docker)
Maven triggers Docker to build and publish the container image if previous checks are successful.
7. Docker Image Scan (Trivy)
Trivy scans the Docker image for vulnerabilities before deployment.
8. Deployment
Secure images are deployed to a Docker container runtime.
-------------------------------------------------------------------------------------------------------------------
# Tools Used------------------------------
:GitHub (Source control)
:Jenkins (CI/CD orchestration) 
:Maven (Build automation)
:SonarQube (Code quality check)
:Dependency-Check (Security scan)
:Docker (Containerization)
:Trivy (Image vulnerability scanning)
