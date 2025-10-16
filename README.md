# Github User Creation Date

## Description
This application allows users to enter a GitHub username and an optional token to fetch and display the account creation date in YYYY-MM-DD UTC format.

## Features
- Form for entering GitHub username and optional token
- Fetches user data from GitHub API
- Displays the account creation date in a formatted manner
- Caches the last successful lookup in localStorage and repopulates the form on load

## Round 2 Updates
- Added functionality to cache the last successful lookup in localStorage under "github-user-${seed}"
- Repopulates the form on load with the cached data

## Installation
Simply open the index.html file in a web browser to run the application.

## Usage
1. Enter a GitHub username in the designated field.
2. Optionally, provide a token for authorization.
3. Click on the "Get Account Creation Date" button to fetch and display the creation date.

## Technologies Used
- Bootstrap v5.1.3 (CSS and JS)
- Fetch API for making HTTP requests

## License
MIT