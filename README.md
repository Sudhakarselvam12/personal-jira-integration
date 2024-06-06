# muskan-assignment
# Jira Issues List React Component

This React component, `IssuesList` in the HomeContainer, is designed to fetch and display a paginated list of Jira issues using the Jira API. It allows users to navigate through pages and adjust the number of items displayed per page.

## Installation
1. Install necessary dependencies:
  - Package.json file is provided. Just install the package with npm i command
  - Follow the same step for both frontend and backend.

## ENV VAriables
2. Specify necessary ENV variables in backend for accessing JIRA APIs.
   - Required ENV variables
    - REACT_APP_JIRA_API_TOKEN=<your-jira-api-token>
    - REACT_APP_JIRA_BASE_URL=<your-jira-base-url>
    - REACT_APP_JIRA_PROJECT_KEY=<your-jira-project-key>
    - REACT_APP_JIRA_USER_NAME=<your-jira-user-name>
    - PORT=<port>>

3. Ensure your project has appropriate configurations to support the usage of Material-UI components.