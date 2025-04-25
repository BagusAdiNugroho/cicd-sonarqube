# SonarQube Integration Sample Project

This project demonstrates integration of SonarQube with GitHub Actions for continuous code quality analysis.

## Setup Instructions

1. Fork this repository
2. Configure the following GitHub Secrets in your repository settings:
   - `SONAR_TOKEN`: Authentication token from your SonarQube server
   - `SONAR_HOST_URL`: URL of your SonarQube server (e.g., http://167.172.236.182:9000)
   - `SONAR_PROJECT_KEY`: Project key defined in SonarQube

## Running Locally

```bash
mvn clean verify sonar:sonar