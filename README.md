# Personal Jira Integration

This project is designed to integrate with Jira's API and perform tasks such as fetching issue details.

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Sudhakarselvam12/personal-jira-integration.git
   cd personal-jira-integration

2. Install dependencies:
    ```bash
    npm install

3. Create a .env file in the root directory with the following configuration:
    ```env
    JIRA_API_URL=your-jira-api-url
    JIRA_USERNAME=your-jira-username
    JIRA_API_TOKEN=your-jira-api-token

4. Run the app:
    ```bash
    node index.js

Usage
This project fetches Jira data and logs it to the console.

You can extend this project by adding more Jira API calls, error handling, etc.

Contributing
Feel free to fork and submit PRs! Issues and contributions are welcome.