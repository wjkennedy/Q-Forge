# Jira Forge App for Q-Factor Calculation

This repository contains resources and documentation for developing a Forge app designed to measure the deviation from the optimum of Jira tickets using the Q-factor algorithm. The Q-factor aims to enhance the efficiency and effectiveness of project or group work management by considering various meta-state factors.

## Overview

The Forge app calculates the Q-factor by analyzing key aspects such as creation time, activity level, similarity to other work, components, and text similarity. This approach aids in accurately assigning Jira issues to the appropriate project or task, streamlining the work management process.

## Resources

Included in this repository are Swagger and API specification files that outline the structure and endpoints available for interacting with Jira's API. Additionally, a CSV file lists the necessary OAuth scopes for the app.

- `jsm.swagger.v3.json`: Jira Service Management API specification.
- `swagger-v3.v3.txt`: General API specification for version 3.
- `user-api.swagger.v3.txt`: User management API specification.
- `jirascopes.csv`: Required OAuth scopes for accessing Jira data.

## Development Guide

### Setting Up

1. **Initialize Your Forge App**: Use the Forge CLI to create a new app, selecting a template suitable for Jira apps.
2. **Configure OAuth Scopes**: Modify the `manifest.yml` file to include the necessary permissions for accessing Jira data.
3. **Implement the Q-Factor Algorithm**: Develop backend logic to calculate the Q-factor based on the provided formulas and criteria.

### Implementing App Logic

- Fetch issue details, work logs, and perform similarity analysis using Jira's REST API.
- Calculate meta-state factors and aggregate them into the Q-factor score.
- Display the Q-factor score within the Jira issue panel for easy access and analysis.

### Deployment

Deploy and install your Forge app in a Jira environment to test its functionality and ensure it meets the project requirements.

## Contribution

Contributions to this project are welcome. Please ensure to follow the best practices for code quality and security.

## License

Specify your project's license here, commonly MIT or Apache 2.0 for open-source projects.

